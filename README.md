These are my notes while working on [Patrick's Javascript Blockchain/Smart Contract FreeCodeCamp Course](https://www.youtube.com/watch?v=gyMwXuJrbJQ).

- On April 22, 2024 successfully compiled and deployed the examples in this `hardhat-erc20-fcc` to a local Hardhat node, and I also deployed the smart contracts to the Ethereum Testnet.

![alt text](./notes/image1.png)

- On April 22, 2024 deployed the following ERC20 token to the following address on Sepolia Testnet using my own Alchemy Sepolia Testnet RPC.

  - https://sepolia.etherscan.io/address/0x6891659932154b569b06eda73fdce489983ac134


---
### Technical Requirements

Check the basic technical requirements from Patrick's original GitHub repo. For convenience, MacOS users can run `bash ./Lesson12CodeSessions_start-deployment-scripts.sh Install-Tools-On-MacOS-Or-Linux` from the root of this repo to help quickly install the required tools.

### Quick Start Script

After the basic technical requirements are installed and working, then you can run the `bash ./Lesson12CodeSessions_start-automation-build-pipeline.sh` script. This automation script will start a sequence of the scripts listed below, and is meant to behave like a typical build pipeline.

### Current Toolkit Capabilities
```
You can view just this help menu again (without triggering any automation) by running 'bash ./Lesson12CodeSessions_start-deployment-scripts.sh -h' or 'bash ./Lesson12CodeSessions_start-deployment-scripts.sh -h --help'.

bash ./Lesson12CodeSessions_start-deployment-scripts.sh Stop-Local-Blockchain-Nodes-Clean-Environment
bash ./Lesson12CodeSessions_start-deployment-scripts.sh Install-Tools-On-MacOS-Or-Linux
bash ./Lesson12CodeSessions_start-deployment-scripts.sh Start-Deployment-On-A-Specific-Network hardhat
bash ./Lesson12CodeSessions_start-deployment-scripts.sh Start-Deployment-On-Real-Ethereum-Testnet
bash ./Lesson12CodeSessions_start-deployment-scripts.sh Start-Hardhat-Test

If you're running this for the first time run the following before running any of these scripts.

bash ./Lesson12CodeSessions_start-deployment-scripts.sh Install-Tools-On-MacOS-Or-Linux

Then you can run the following combined commands in your terminal to deploy the contract to the Hardhat local blockchain node.

bash ./Lesson12CodeSessions_start-deployment-scripts.sh Stop-Local-Blockchain-Nodes && bash ./Lesson12CodeSessions_start-deployment-scripts.sh Start-Deployment-On-A-Specific-Network hardhat
```

