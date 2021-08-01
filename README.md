# Week-20-Homework

Level 1 of this task is to create a smart contract that splits profits between three associates evenly. 

To complete this task, you will need Remix, Ganache and Metamask installed. 

Step 1: Download the Associate Profit Splitter Starter contract which contains most of the code you will need. 

This contract can be opened on the first page of the Remix platform. Just go to open file and retrieve where you've downloaded the starter code. 
![open file](https://user-images.githubusercontent.com/76278469/127757819-b2fa1820-ed30-45b3-99ef-5a57b5c08f00.PNG)

The next steps involve filling out the rest of the code you will need to pay the associates equally. 
![completed code](https://user-images.githubusercontent.com/76278469/127757840-b554f560-12b7-4129-b6d8-3513d4937e31.PNG)

Step 2: Compile the contract. 

Go to the third tab of Remix and press COMPILE. 

Step 3: Fill in the addresses. 

![Enter 3 address deploy](https://user-images.githubusercontent.com/76278469/127757929-5dedf246-7e07-4c6c-9566-e1cedfcb7365.PNG)
![Entered 3 addresses](https://user-images.githubusercontent.com/76278469/127757933-13fb2c7f-7691-44e3-bd7d-2f3721b10e8c.PNG)


Change the environment to 'Injected Web3' which should show a (Custom (5777) network flag beneath it. 

Select account you will sending ether from. This should involve using your main test wallet from Metamask. Ensure it is a wallet that has some ether in it for the transaction. 

Leave Gas Limit as is. 

Enter in a value such as '1 Ether'. 

Ensure the contract is the correct contract 'AssociateProfitSplitter'

In the deploy section, ensure addresses: 

_one:
_two:
_three:

are three test addresses of wallets you have in Ganache. 

![sending 1 ether](https://user-images.githubusercontent.com/76278469/127757943-8d0b7278-451b-4447-8ad0-a78b0dc2318b.PNG)

![ganache screenshot](https://user-images.githubusercontent.com/76278469/127757950-0cccef07-665e-458b-89e1-42767eb94b61.PNG)

Step 4: Transact and Deposit

Click the button 'transact' once you're sure all details are correct. A window will pop up about gas estimation and then your Metamask window show up with details about the transaction.  ![1 sent success](https://user-images.githubusercontent.com/76278469/127757983-08aeb3d3-a049-405f-afe7-d408b5d09956.PNG)

Press confirm. 

A block should show up in remix confirming a successful transaction.

![block success](https://user-images.githubusercontent.com/76278469/127757995-8ca157f1-5530-4c59-b273-282c37944ef5.PNG)

You can also check Ganache to ensure the balances have changed and the ether has been sent equally. 

![transactions difference](https://user-images.githubusercontent.com/76278469/127758008-2d8c3425-a38d-43a2-a8a6-8ca2c7cb20c4.PNG)


Congrats, you've sent profits equally using smart contracts!
