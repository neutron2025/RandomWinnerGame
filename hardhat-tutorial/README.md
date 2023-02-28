

```shell

mkdir RandomWinnerGame 
cd RandomWinnerGame 
mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat
npx hardhat  选择Create a Javascript Project
npm install @openzeppelin/contracts
npm install --save @chainlink/contracts

创建合约 RandomWinnerGame.sol
npm install dotenv

创建 .env
配置 QUICKNODE_HTTP_URL="add-quicknode-http-provider-url-here"

PRIVATE_KEY="add-the-private-key-here"

POLYGONSCAN_KEY="polygonscan-api-key-token-here"  从这获得 https://polygonscan.com/myapikey

修改 hardhat.config.js

新建 constants/index.js    从这获得https://blog.chain.link/how-to-get-a-random-number-on-polygon/配置
新建 scripts/deploy.js

npx hardhat compile

npx hardhat run scripts/deploy.js --network mumbai

```
