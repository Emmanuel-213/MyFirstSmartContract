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

**Implementing Data Types and Variables**

I created a struct person variable to store a person's name and their favorite number. I added a Person array to be able to store multiple user's data. I created an enum to check the state of a contract, active and inactive contracts. I created a contractstate variable to store the current contract state and I made sure that it was public. After adding the variables, I compiled and deployed again to make sure that everything is working properly.

**Implement Solidity Functions, Conditions and Loops**

I created a public storeNumber function to store the favoriteNumber, I set the variable type of the favoriteNumber to uint256. I also created a getNumber function which would return the favoriteNumber, I set it to public view return so it could be visible. I created a function for a conditional statement and I named it isGreaterThan, to compare the favoriteNumber and a comparedValue after that it should return a boolean(true or false).
I created a sumToFavoriteNumber function, under it, I created a for loop to sum all numbers up to the favorite number. I compiled and deployed to ensure that everything works properly.

**Apply Visibility Specifiers**

I changed the favoriteNumber to private to allow only getFavoriteNumber function to return the stored favoriteNumber. I created an internalFunctiion to return a string, since it is internal, I created a callInternalFunction to expose the internalFunction. I created an externalFunction and a testExternalFunction to call the externalFunction within the contract.

**Add arrays, Structs and Enums**

I created addFavoriteNumber function to add favorite numbers to the array. I created a returnNumbers function just to return the favorite numbers, I did this to check whether the favoriteNumbers were stored. I created addPerson function to add people names and their favoriteNumbers. I created activateContract for contracts that are active, deactivateContract for contracts that are inactive and isActive to check if a contract is active or not.

**Compile, Test, and Push to GitHub**

After all these, I clicked on the solidity compiler again and Compile SimpleStorage.sol. The compilation was successful. I clicked on the deploy and run transactions, I checked to ensure that SimpleStorage was written in the CONTRACT before I clicked on deploy. Under console I saw the status after deploying written “Transaction mined and execution succeed”. I tested my functions along as I code, I clicked on Source Control and "added second commit" and I finally went to COMMANDS under Git and pushed my code to the GitHub repository.
