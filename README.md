# Angular-Spring-boot-Smart-Healthcare-System

## Overview

**Angular-Spring-boot-Smart-Healthcare-System** is a comprehensive platform designed to enhance healthcare services by bridging the gap between patients, doctors, and administrators. The system utilizes modern web technologies—**Angular** for the front end and **Spring Boot** for the back end—to provide features such as appointment booking, patient management, doctor scheduling, and health record tracking.

## Features

- **User Authentication & Authorization:** Secure login for admins, doctors, and patients.
- **Doctor Module:** Manage schedules, view appointments, and interact with patients.
- **Patient Module:** Book appointments, view prescriptions, and access health records.
- **Admin Dashboard:** Manage users, monitor system usage, and oversee appointments.
- **Health Record Management:** Store and manage patient medical histories.
- **Notifications:** Real-time notifications for users.

## Tech Stack

| Technology | Purpose                   |
| ---------- | ------------------------- |
| Angular    | Frontend (UI/UX)          |
| Spring Boot| Backend (REST APIs)       |
| Java       | Primary Backend Language  |
| Python     | Utility Scripts/Modules   |
| HTML, CSS  | Web Structure & Styling   |
| Maven      | Dependency Management     |
| MySQL      | Database (suggested)      |

## Project Structure

```plaintext
/
├── Doctor/                        # Doctor-specific modules
├── Smart-Health-Care-System-main/ # Main backend and Angular source
├── package-lock.json              # Node.js dependency lockfile
```

## Getting Started

### Prerequisites

- Node.js & npm (for Angular)
- Java JDK 8+ (for Spring Boot)
- Maven (for managing Java dependencies)
- MySQL or another SQL-compatible database

### Installation Steps

1. **Clone the Repository**
    ```sh
    git clone https://github.com/Rakesh161rausahn/Angular-Spring-boot-Smart-Healthcare-System.git
    cd Angular-Spring-boot-Smart-Healthcare-System
    ```
2. **Install Angular Dependencies**
    ```sh
    cd Smart-Health-Care-System-main
    npm install
    ```
3. **Install Backend Dependencies**
    ```sh
    cd ../Doctor
    mvn clean install
    ```
4. **Configure Database**
    - Update `application.properties` in the Spring Boot module with your database credentials.
5. **Run Backend**
    ```sh
    mvn spring-boot:run
    ```
6. **Run Frontend**
    ```sh
    ng serve --open
    ```

## Usage

- Access the application at `http://localhost:4200` after running both backend and frontend services.
- Register or log in as a doctor/patient/admin depending on your access level.

## Contribution

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is [MIT Licensed](LICENSE).

## Contact

For any queries or suggestions, feel free to contact [Rakesh161rausahn](https://github.com/Rakesh161rausahn).
