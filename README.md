# How to send BTC from cold storage wallet using Tails and Electrum


Open watch-only wallet in Electrum

Enter details of send transaction, click 'Pay'

On the transaction screen, click 'Share --> 'Save to file'

Save Unsigned transaction to USB drive

Boot into Tails, open Electrum

import cold wallet from seed phrase

Click on 'Tools' --> 'Load transaction' --> 'From file'

Click 'Sign'

Click 'Share' --> 'Save to file'

Save SIGNED transaction to USB key

Power off Tails and retuen to online Electrum

Click on 'Tools' --> 'Load transaction' --> 'From file'. Select SIGNED transaction from USB drive

Click on 'Broadcast'

Confirm receipt on revieving wallet
