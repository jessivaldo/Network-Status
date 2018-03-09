# Clona.ru Network Status Monitor [musicoin] [vic] [daxx] [dbix] ....


Clone the git repo, then install pm2:

git clone https://github.com/cubedro/eth-net-intelligence-api

cd eth-net-intelligence-api

npm install

sudo npm install -g pm2


# next step (editing app.json)

nano app.json



# next step

pm2 start app.json  ( and next showm and monitoring you node )

pm2 kill ( kill all process pm2 )


# info
#musicoin 

"WS_SERVER" : "clona.ru:3000", // path to etc-netstats WebSockets api server
"WS_SECRET" : "123", // WebSockets api server secret used for login
