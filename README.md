# Emergency and Mental Wellbeing Application

This application is designed to enhance users' personal security and mental wellness through features such as secure journaling, emergency SOS alerts, and motivational affirmations.

## Features

1. **User Authentication**: Users can register, log in, and securely manage their profiles.
2. **Secure Journal**: Encrypted journal entries support text, images, and documents.
3. **Emergency SOS Alerts**: Allows users to send emergency alerts with geolocation to predefined contacts.
4. **Positive Affirmations**: Displays motivational affirmations on each visit.

---

## Technology Stack

- **Frontend**: React
- **Backend**: Spring Boot
- **Database**: PostgreSQL
- **Architecture**: Monolithic application for simplified deployment and management


## Setup Instructions

### Prerequisites

- **Java 11 or higher**
 <!--- - **Node.js and npm** (for the frontend) --->
- **PostgreSQL** (for the database)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/emergencyandmentalwellbeing.git
   cd emergencyandmentalwellbeing
   ```

2. **Backend Setup**:
   - Update `application.properties` in Spring Boot with your PostgreSQL credentials.
    - Run database migrations (e.g., Flyway or Liquibase) to set up the tables. 
   - Start the Spring Boot server:
     ```bash
     ./mvnw spring-boot:run
     ``` --->

<!---3. **Frontend Setup**:
   - Navigate to the frontend directory:
     ```bash
     cd frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```--->

3. **Access the Application**:
   - Open a browser and navigate to `http://localhost:8080` for the backend API.

---

## API Endpoints

The application’s backend provides several RESTful API endpoints. Below are some examples:

- **User Authentication**:
  - `POST /api/users/register` - Register a new user.
  - `POST /api/users/login` - Log in with email and password.

- **Journal Management**:
  - `GET /api/journals` - Get user journal entries.
  - `POST /api/journals` - Add a new journal entry.

- **Emergency Alerts**:
  - `POST /api/sos` - Trigger an SOS alert.
  - `GET /api/sos/status` - Get status of previous alerts.

---

## Contributing

We welcome contributions! Here’s how you can help:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

Feel free to reach out with any questions, issues, or feedback! 

---
