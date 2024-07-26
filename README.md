# Banking System with ATM Interface

## Overview
This project is a simple banking system with an ATM interface, developed using Java and Spring Boot. It provides functionalities for basic banking operations such as account creation, balance inquiry, deposits, and withdrawals through an ATM-like interface.

## Features
- **Account Creation**: Create new bank accounts with unique account numbers.
- **Balance Inquiry**: Check the balance of an account.
- **Deposits**: Deposit money into an account.
- **Withdrawals**: Withdraw money from an account.
- **Transaction History**: View transaction history for an account.

## Technologies Used
- **Java**: The core programming language used for developing the application.
- **Spring Boot**: Framework used for building the back-end services.
- **Spring Data JPA**: For database interactions.
- **H2 Database**: In-memory database for testing and development purposes.
- **RESTful API**: To interact with the banking system.

## Getting Started

### Prerequisites
- JDK 11 or later
- Maven or Gradle
- IDE (IntelliJ, Eclipse, etc.)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/banking-system-atm.git
   cd banking-system-atm
   ```

2. **Build the project**
   ```bash
   mvn clean install
   ```

3. **Run the application**
   ```bash
   mvn spring-boot:run
   ```

## Usage

### API Endpoints
- **Create Account**
  ```http
  POST /api/accounts
  ```

- **Get Balance**
  ```http
  GET /api/accounts/{accountId}/balance
  ```

- **Deposit Money**
  ```http
  POST /api/accounts/{accountId}/deposit
  ```

- **Withdraw Money**
  ```http
  POST /api/accounts/{accountId}/withdraw
  ```

- **Transaction History**
  ```http
  GET /api/accounts/{accountId}/transactions
  ```

## Project Structure

```plaintext
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── example/
│   │           └── bankingsystem/
│   │               ├── controller/
│   │               ├── model/
│   │               ├── repository/
│   │               ├── service/
│   │               └── BankingSystemApplication.java
│   └── resources/
│       ├── application.properties
│       └── data.sql
└── test/
    ├── java/
    └── resources/
```

## Contributing
Feel free to fork this repository and contribute by submitting pull requests. Any improvements or suggestions are welcome.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, please contact (arifeducation799@gmail.com).
