# Starbug Membership
This project involves the design and implementation of a membership system for a coffee shop using C# with an Object-Oriented Programming (OOP) paradigm, developed as a part of Object Oriented Programming Subject. The system is built to support various business events within the coffee shop, including member registration, drink and beverage purchases, and a points-based system that allows members to accumulate stars and redeem a free cup of coffee.

## Classes:
### 1. Program
The `Program` class serves as the general program entry point. It orchestrates the flow of the application and interacts with other classes to handle member registration, transactions, and point redemption.

### 2. Sale
The `Sale` class is responsible for managing sales transactions. It contains two essential methods:
- `recordSaleItem`: Calculates the total price of a transaction.
- `Print`: Prints the receipt for a completed transaction.

### 3. Star
The `Star` class manages the accumulation and redemption of stars for members. It includes two crucial methods:
- `CStar`: Accumulates stars when a member makes a purchase.
- `Redeem`: Deducts stars from a member's account to redeem a free cup of coffee.

### 4. CoffeeFree
The `CoffeeFree` class handles the process of redeeming a free cup of coffee when a member has accumulated enough stars.

### 5. Member
The `Member` class represents a member in the coffee shop's membership system. It includes two key methods:
- `ExchangeStar`: Calculates the number of stars a member earns for a purchase, contributing to star accumulation.
- `DeductStar`: Deducts stars from a member's account when redeeming a free cup of coffee.

### 6. Menu
The `Menu` class handles the coffee shop's menu objects. It is responsible for managing and displaying the available items for purchase.
