# Beginner-Blockchain in Pyhthon with CLI
⬛️🔗⬛️🔗
Start with terminal on the filedirectory where the file is downloaded and type: 
> blockchain.py

Alternatively open the file in your favorite IDE and run it.

Once you start the file, you’ll get the option to choose what you’d like to do. Following we will explain what each of these options does.

Functions: 
1. Press “1” to “Add a new transaction value”
  - Before you can add a new transaction, you will need to have some balance. To get balance, you’ll need to mine a block first. 
  - You will be able to enter the recipient of your transaction and the amount.
  - After it will add the transaction to the chain and show your new balance.
2. Press “2” to “Mine a new block”
  - This option will extend your balance by 10 by mining a new block. If you’d like to adjust the “mining reward” you can do so by setting “MINING_REWARD = 10” to a new amount.
3. Press “3” to “Output the blockchain blocks”
  - This will show the previous outputted blocks of the chain.
4. Press “4” to “Output participants”
  - This will show all the people that so far participated in the chain.
5. Press “5” to “Check transaction validity”
  - This will check whether the previous transactions were valid or not.
6. Press “h” to “Manipulate the chain”
  - This option is there to show, that you can’t manipulate the chain. 
  - Please keep in mind, that choosing this option will only work after at least one block has been mined. The original genesis_block can’t be altered, because it is known by everyone in the network. 
  - Once chosen you will get an error message and the program will close itself.
7. Press “q” to “Quit”
  - You can use this option to leave the menu and be done with the program. 

