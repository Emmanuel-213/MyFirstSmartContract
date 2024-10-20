Smart Contract Development Environment
Below was how I wrote the first smart contract and pushed it to GitHub. Remix IDE was the coding environment I used.
I opened Remix IDE through Remix IDE in my browser. On File explorer, I created a new workspace and named it “MyFirstSmartContract”. After creating the workspace, I created a new solidity file under the workspace and I named it “SimpleStorage.sol”. Inside my SimpleStorage.sol file, I begun writing the code. Before writing the code, I made sure that I declared the License before writing the pragma version. I ensured that the version was pragma solidity ^0.8.25. I used a variable type of uint256 for the variable favoriteNumber to be able to store large numbers. The code is shown below;
contracts/SimpleStorage.sol: 
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.25; // This allows any version from 0.8.25 to less than 0.9.0
contract SimpleStrorage{
    uint256 favoriteNumber; //state a variable to store number
}  
Under solidity compiler, I clicked on Compile SimpleStorage.sol, it was thick green at the solidity compiler button indicating no errors. 
I clicked on the deploy and run transactions button and selected the Remix VM (cancun) under environment, I checked to ensure that SimpleStorage was written in the CONTRACT before I clicked on deploy. Under console I saw the status after deploying written “Transaction mined and execution succeed”
I created an empty repository in GitHub and named it “MyFirstSmartContract”, I added the repository as a remote repository to the Remix environment. Under git, I pushed the code to the repository.   
