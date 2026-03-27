# How to send BTC from cold storage wallet using Tails and Electrum


1) Open the watch-only cold wallet in Electrum on Windows/Mac (ONLINE)

2) Enter the details of the send transaction, click _'Pay'_

3) On the transaction screen, click on _'Share'_ --> _'Save to file'_

4) Save the UNSIGNED transaction to a USB drive

5) Boot into Tails (OFFLINE), open Electrum (Apps --> Internet --> Electrum Bitcoin Wallet)

6) Import the cold wallet from the seed phrase

7) Click on _'Tools'_ --> _'Load transaction'_ --> _'From file'_

8) Click _'Sign'_

9) Click _'Share'_ --> _'Save to file'_

10) Save the SIGNED transaction to the USB drive

11) Power-off Tails and return to the watch-only cold wallet in Electrum on Windows/Mac (ONLINE)

12) Click on _'Tools'_ --> _'Load transaction'_ --> _'From file'_ 

13) Select the SIGNED transaction from the USB drive

14) Click on _'Broadcast'_

15) Check for receipt of transaction at the recieving wallet.

----------------

Resources:

https://tails.net/

https://etcher.balena.io/

https://electrum.org/



