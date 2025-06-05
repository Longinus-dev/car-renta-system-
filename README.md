Car Rental System (Java, OOP)
This is a console-based Car Rental System built using **Java** and **Object-Oriented Programming (OOP)** principles. It includes login authentication with masked password input, car and customer management, and a rental agency system. The project also includes test cases written using **JUnit 5**.
 Login Feature
- Accepts username and password
- Password input is masked (`*`) where possible (may not work in some IDEs)
- Allows *3 attempts before locking the user out

OOP Structure
1. Car.java
- Stores car model, license plate, and availability
- Methods: `rent()`, `returnCar()`, `isAvailable()`
2. Customer.java
- Stores customer name and driver license number
3. RentalAgency.java
- Stores and manages a list of cars
- Allows rental and return transactions
- Displays available cars

4. LoginSystem.java
- Handles secure login with retry logic and optional password masking

5. Main.java
- Menu-driven system to rent/return cars and interact with the user

Unit Tests

Tested using **JUnit 5** (`RentalAgencyTest.java`):
- Rent a car
- Return a car
- Attempt to rent an unavailable car

How to Run
Requirements
- Java JDK 11+
- JUnit 5 (for tests)
- Terminal or IDE (IntelliJ, Eclipse, VS Code)

Compile & Run
bash
javac src/*.java
java src/Main


