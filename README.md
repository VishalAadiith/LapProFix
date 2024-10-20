# LapProFix

_LapProFix_ is a open source web application designed to provide users with a convenient way to book laptop repair services from certified service centers. The platform emphasizes user experience by allowing for easy service booking, real-time progress tracking, and interactive support through a built-in chatbot.

## Table of Contents
- [Setup](#setup)
- [Features](#features)
- [Technologies Used](#technologies-used)


## Setup

1. **Fork the Repository**

Click the **Fork** button at the top-right corner of this repository to create your own copy.

2. **Clone Your Fork**

Once you've forked the repository, clone it to your local machine:

```bash
git clone https://github.com/VishnuAmit/LapProFix.git
```

3. **Create a New Branch**

Always create a new branch for your changes:

```bash
git checkout -b your_branch
```

4. **Do staging in it**

Make Your Changes

```bash
git add .
```

6. **Commit Your Changes:**

```
git commit -m "Relevant message"
```

7. **Push to Your Branch:**

```
git push origin your_branch
```

8. **Create a Pull Request:**
 
 Go to your forked repository on GitHub and create a pull request to the main repository _and i'll merge it as soon as i can._



## Features
- _User Authentication_: Users can sign up and log in securely to manage their bookings.
- _Dashboard_: An intuitive dashboard displaying service options, user profile, and booking history.
- _Service Booking_:
  - Instant Book for quick service requests.
  - Specialized services for Windows, Apple, and other laptop types. 
- _Technician Scheduling_:
  - Automated scheduling of technicians based on the user's issues reported during the booking process.
  - Users can select specific time slots for technician visits, enhancing convenience and flexibility. 
- _Progress Tracking_:
  - A visual progress bar indicating the current status of the service request:
    - Booking
    - Assigning
    - Service Progress
    - Complete
- _Chatbot Assistance_:
  - A built-in chatbot to assist users with common queries and provide real-time support.
    
## Technologies Used

- _Frontend_:
  - _Next.js_: For building dynamic user interfaces.
  - _Axios_: For making HTTP requests to the backend.
- _Backend_: 
  - Node.js: JavaScript runtime for building the server.
  - Express.js: Web framework for Node.js to handle requests and responses.
  - MongoDB: NoSQL database for storing user and booking information.
  - Mongoose: ODM for MongoDB to define models and schemas.
- _Authentication_: 
  - JWT (JSON Web Tokens): For user authentication and secure session management.
- _Deployment_: 
  - Vercel: For hosting the application.
- _Other Libraries/Tools_: 
  - dotenv: For managing environment variables.
  - Bcrypt.js: For hashing user passwords.


