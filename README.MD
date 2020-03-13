## Docker for HyperLedger Indy development

1. git clone --recurse-submodules <this repository>
2. Build the images using the [docker compose file](docker-compose.yml) with command `$ docker-compose build`
3. Enter the `sdk` client with command `$ docker-compose run sdk`. The `sdk` client will automatically starts the local **indy** server using the command in https://github.com/hyperledger/indy-sdk#1-starting-the-test-pool-on-localhost
