# CLI-express 🚆

CLI-express is a Java-based command-line train ticket booking system that uses local JSON storage to manage data.
This project was created as a learning exercise to understand Java application structure, file handling, and basic system design.

## Features

- Command-line based user interaction
- Train search and ticket booking
- Passenger details handling
- Local JSON-based data storage
- Modular Java code structure
- No external database dependency

## Tech Stack

- Java
- Gradle
- JSON

## Project Structure

```text
CLI-express/
├── app/                # Application source code
├── gradle/             # Gradle wrapper files
├── gradlew             # Gradle executable (Linux/Mac)
├── gradlew.bat         # Gradle executable (Windows)
├── settings.gradle     # Gradle settings
└── build.gradle        # Build configuration and dependencies
```

## How to Run

### Prerequisites

- Java JDK 8 or higher installed
- Git installed
- Internet connection (for the first Gradle build)

### Steps

1. **Clone the repository**
   ```bash
   git clone [https://github.com/Ayush-sinha44/CLI-express.git](https://github.com/Ayush-sinha44/CLI-express.git)
   ```

2. **Navigate to the project directory**
   ```bash
   cd CLI-express
   ```

3. **Run the application**

   **For Linux / macOS:**
   ```bash
   ./gradlew app:run
   ```

   **For Windows:**
   ```bash
   .\gradlew.bat app:run
   ```

## Learning Outcomes

- Understanding Gradle-based Java project structure
- Working with JSON-based local storage
- Building CLI applications in Java
- Handling user input and control flow
- Writing modular and maintainable code

## Future Improvements

- [ ] Add user authentication
- [ ] Improve input validation and error handling
- [ ] Implement seat availability logic
- [ ] Replace JSON storage with a real database (MySQL/PostgreSQL)
- [ ] Add automated unit tests

## License

This project is intended for educational and learning purposes.

## Author

**Ayush Sinha**
[GitHub Profile](https://github.com/Ayush-sinha44)
