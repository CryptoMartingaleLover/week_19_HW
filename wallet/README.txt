Week 19 Homework - Blockchain with Python 
By Steve Stark

In this assignment, we were tasked with generating addresses and sending/receiving transactions on Ethereum and Bitcoin testnets, using Python. 

The main code for the assignment submission can be found in wallet.ipynb, the constants in constants.py, and the outut images in the Images folder. 

Regarding the output, I was able to successfully complete transactions across the BTC testnet using Python and the addresses generated in the activity. 

![BTC_testnet_tx_confirmation](Images/BTC_testnet_tx_confirmation.png)

However, I was not able to successfully complete transactions over the Ethereum test network for this assignment. 

![ETH_testnet_tx_confirmation](Images/ETH_testnet_tx_confirmation.png)

I was able to get everything running up until that point. However, a major obstacle was restarting the blockchain from the Week 18 Homework. In particular, there was an issue in the command for actually getting the nodes minting again on the blockchain: 

./geth --datadir node1 --unlock 0x34BE4a71a8B074A48DAdfc7c949526065a049dea --password password.txt --rpc --allow-insecure-unlock --syncmode "fast" --mine --minerthreads 1

This is the exact line I used to successfully generate and run a blockchain in Week 18. However, for some reason, the --password flag followed by the .txt file was now completely ineffective in unlocking the address. I tried everything. I worked on it from 8am to 12:30pm, after spending two full days working on this assignment, and I just don't know why it isn't working. It worked before. Nothing else changed but the address, which is correct and properly assigned within the blockchain. I could probably find success if I were to start from the beginning of the Week 18 Homework and then straight through the current assignment, but I have put enough into this one and I have other assignments to catch up on. So this is the best I can do at this point in time. 

Thank you! 

