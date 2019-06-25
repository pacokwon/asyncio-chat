# Asyncio Chat Program

To install dependencies, run:

```pip3 install -r requirements.txt```

Before running server, `redis` and `postgresql` must be running in the background

To run redis(by default):

`redis-server /usr/local/etc/redis.conf --daemonize yes`

To run postgresql(by default):

`pg_ctl -D /usr/local/var/postgres start`

Also, `postgresql` must have table `log` in database `chat`. To automate this particular task, run `./pg.sh`

Finally, `python3 chat.py` to run app

Then access `localhost:8080` to join chat room
