This is a repository containing a solidity smart contract named SimpleStorage.sol. 
Remix IDE was used for the development. 

**Development and Environment Setup**

Since Remix IDE was the coding environment I used, I opened Remix IDE through https://remix.ethereum.org in my browser. 
After opening Remix IDE, on File explorer, I clicked on workspaces and I created a new workspace and named it “MyFirstSmartContract”. After creating the workspace, I created a new solidity file under the workspace and I named it “SimpleStorage.sol”. 

**Writing the Smart Contract**

Inside my SimpleStorage.sol file, I begun writing the code. Before writing the code, I made sure that I declared the License before writing the pragma version. I ensured that the version was pragma solidity ^0.8.25. I used a variable type of uint256 for the variable favoriteNumber to be able to store large numbers. The code is shown below;
contracts/SimpleStorage.sol: 
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.25; // This allows any version from 0.8.25 to less than 0.9.0
contract SimpleStrorage{
    uint256 favoriteNumber; //state a variable to store number
}  

**Compiling the Smart Contract**

Under solidity compiler, I checked again to ensure that the version is pragma solidity ^0.8.25. I clicked on Compile SimpleStorage.sol, it was thick green at the solidity compiler button indicating no errors. 

**Deploy and Run Transactions**

I clicked on the deploy and run transactions button and selected the Remix VM (cancun) under environment, I checked to ensure that SimpleStorage was written in the CONTRACT before I clicked on deploy. Under console I saw the status after deploying written “Transaction mined and execution succeed”

**Push Contract to GitHub**

I created an empty repository in GitHub and named it “MyFirstSmartContract”, I added the repository as a remote repository to the Remix environment. Under git, I pushed the code to the repository.   
