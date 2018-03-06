# JoorsChain

##JoorsChain: A Blockchain Based Eco-System for Next Level Digital Advertising 
This repo is for JoorsChain development

Joors is an upcoming ad-tech and media/telco platform for offering end-users and
publishers a transparent and non-fraudulent way of viewing ads and downloading apps
and sponsored content. 

Applications are built with Turing-Complete Dapps in Lua and very efficient VM. The Dapps are built on TrueChain consensus network. The JoorsChain provides a rich API which will enable organizations to publish their on applications easier, faster and securely to the market.

JIC is the native token on the JoorsChain network, which enable organization to incentivize end-users, and also make transactions globally with very  low transaction fee.

The Dapp development team will support supported from members of TrueChain, TalkPool, Joors community.

## Development

### Compile
see `doc/compile.md` or use docker compose as described below..

### Run

Step 1: Install `docker-compose`

Step 2: Copy `env.example` to `.env` in same folder. Then, build and run:

`$  docker-compose up --build -d`

Step 3: See if the test page is accessible at `<your docker host IP>:5020` (as the 5020 host port is mapped to container port).
