# Detail

### Setup

1. `npm install -g typescript`
2. `npx create-react-app ProductValidation --typescript`
3. `cd ProductValidation`
4. `npm install web3`
5. `npm install --save react-router-dom`
6. `npm install --save @types/react-router-dom`
7. `npm install axios`

### Update Dependencies
- `npm outdated`
- `npm update`
- `npm update "react" "react-dom"`
- `npm install <packagename>@latest [<packagename2>@latest]`

### Truffle Setup
1. `npm install -g truffle`
2. `npm install --save @types/jest`
3. `truffle init`
4. Configure networks in truffle-config.js
5. Configure installed solc compiler in truffle-config.js, i.e. `solcjs --version`
6. Write contracts in Solidity and place them in ./contracts
7. Add initial deployment script called ./migration/1_initial_migration.js for the Migration contract previously created with `truffle init`
8. Implement additional deployment scripts for Truffle with increasing prefix numbers in the filename, e.g. 2_deploy_contract.js
9. truffle test [Truffle testing documentation](http://truffleframework.com/docs/getting_started/testing)
10. truffle compile
11. truffle migrate [Truffle migrations documentation](http://truffleframework.com/docs/getting_started/migrations)
