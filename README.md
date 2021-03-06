# CurrentCoin Create Frontend

This is the frontend of CurrentCoin Create.

`currentcoin-create-frontend` is just one of three parts which make CurrentCoin Create work. The other parts are `currentcoin-create-backend` and `currentcoin-create-deployer`.

### To run

Clone this repo, then run:

`git submodule update --recursive --init`

Install dependencies and start:

`yarn` (or `npm install`)

`yarn start` (or `npm start`)

### To deploy

This frontend is not deployed directly. This repository is included in `currentcoin-create-backend` as a submodule.

To deploy, commit and push changes to github, then pull within `currentcoin-create-backend`, and follow the deployment instructions there.

### Useful command

To get the latest templates,

`git submodule foreach --recursive 'git pull origin master && git checkout master'`
