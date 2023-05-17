# Ethereum Network Intelligence API
This is the backend service which runs along with ethereum nodes and tracks the network status, fetches information through JSON-RPC and connects through WebSockets to an ethstats-server to feed information.

Available dashboards
https://ethstats.net
https://stats.goerli.net
https://kotti.goerli.net
https://mordor.dash.fault.dev
https://classic.dash.fault.dev

# Prerequisite
client: geth, besu, nethermind, or openethereum
reporting: node js, npm, and pm2
Installation
Clone the repository, install node dependencies, and run the pm2 daemon.

git clone https://github.com/goerli/ethstats-client.git
cd ethstats-client/
npm install
sudo npm install -g pm2
