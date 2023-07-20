# oem-blockchain

https://github.com/adhavpavan/BasicNetwork-2.0.git (for default project structure)

1. go to artifacts/channel and replace configtx.yaml, crypto-config.yaml and createartifacts.sh
2. give chmod access to createartifacts.sh and run ./createartifacts.sh
3. cd .. (go to artifacts) and replace docker-compose.yaml
4. docker-compose up -d
5. check -> docker ps -a
6. cd .. (to root directory)
7. ./createartifacts.sh (still in development, but should create all channels, no update to anchor peers yet)
