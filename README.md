# MedCore

A Java and Oracle Database based Hospital Management System featuring both Console and GUI implementations.

Built right after the DBMS mid term as a personal practice project, using the same schema provided in the lab mid exam. This wasn't assigned coursework, I wanted to build a complete console and GUI app on top of that schema before starting TRACK later in the semester.

**Project Type:** University Project (Solo, Practice) <br>
**Course:** Database Systems, 3rd Semester, COMSATS University Islamabad

**Portfolio:** [hassanbukhari.is-a.dev](https://hassanbukhari.is-a.dev/) <br>
**LinkedIn:** [Syed Hassan Ali Bukhari](https://www.linkedin.com/in/syedhassanalibukhari/)

## Features

### Console Version

- Doctor management
- Patient management
- Medicine management
- Custom SQL query runner
- CRUD operations
- Oracle Database connectivity

### GUI Version

- Modern Java Swing interface
- Doctor records management
- Patient records management
- Medicine records management
- Database integration
- Interactive forms and tables

## Technologies Used

- Java
- Java Swing
- Oracle Database
- JDBC (Oracle ojdbc11)
- SQL
- Bash Shell Scripts

## Project Structure

```text
MedCore-Hospital-Management/
├── src/
│   ├── console/
│   ├── gui/
│   ├── db/
│   └── models/
├── sql/
├── lib/
├── screenshots/
└── run.sh
```

## Requirements

- Java JDK 17 or later
- Oracle Database
- Oracle JDBC Driver (ojdbc11.jar)
- Linux environment or Bash support

## Setup

### 1. Clone Repository

```bash
git clone https://github.com/TheHassanBukhari/MedCore-Hospital-Management.git
cd MedCore-Hospital-Management
```

### 2. Add Oracle JDBC Driver (if not present already)

Place `ojdbc11.jar` inside `lib/`.

### 3. Configure Database

Run SQL files in order:

```text
sql/create_database.sql
sql/create_tables.sql
sql/sample_data.sql
```

### 4. Run Program (Linux)

```bash
./run.sh
```

For Windows, make your own Batch File (.bat) from this bash file.

## Screenshots

### Login
![Login screen](screenshots/01_login.png)

### Overview
![Overview dashboard](screenshots/02_overview.png)

### Doctors
![Doctors management](screenshots/03_doctors.png)

### Patients
![Patients management](screenshots/04_patients.png)

### Medicines
![Medicines management](screenshots/05_medicines.png)

### Custom Query
![Custom SQL query runner](screenshots/06_custom_query.png)

## Author

[Syed Hassan Ali Bukhari](https://hassanbukhari.is-a.dev/)

## License

This project is licensed under the [MIT License](./LICENSE).
