# Xenon

## Disclaimer

You might need basic knowledge of python, pip, git and the console of your operating system to run this bot.  
If you need further help you can join the [support discord](https://discord.club/discord), but I won't answer any question regarding the topics above.

[Hosted Version](https://discordbots.org/bot/xenon)

## With Docker (Recommended)

Download and install [docker](https://www.docker.com/) on your operating system.

Build and run it with docker-compose:

1. Download / Clone the repository
2. Edit the `xenon.env` file and change the token
3. You might wanna change some values in `xenon/config.py` e.g. the prefix
4. Create a `xenon/logs` directory for the log files
5. Run `docker-compose build`
6. Run `docker-compose up`

The database and the bot should start up.

## Without Docker

Download and run [rethinkdb](https://www.rethinkdb.com/) and make the port 28015 accessible by the python script.  
Install all dependencies, edit `xenon/config.py` and change the token, run `xenon/launcher.py`.
