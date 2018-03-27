# Safecoin-omni-explorer

Omni explorer

## Requirements

Node >= 7.x

## Setup

Configure your IP and port in config.js

Run npm install

## How to run

npm start

## How to build UI

```
cd ui
change ui/config to desired ip and port
npm run build
```

built ui version will be copied to /public folder

## URL navigation

#### SAFE interest
http://atomicexplorer.com/#/interest

http://atomicexplorer.com/#/interest/RNdqHx26GWy9bk8MtmH1UiXjQcXE4RKK2P

#### SAFE interest calc
http://atomicexplorer.com/#/interest-calc

#### Explorers list summary
http://atomicexplorer.com/#/summary

#### Balance
http://atomicexplorer.com/#/search

http://atomicexplorer.com/#/search/RNdqHx26GWy9bk8MtmH1UiXjQcXE4RKK2P

#### BarterDEX Charts
http://atomicexplorer.com/#/charts

http://atomicexplorer.com/#/charts/SAFE-BTC

#### BarterDEX Prices
http://atomicexplorer.com/#/prices

http://atomicexplorer.com/#/prices/SAFE-BTC

#### BarterDEX Orderbooks
http://atomicexplorer.com/#/books

http://atomicexplorer.com/#/books/SAFE-BTC

#### BarterDEX coins list
http://atomicexplorer.com/#/coins

## API
#### GET /api/explorer/search?term=RNdqHx26GWy9bk8MtmH1UiXjQcXE4RKK2P

params: txid or pub address

#### GET /api/safe/interest?address=RNdqHx26GWy9bk8MtmH1UiXjQcXE4RKK2P

params: pub address

#### GET /api/explorer/overview

params: none required

#### GET /api/explorer/summary

params: none required

#### GET /api/mm/prices

params: none required

#### GET /api/mm/orderbook

params: none required