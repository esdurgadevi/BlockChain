# BlockChain
### Installation
- npm install --save--dev hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers
- Hardhat - It is a ethereum development environement it allows to run the solidity locally Used to test the smart contract before the deployment
## 📦 Dependencies Used in This Project

This project uses the following Web3-related dependencies:

### 1. @nomiclabs/hardhat-ethers
- **Purpose:** Integrates the [Ethers.js](https://docs.ethers.io/) library with [Hardhat](https://hardhat.org/).
- **Why:** Lets us easily interact with Ethereum smart contracts in the Hardhat environment.
- **Example:** Deploying a contract and calling its functions during development.

---

### 2. @nomiclabs/hardhat-waffle
- **Purpose:** Adds [Waffle](https://ethereum-waffle.readthedocs.io/en/latest/) testing features to Hardhat.
- **Why:** Provides easy smart contract testing with readable assertions.
- **Example:** Writing tests like `expect(await contract.balanceOf(addr1)).to.equal(1000)`.

---

### 3. chai
- **Purpose:** Assertion library for JavaScript tests.
- **Why:** Makes test results more readable and easier to understand.
- **Example:**  
  ```js
  expect(value).to.equal(42);
