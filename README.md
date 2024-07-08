# Financial Asset Management System

Welcome to our financial asset management system repository! This system uses DAML to manage various financial transactions and contracts. Below is a summary of recent activities:

## Recent Activities

### Account Setup

- **Alice's Account**: 'Bank' sets up an account for Alice.
- **Bob's Account**: 'Bank' sets up an account for Bob.

### Investments

- **Real Estate Investment Trusts (REITs)**: Alice creates an investment product categorized under real estate with moderate risk and return profiles, accessible to retail and institutional investors.

### Transactions

#### Transaction Details

1. **Account Operations**:
   - 'Bank' checks details in Alice's and Bob's accounts.

2. **Trading**:
   - Alice offers to sell 100 units of REITs to Bob for a total price of 1000 units.
   - Bob accepts Alice's offer, and they create a settlement contract.

## Active Contracts

- **Holding**: Alice's investment in REITs managed by 'Bank'.
- **Settlement**: Contract between Alice and Bob for the REITs trade.

## Repository Structure

```
root/
│
├── README.md       # Overview of the project and transaction details
├── daml/           # DAML smart contract files
│   ├── Account.daml
│   ├── Investments.daml
│   ├── Holding.daml
│   ├── Trading.daml
│   └── Setup.daml
│
└── .github/        # GitHub Actions or other CI/CD configurations (if any)
```

## About DAML

DAML is the language used to define smart contracts in this system. It allows us to securely automate and manage financial transactions and contracts.

## Notes

This README provides an overview of recent activities, active contracts, and the repository's structure. For detailed smart contract implementations, please refer to the `daml/` directory.

Feel free to reach out for more information or collaboration opportunities!

---
