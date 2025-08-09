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
- **Symptom-Based Health Predictions:** Patients can input their symptoms into the system, which then analyzes the data using advanced algorithms to provide health predictions. This feature helps patients understand their possible health conditions and take timely action.
- **Medicine Suggestions:** Based on the symptoms provided by the patient, the system suggests appropriate over-the-counter medicines or treatments. This feature aids patients in managing minor health issues without needing immediate consultation, while also guiding them toward appropriate care.
- **Doctor Recommendations:** The system recommends specialist doctors based on the patient's symptoms and health predictions. This ensures that patients receive the most relevant and expert care for their specific health concerns.
- **Doctor Profile and Clinic Management:** Doctors have the ability to create and manage their profiles within the system. This includes updating personal information, clinic details, and availability. It allows doctors to maintain an online presence and facilitates easy patient-doctor interaction.
- **Administrative Control:** Administrators are granted the authority to manage system operations, ensuring that the platform remains current, secure, and fully functional. They handle tasks such as updating the database, managing user roles, and maintaining overall system integrity.
## Tech Stack
| Technology | Purpose                   |
| ---------- | ------------------------- |
| Angular    | Frontend (UI/UX)          |
| Spring Boot| Backend (REST APIs)       |
| Java       | Primary Backend Language  |
| Python     | Utility Scripts/Modules   |
| HTML, CSS  | Web Structure & Styling   |
| Maven      | Dependency Management     |
## Installation Steps

1. **Clone the Repository**
   ```sh
   git clone https://github.com/Rakesh161rausahn/Angular-Spring-boot-Smart-Healthcare-System.git
   cd Angular-Spring-boot-Smart-Healthcare-System
   ```
2. **Install Angular Dependencies**
   ```sh
   cd Smart-Health-Care-System-main/New\ folder/frontend
   npm install
   ```
3. **Install Backend Dependencies**
   ```sh
   cd ../../SmartHealthcareSystem-Backend
   mvn clean install
   ```
4. **Configure Database**
   - Update `application.properties` in the Spring Boot backend module with your MySQL credentials.
5. **Run Backend**
   ```sh
   mvn spring-boot:run
   ```
6. **Run Frontend**
   ```sh
   cd ../../New\ folder/frontend
   ng serve --open
   ```
## Usage
- Access the application at `http://localhost:4200` after running both backend and frontend services.
- Register or log in as a doctor, patient, or admin depending on your access level.
## Contribution
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.
## License
This project is MIT Licensed.
## Contact
For queries or suggestions, contact [Rakesh161rausahn](https://github.com/Rakesh161rausahn).
