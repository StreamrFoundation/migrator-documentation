## It is time to upgrade your old Streamr DATA tokens!
<img width="1520" height="624" alt="xdata" src="https://github.com/user-attachments/assets/b1fae007-ff6a-4f7a-971c-31a7a49ce6c9" />

In a recent governance vote (SIP-1), DATA token holders approved a transition to a new smart contract for the token. In addition to technical enhancements, the new contract introduces the ability to increase the token supply, depending on decisions made through the governance process.

### What you need to know

- The old token will be renamed to XDATA, and the new token will inherit the DATA symbol.
- Both the old and new tokens will co-exist for a while. The old tokens are destroyed when they are migrated and an equivalent amount of new tokens are released by the migration system.
- For any remaining XDATA tokens that have not yet been migrated, we have decided to conduct the migration directly using **migration smart contract**, rather than using a migration user interface that is no longer supported. This makes the migration process for the remaining old XDATA token holders simple.
- This is a 1:1 swap, which means that anyone who holds the old XDATA token will receive the same amount of new DATA tokens.


## How to migrate old XDATA Streamr tokens?
### Steps for migration:

**1. Access Your Wallet:** Check your XDATA balance in the list of Ethereum or Polygon tokens.

**2. Send Tokens:** Send your old XDATA tokens to the migration smart contract address `0xcAC6c954A2a8087171D11c84023d5731ae6fa448`. The migration smart contract address begins with `0xcA` and ends with `a448`. The case of letters does not matter (lower case or upper case).
Choose to send the **entire balance** of XDATA tokens. The migration contract will wait for the **full balance** to arrive before initiating the migration process to optimize due to high Ethereum gas fees, partially covered by Streamr Network.

**3. Confirmation:** After the transaction is confirmed and broadcasted to the blockchain, the migration process will start, and your wallet will be credited with new DATA tokens. Depending on network usage, it may take 5–10 minutes to process the migration.

### Help, my wallet doesn’t show the new DATA tokens!
Don’t panic, they are most likely there, your wallet just doesn’t show the new tokens by default yet. Most wallets support adding custom tokens manually. To do so, consult your wallet’s instructions and enter the following information:

- Token contract address (on mainnet): `0x8f693ca8d21b157107184d29d398a8d082b38b76`
- Name: Streamr
- Symbol: DATA
- Decimals: 18

### Post-Migration

Your wallet will **automatically recognize** the new Streamr tokens, and DATA will be credited to your wallet once the migration is complete. These tokens can be sold on any exchange that lists DATA.

Congratulations, you have successfully performed the migration.
