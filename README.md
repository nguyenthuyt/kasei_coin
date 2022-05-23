# Martian Token Crowdsale Challenge

The purpose of this challenge to use Solidity to create a smart contract that uses Ethereum management functions. The smart contract will automate the creation of joint savings account.

    
---

## Technologies

This analysis leverages Solidity (pragma ^0.5.5) and utilizes Remix IDE to build and test smart contracts.

---

## Installation Guide

Metamask & Ganache
This challenge utilizes a web version of Remix IDE and as a result, you do not need to install any software.

---

## Usage
The challenge is hosted on the following GitHub repository at: https://github.com/nguyenthuyt/kasei_coin   

### **Run instructions:**
To run this project, simply clone the repository or download the files. Open a Remix IDE web browser instance and navigate to the directory that contains the follwing files:
**KaseiCoin.sol**
**KaseiCoinCrowdsale**

Then compile and deploy the file using Injected Web3 environment:

![Remix Compile](Execution_Results/compile.PNG)
![Remix Deploy](Execution_Results/deploy.PNG)

## Remix IDE

Utilizing Remix IDE web browser instance, the user is able to set the recipient addresses for account1 and account2 using the 'setAccounts' function. 

![Remix Set Accounts](Execution_Results/01_Set_Accounts.PNG)

The user is then able to deposit funds into the account using the 'deposit' function. In this exercise, three separate deposits of 1ETH, 10ETH, and 5ETH are made. Notice the contract balance is increased as each deposit is made.

![Remix Deposit 1ETH](Execution_Results/02a_Deposit_1_ETH.PNG)
![Remix Deposit 10ETH](Execution_Results/02b_Deposit_10_ETH.PNG)
![Remix Deposit 5ETH](Execution_Results/02c_Deposit_5_ETH.PNG)

Finally, the user is able to withdraw funds to the authorized accounts set in the first step. In this exercise, 5ETH is transferred to account1 and 10ETH to account2.

![Remix Withdrawal 5ETH](Execution_Results/03a_account_one_withdrawal_5ETH.PNG)
![Remix Withdrawal 10ETH](Execution_Results/03b_account_two_withdrawal_10ETH.PNG)




---

## Contributors

This project was created as part of the Rice Fintech Bootcamp 2022 Program by:

Thuy Nguyen

Email: nguyen_thuyt@yahoo.com

LinkedIn: nguyenthuyt



---

## License

MIT




