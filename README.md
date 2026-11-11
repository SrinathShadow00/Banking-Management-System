# Banking-Management-System
Developed a Core Java banking application supporting customer registration, account management, deposits, withdrawals, fund transfers, and transaction history.  Implemented OOP principles, inheritance, polymorphism, Java Collections, custom exceptions, and transaction tracking to enforce banking business rules.

Developed a banking management application in Java supporting 9 operations: customer registration, account opening,
deposits, withdrawals, inter-account transfers, balance enquiry, and transaction statements.
• Applied abstraction and polymorphism through an abstract Account base class with SavingsAccount and CurrentAccount
subclasses that override withdrawal logic to enforce a minimum-balance business rule.
• Enforced encapsulation of invariants — balances mutate only through validated deposit/withdraw methods — with a custom
InsufficientBalanceException/InvalidTransactionException hierarchy replacing generic error handling.
• Used the Java Collections Framework (HashMap, ArrayList) with computeIfAbsent for O(1) customer/account lookup, static
factory methods (open()) to prevent invalid account construction, and a transaction ledger keyed by a Type enum recording
deposits, withdrawals, and transfer-in/transfer-out with post-transaction balances.
