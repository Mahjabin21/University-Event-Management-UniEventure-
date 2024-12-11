# UniEventure

UniEventure is a comprehensive event management system designed for universities. It allows event organizers and students to manage and participate in university events seamlessly. The system includes functionalities for signing up, logging in, booking events, and participating in them, along with an admin portal for managing users and events.

## Features

- **Homepage**:
  - Sign up or log in to your account.
  - View available events directly from the homepage.

- **User Registration**:
  - University event organizers and students can sign up with accurate information.
  - Validation ensures the correctness of data during the sign-up process.

- **UserDashboard**:
  - A common dashboard for all users.
  - Navigate to:
    - **OrganizerDashboard**: Book events as an organizer.
    - **ParticipantDashboard**: Participate in events by filling out an information form.

- **Admin Portal**:
  - Admins can log in by checking the admin data file for credentials.
  - Manage all user and event information efficiently.

## How It Works

1. **Sign Up**:
   - University event organizers and students must register using valid information.
   - Validation ensures correct and complete data.

2. **Login**:
   - Access your account by providing the correct credentials.
   - Organizers and students share a common UserDashboard upon login.

3. **OrganizerDashboard**:
   - Book an event by selecting available venues, dates, and time slots.
   - Add details about the event to ensure proper scheduling.

4. **ParticipantDashboard**:
   - View a list of available events.
   - Participate in events by completing a simple information form.

5. **Admin Portal**:
   - Admins can log in using credentials from the admin data file.
   - Manage all user accounts and events effectively, including adding or removing records as needed.

## Prerequisites

To run UniEventure, you will need:

- Java 8 or later.
- A Java-compatible IDE (like IntelliJ IDEA or Eclipse).
- Access to text files for managing user, event, and admin data.

## Installation and Execution

1. Download the repository as a ZIP file from GitHub.
2. Extract the ZIP file to your desired location.
3. Open a terminal or command prompt and navigate to the extracted folder.
4. Compile the program:
   javac Start.java
   java Start
