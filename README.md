
# Letter Of Recommendation

Welcome to the **Letter of Recommendation** decentralized application (DApp), designed to make the process of managing student recommendation requests more transparent, secure, and efficient using blockchain technology.

This smart contract allows students to submit their recommendation requests and provides authorized personnel with the ability to approve them — all while ensuring the integrity of the data through the power of the Ethereum blockchain.


Index
- [Features](#Features)
- [Installation](#installation)
- [Run Locally](#RunLocally)
- [Environment Variables](#EnvironmentVariables)
- [Screenshots](#Screenshots)

---

## 🚀 Features

### 1. **Student Recommendation Requests**
   - Students can submit their name, university, and program to request a recommendation.
   - Each submission is assigned a unique ID, making it easy to track individual requests.

### 2. **Approval System**
   - Once a recommendation request is submitted, professors or authorized personnel can approve it.
   - The approval status is permanently stored on the blockchain, ensuring trust and transparency.

### 3. **View Student Details**
   - Easily retrieve student details, including their name, university, program, and recommendation status.
   - Anyone can view the status, ensuring transparency for all parties involved.

### 4. **Planned Features**
   - **Role-Based Access**: Only specific individuals (e.g., professors) will be able to approve recommendations.
   - **Recommendation Storage**: Option to include recommendation text or an IPFS link for decentralized document storage.
   - **Revocable Approvals**: Ability to revoke approvals if necessary.
   - **Recommendation Expiration**: Set an expiration period for recommendations.
   - **Multi-Signature Approval**: Require multiple approvers for added integrity.




## Installation

Install my-project with npm

```bash
  npm install
  cd client
  npm install
```
## Metamask Installation

This project utilizes blockchain technology and smart contracts, requiring the installation of Metamask for Ethereum wallet functionality. Follow these steps to set up Metamask:

1. **Install Metamask:**

   If you haven't already, install Metamask as a browser extension for your preferred browser (Chrome, Firefox, Brave, etc.). You can find Metamask and installation instructions at [metamask.io](https://metamask.io/).

2. **Set up Metamask:**

   - Create a new wallet or import an existing one.
   - Connect Metamask to the Ethereum Mainnet or any other network your project interacts with.

3. **Configure your wallet:**

   Ensure your wallet is funded with the appropriate Ethereum (ETH) or tokens required for interacting with this application's smart contracts.

4. **Connect Metamask to the application:**

   Once Metamask is installed and set up, connect it to the application to enable blockchain interactions.

For detailed instructions on using Metamask, refer to the [Metamask User Guide](https://metamask.zendesk.com/hc/en-us/categories/360001824191).

## RunLocally

Clone the project

```bash
  git clone https://github.com/gagan-kotian/Blockchain-based-Electoral-Bond-Web-App.git
```

Go to the project directory

```bash
  cd Blockchain-based-Electoral-Bond-Web-App
```

Install dependencies

```bash
  npm install
```
Deploy Smart contract
```bash
  npx hardhat run --network goerli scripts/finaldeploy.js
```
copy and paste the deployed contract address in App.js
```bash
  const contractAddress = "0x0e32839B72AD8589F633F1Ce9ad94d13D1438630";
```

Frontend install

```bash
  cd client
  npm install
```

Start the server

```bash
  npm start
```


## EnvironmentVariables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

GOERLI_URL=ADD RPC url

PRIVATE_KEY=ADD Private key of wallet
## Screenshots

![Screenshot 1](https://i.postimg.cc/MKJW2HTg/alor4.png)
![Screenshot 2](https://i.postimg.cc/CxmYq4NV/alor3.png)
![Screenshot 3](https://i.postimg.cc/1RwQHSHB/alor2.png)
![Screenshot 4](https://i.postimg.cc/CL4p349f/alor1.png)



