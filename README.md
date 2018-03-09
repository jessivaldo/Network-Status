# Network-Status
Clona.ru Network Status Monitor [musicoin] [vic] [daxx] [dbix] ....


Clone the git repo, then install pm2:

git clone https://github.com/cubedro/eth-net-intelligence-api
cd eth-net-intelligence-api
npm install
sudo npm install -g pm2

nano app.json

[

{
    "name"              : "musicoin",
    "script"            : "app.js",
    "log_date_format"   : "YYYY-MM-DD HH:mm Z",
    "merge_logs"        : false,
    "watch"             : true,
    "max_restarts"      : 10,
    "exec_interpreter"  : "node",
    "exec_mode"         : "fork_mode",
    "env":
    {
      "NODE_ENV"        : "testnode2",
      "RPC_HOST"        : "127.0.0.1",
      "RPC_PORT"        : "8545",
      "LISTENING_PORT"  : "30303",
      "INSTANCE_NAME"   : "name you node",
      "CONTACT_DETAILS" : "skype: mail",
      "WS_SERVER"       : "clona.ru:3000",
      "WS_SECRET"       : "123",
      "VERBOSITY"       : 2
    }
  }
  ]
