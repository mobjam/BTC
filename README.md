# How to send BTC from cold storage wallet using Tails and Electrum


1) Open the watch-only cold wallet in Electrum on Windows/Mac **(ONLINE)**

2) Enter the details of the send transaction, click _'Pay'_

3) On the transaction screen, click on _'Share'_ --> _'Save to file'_

4) Save the **UNSIGNED** transaction to a USB drive

5) Boot into Tails **(OFFLINE)**

6) Open Electrum (Apps --> Internet --> Electrum Bitcoin Wallet)

7) Import the cold wallet using the seed phrase

8) Click on _'Tools'_ --> _'Load transaction'_ --> _'From file'_

9) Select the **UNSIGNED** transaction from the USB drive

10) Click _'Sign'_

11) Click _'Share'_ --> _'Save to file'_

12) Save the **SIGNED** transaction to the USB drive

13) Power-off Tails and return to the watch-only cold wallet in Electrum on Windows/Mac **(ONLINE)**

14) Click on _'Tools'_ --> _'Load transaction'_ --> _'From file'_ 

15) Select the SIGNED transaction from the USB drive

16) Click on _'Broadcast'_

17) Check for receipt of the transaction at the recieving wallet address.

----------------

**Resources:**

  - https://tails.net/ (download Tails OS image file)

  - https://etcher.balena.io/ (write Tails image to USB drive)

  - https://electrum.org/ (download Electrum Wallet for Windows/Mac)



