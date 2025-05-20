
## Note ##

</hr></hr>

**As I am stoing URL of Image in database but not on block,As I am storing only Image Id on Blockchain and deleting from ID only,but it become difficult to fetch data as My Display.js file fetching data from blockchain only here is the issue...** 

</hr></hr>


</hr></hr>

# Blockchain Process


**--------------------------------------------------------- start ---------------------------------------------------------------**

**-----> Automate   Installation of all file will be as follows** 
                                                                **↩**
## step 1 : clone the github file using :
```
git clone https://github.com/manojpisepatil/final-project.git
```
## step 2 : open powershel cmd
```
 ./setup.ps1
```
## It is one time process and if we try to run above same files then it gives error so , Unblock the Script File
```
Unblock-File -Path .\setup.ps1
```

## before select connect do below process then click on select 
**1. create account by importing private key** </br>
**2. now connect to that account e.g account2** </br>
**3. inset below details** </br>
```
| ------------------ | ---------------------------------------------- |
| Field              | Value                                          |
| ------------------ | ---------------------------------------------- |
| Network name       | Localhost 8545                                 |
| New RPC URL        | http://127.0.0.1:8545                          |
| Chain ID           | 31337                                          |
| Currency symbol    | ETH                                            |
| Block Explorer URL | (Leave blank)                                  |
| ------------------ | ---------------------------------------------- |

```
</br> **select network : Localhost 8545** </br>

**---------------------------------------------------------- end ----------------------------------------------------------------**


**----> Manual  Installation of all file will be in the blockchain folder " final-project "**


=======
</hr></hr>

# Blockchain Process


**--------------------------------------------------------- start ---------------------------------------------------------------**

**-----> Automate   Installation of all file will be as follows** 
                                                                **↩**
## step 1 : clone the github file using :
```
git clone https://github.com/manojpisepatil/final-project.git
```
## step 2 : open powershel cmd
```
 ./setup.ps1
```
## It is one time process and if we try to run above same files then it gives error so , Unblock the Script File
```
Unblock-File -Path .\setup.ps1
```

## before select connect do below process then click on select 
**1. create account by importing private key** </br>
**2. now connect to that account e.g account2** </br>
**3. inset below details** </br>
```
| Field              | Value                                          |
| ------------------ | ---------------------------------------------- |
| Network name       | Localhost 8545                                 |
| New RPC URL        | http://127.0.0.1:8545                                  |
| Chain ID           | 31337                                          |
| Currency symbol    | ETH                                            |
| Block Explorer URL | (Leave blank)                                  |
```
</br> **select network : Localhost 8545** </br>

**---------------------------------------------------------- end ----------------------------------------------------------------**


**-----> Manual  Installation of all file will be in the blockchain folder " final-project "**


## Terminal 1
```
1. winget install OpenJS.NodeJS   --->  give permission "y"
2. Set-ExecutionPolicy RemoteSign -scope currentuser
3. npm install -save -dev hardhat
4. npx init -y 
5. npm install
6. npx hardhat node --->  give permission "y"
``` 
**downlaod metamask chrome extension and setup it**</br>
**In main**</br>
**1. create account by importing private key**</br>
**2. now connect to that account e.g account2**</br>
**3. inset below details**</br>
```
| Field              | Value                                          |
| ------------------ | ---------------------------------------------- |
| Network name       | Localhost 8545                                 |
| New RPC URL        | http://127.0.0.1:8545                          |
| Chain ID           | 31337                                          |
| Currency symbol    | ETH                                            |
| Block Explorer URL | (Leave blank)                                  |
```

**select network : Localhost 8545**</br>
## Terminal 2
```
1. npx hardhat run --network localhost scripts/deploy.js
2. cd .\client\
3. npm install
4. npm start
```
**click on select**

# 🦊 MetaMask – Import Account Using Private Key

This guide walks you through the steps to import an account into MetaMask using a private key.

## 📌 Steps to Import an Account

| Step | Description | Screenshot |
|------|-------------|------------|
| 1 | Open the **MetaMask extension** | ![Step 1](https://github.com/user-attachments/assets/8190b9eb-a1bb-4366-a031-4a6857e685b9) |
| 2 | Click on **Add Account** | ![Step 2](https://github.com/user-attachments/assets/2573a8f0-346b-4ac1-b35f-8553e1c23537) |
| 3 | Select **Import Account**, then choose **Private Key** | ![Step 3](https://github.com/user-attachments/assets/18d772bf-6bd2-4343-aac7-d2058d12520e) |
| 4 | Copy the Private Key | ![Step 5](https://github.com/user-attachments/assets/b844efcd-2dc9-442e-b923-63edc62b450c) |
| 5 | Paste your **Private Key** into the field and click **Import** | ![Step 4](https://github.com/user-attachments/assets/7dc49e4c-97df-4d45-b6fd-de45a8209d73) |

> ⚠️ **Never share your private key with anyone.** Anyone with access to your private key can control your wallet.

---

## ✅ Done!

Your wallet is now ready to use with the imported account.


https://github.com/user-attachments/assets/cf4d4b32-6582-4fd4-95a4-71774af51c97


