# Player Management System

A desktop application built with Java Swing for managing player information in a sports database. This system provides a user-friendly graphical interface to perform CRUD (Create, Read, Update, Delete) operations on player records.

## Features

- **Add Players**: Insert new player records with details like name, team, role, and country
- **Update Players**: Modify existing player information
- **Delete Players**: Remove player records from the database
- **View Players**: Display all player records in a table format
- **Database Integration**: Connected to SQL database for persistent data storage
- **GUI Interface**: User-friendly Java Swing-based interface

## Technologies Used

- **Language**: Java
- **GUI Framework**: Java Swing
- **Database**: SQL (java.sql package)
- **IDE**: NetBeans (nbproject configuration files included)
- **Build Tool**: Apache Ant (build.xml)

## Project Structure

```
Player-Management-System/
├── src/
│   ├── design/          # Player form and logic
│   ├── designs/         # Additional UI components
│   └── icons/           # Application icons
├── build/
│   └── classes/         # Compiled .class files
├── nbproject/           # NetBeans project configuration
├── build.xml            # Ant build configuration
└── manifest.mf          # JAR manifest file
```

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- NetBeans IDE (recommended) or any Java IDE
- SQL Database (MySQL/PostgreSQL/etc.)
- JDBC Driver for your database

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jagadeesh242/Player-Management-System.git
   ```

2. Open the project in NetBeans or your preferred IDE

3. Configure your database connection in the source files

4. Build the project:
   ```bash
   ant build
   ```

5. Run the application:
   ```bash
   ant run
   ```

## Usage

1. **Launch the application** - Run the Players.java main class
2. **Add a Player** - Fill in the form fields and click the Add button
3. **Update a Player** - Select a player from the table, modify the details, and click Update
4. **Delete a Player** - Select a player from the table and click Delete
5. **View Players** - All players are displayed in the table automatically

## Database Setup

Ensure you have a database table with the following structure:

```sql
CREATE TABLE players (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    team VARCHAR(100),
    role VARCHAR(50),
    country VARCHAR(50)
);
```

## Screenshots

(Add screenshots of your application here)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Author

**jagadeesh242**

## Acknowledgments

- Built as a learning project for Java Swing and database integration
- Thanks to the NetBeans community for excellent IDE support
