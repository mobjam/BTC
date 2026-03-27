# How to send BTC from cold storage wallet using Tails and Electrum


1) Open the watch-only cold wallet in Electrum on Windows/Mac (ONLINE)

2) Enter the details of the send transaction, click 'Pay'

3) On the transaction screen, click on 'Share' --> 'Save to file'

4) Save the UNSIGNED transaction to a USB drive

5) Boot into Tails (OFFLINE), open Electrum (Apps --> Internet --> Electrum Bitcoin Wallet)

6) Import the cold wallet from the seed phrase

7) Click on 'Tools' --> 'Load transaction' --> 'From file'

8) Click 'Sign'

9) Click 'Share' --> 'Save to file'

10) Save the SIGNED transaction to the USB drive

11) Power-off Tails and return to the watch-only cold wallet in Electrum on Windows/Mac (ONLINE)

12) Click on 'Tools' --> 'Load transaction' --> 'From file' 

13) Select the SIGNED transaction from the USB drive

14) Click on 'Broadcast'

15) Check for receipt of transaction at the recieving wallet.

----------------

Resources:

https://tails.net/

https://etcher.balena.io/

https://electrum.org/



