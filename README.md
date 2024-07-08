# Financial Asset Management System
This repository tracks transactions and manages contracts within a financial asset management system built using DAML. It facilitates the creation, trading, and management of various financial instruments among participants.

 ## Transactions Overview
### Transaction 0
#### Timestamp: 1970-01-01T00:00:00Z
Description: Initialization transaction for setting up an account.
Details:
'Bank' creates an account for 'Alice' with ID "Alice_Account".
### Transaction 1
#### Timestamp: 1970-01-01T00:00:00Z
Description: Initialization transaction for setting up another account.
Details:
'Bank' creates an account for 'Bob' with ID "Bob_Account".
### Transaction 2
#### Timestamp: 1970-01-01T00:00:00Z
Description: Account operation.
Details:
'Bank' exercises account fetch on Alice's account.
### Transaction 3
#### Timestamp: 1970-01-01T00:00:00Z
Description: Account operation.
Details:
'Bank' exercises account fetch on Bob's account.
### Transaction 4
#### Timestamp: 1970-01-01T00:00:00Z
Description: Investment creation.
Details:
'Alice' creates an investment product named "Real Estate Investment Trusts (REITs)".
### Transaction 5
#### Timestamp: 1970-01-01T00:00:00Z
Description: Investment operation.
Details:
'Alice' exercises fetch operation on the REITs investment.
### Transaction 6
#### Timestamp: 1970-01-01T00:00:00Z
Description: Holding creation.
Details:
'Bank' creates a holding associated with Alice's account and the REITs investment.
### Transaction 7
#### Timestamp: 1970-01-01T00:00:00Z
Description: Trade offer creation.
Details:
'Alice' creates an offer to sell 100 units of REITs to 'Bob' for a total price of 1000 units.
### Transaction 8
#### Timestamp: 1970-01-01T00:00:00Z
Description: Trade settlement.
Details:
'Bob' accepts Alice's offer to purchase 100 units of REITs for 1000 units.
Additionally, 'Alice' and 'Bob' create a settlement contract for the trade.
Active Contracts
Holding: Associated with Alice's account and the REITs investment.
Settlement: Generated from the trade between Alice and Bob.
