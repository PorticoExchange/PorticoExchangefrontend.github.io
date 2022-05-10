# Portico Exchange-frontend ⚡️

[![Build Status](https://travis-ci.org/BoltzExchange/boltz-frontend.svg?branch=master)](https://travis-ci.org/BoltzExchange/boltz-frontend)

[![Build Status](https://app.travis-ci.com/PorticoExchange/PorticoExchangefrontend.svg?branch=master)](https://app.travis-ci.com/PorticoExchange/PorticoExchangefrontend)

# Requiriments 

Node.Js/NPM and Node Lightning Network or LND

## install
* Clone the repo, install requirements and compile  
`git clone https://github.com/PorticoExchange/PorticoExchangefrontend.git`  
`cd porticoExchangefrontend  && npm i && npm run compile`  
* Start btc & lnd  
`npm run docker:regtest`
* Start LN 
`npm run porticoexchangefrontend:geth`
* Start the app  
`npm run start`

## use
* Visit `http://localhost:9001/getpairs` to see the API.
* Deploy [frontend](https://github.com/pseudozach/boltz-frontend) and visit `http:localhost:3000` to see the GUI.



## acknowledgement
* Portico Exchange is a fork of [Boltz](https://github.com/BoltzExchange/boltz-backend).

## documentation
* [Read the Docs](https://layertwolabs.gitbook.io/portico-exchange/)
