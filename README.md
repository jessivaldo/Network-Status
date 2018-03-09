# Network-Status
Clona.ru Network Status Monitor [musicoin] [vic] [daxx] [dbix] ....


Clone the git repo, then install pm2:

git clone https://github.com/cubedro/eth-net-intelligence-api
cd eth-net-intelligence-api
npm install
sudo npm install -g pm2

nano app.json

"env":
	{
		"NODE_ENV"        : "production", // tell the client we're in production environment
		"RPC_HOST"        : "localhost", // eth JSON-RPC host the default is 8545
		"RPC_PORT"        : "8545", // eth JSON-RPC port
		"LISTENING_PORT"  : "30303", // eth listening port (only used for display)
		"INSTANCE_NAME"   : "", // whatever you wish to name your node
		"CONTACT_DETAILS" : "", // add your contact details here if you wish (email/skype)
		"WS_SERVER"       : "wss://rpc.ethstats.net", // path to eth-netstats WebSockets api server
		"WS_SECRET"       : "", // WebSockets api server secret used for login
	}
