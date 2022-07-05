# buildspace project -- mint your own nft collection

buildspace project description -- https://buildspace.so/p/mint-nft-collection

Uses hardhat to set up and deploy a solidity contract that
allows a user to a web app create a new NFT in the collection.

Frontend was built on replit.com -- https://nft-starter-project.laurenthelauren.repl.co/

To deploy contract on goerli testnet:
`npx hardhat run scripts/deploy.js --network goerli`

After deploying, make sure to update contract address and
`src/utils/MyEpicNFT.json` in frontend project!
