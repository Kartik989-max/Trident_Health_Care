# Trident HealthCare 

Tri-Data Record System (Prototype). 
TDRS is a blockchain based data/record storage system that lets you store your data on blockchain itself and not on a regular DB; this makes it less vulnerable to Ransomware attacks and guarantees data availability and security by applying the Blockchain protocols.

To setup the project locally:

```shell
npx hardhat help
npx hardhat test
npx hardhat node
npm install 
npx hardhat run scripts/00-deploy.js
npx hardhat run scripts/01-seeding.js
npm start
```

Note: To expose the local host to the internet, try using cloudflare zero trust (tunneling) service.
