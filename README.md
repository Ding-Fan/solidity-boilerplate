# solidity-boilerplate
This boilerplate includes two parts: contract-hardhat for contract part, frontend-next for frontend part.

## create a project/repository/path/directory/folder/WhatEverYouCallIt

```sh
mkdir new-project
cd new-project
```

We'd like to keep "contract-hardhat" and "frontend-next" into two seperate (sibling) repositories. For the sake of simple and easy configurations.

### [contract-hardhat](https://github.com/Ding-Fan/solidity-boilerplate-contract-hardhat)

Click link above to get the code

Or make it manually:

```sh
mkdir contract-hardhat
cd contract-hardhat
npx hardhat
...
# choose
  Create an advanced sample project that uses TypeScript
# then go along with those default options
```

- go to file `.prettierrc` , add `"semi": false`

- copy the file `.env.example` and rename to `.env`, add/edit your own config like `GOERLI_URL` and `PRIVATE_KEY`

- to deploy to specific network
  - `npx hardhat run scripts/deploy.js --network <network>`
  - maybe add this to package.json `script`

- `git init` and keep going the git things
  - `git branch -m master main` to rename master to main

### [frontend-next](https://github.com/Ding-Fan/solidity-boilerplate-frontend-next)

Click link above to get the code

Or make it manually:

```sh
yarn create next-app -e with-tailwindcss frontend-next
...
yarn add ethers
```

for reference:
https://github.com/NomicFoundation/hardhat-hackathon-boilerplate/blob/master/frontend/src/components/Dapp.js
