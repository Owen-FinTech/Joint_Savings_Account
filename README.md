# Joint_Savings_Account

To automate the creation of joint savings accounts, I created a Solidity smart contract that accepts two user addresses. These addresses are able to withdraw funds from the account.

## Testing The Deployed Contract

The 'setAccounts' function defines the authourized Ethereum addresses able to withdraw funds from the contract:

![Step_1](Execution_Results/Step_1.png)

Testing the deposit functionality of the contract and the 'contractBalance' function to verify funds were added to the contact.

Transaction 1: Deposit 1 ether as wei:

![Step_2](Execution_Results/Step_2.png)

Transaction 2: Deposit 10 ether as wei:

![Step_3](Execution_Results/Step_3.png)

Transaction 3: Deposit 5 ether:

![Step_4](Execution_Results/Step_4.png)

Testing the contracts withdrawal functionality.

Withdrawing 5 ether into 'accountOne':

![Step_5](Execution_Results/Step_5.png)

Using the 'lastToWithdraw' and 'lastWithdrawAmount' functions to verify that the address and amount were correct:

![Step_6](Execution_Results/Step_6.png)

Withdrawing 10 ether into 'accountTwo':

![Step_7](Execution_Results/Step_7.png)

Verifying address and amount were correct:

![Step_8](Execution_Results/Step_8.png)

## Contributors

Owen Harris











