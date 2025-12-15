# Hotel Booking Application
### Overview
This project is a  Group assignment for Group U  which is Hotel Booking Application developed using ReactJS for the front-end and Spring Boot for the back-end. The application provides two roles: Admin and User. Each role has specific functionalities as described below.
Group members are:
WERE ELLIOT	IN13/00175/23
IAN KIPLANGAT	IN13/00031/23
ALAN SHIKOLI	IN13/00065/23
DENISH OCHIENG OKUMU	IN13/00174/23


## Features
### User Role
#### Users have the following permissions:
```
Book a room
View their bookings
```
### Technologies Used
Front-end: ReactJS, Redux, Axios
Back-end: Spring Boot, Spring Security, JPA, Hibernate
Database: MySQL

### Installation
###### Prerequisites - Ensure you have the following installed:
Node.js
npm or yarn
Java (JDK 11 or above)
MySQL

#### Front-end Setup
##### Navigate to the frontend directory:
```
cd frontend/Hotel-booking-application
```
##### Install the dependencies:
```
npm install
```
##### Start the development server:
```
cmd /c npm run dev

```

### Back-end Setup
##### Navigate to the backend directory:
```
cd backend/HotelBookingApplication
```

##### Configure the database connection in src/main/resources/application.properties:
```
spring.datasource.url=jdbc:mysql://localhost:3306/hotel_booking
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

##### Build the project:
```
./mvnw clean install
```
##### Run the Spring Boot application:
```
./mvnw spring-boot:run
``` 

