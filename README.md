# Fake medications Identification using Blockchain

## Packages Required:-
- Truffle v5.6.7 (core: 5.6.7)
- Ganache v7.5.0
- Solidity v0.5.16 (solc-js)
- Node 
- npm 7.5.1

## Other Requirements:-
1. Any chromium based browser i.e. Chrome 
2. Metamask browser extension
    
1. Go to the project folder, open terminal there and run following command to install required node_modules:-
```
npm install
```
2. Compile contract source files. (Compilation and deployment can be done using truffle migrate):-
```
truffle compile
```
3. Open Ganache, (to setup local blockchain)
    - crerate new workspace
    - add truffle-config.js  in truffle project 
    - change port to 7545 in server settings (same as port in truffle-config.js)
4. In chrome, open metamask 
   - add new test network using  
        - NETWORK ID (i.e. 5777 ,from Ganache Server settings) 
        - RPC SERVER (i.e HTTP://127.0.0.1:8545 ,from Ganache Server settings
5. In terminal, run following commands:-
- Run migrations to deploy contracts.
```
truffle migrate
```
npm run dev 
```
6. Interact with website
