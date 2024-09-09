# EmployHive

EmployHive is a modern job portal application built with React.js, Tailwind CSS, Shadcn UI, Clerk, and Zod. It provides a user-friendly interface for job seekers and employers to connect and manage job listings effectively.

## Features

- **User Authentication**: Secure sign-up and login functionality using Clerk.
- **Job Listings**: Browse and search for job postings.
- **Employer Dashboard**: Post new job openings and manage existing listings.
- **Job Seeker Dashboard**: Apply for jobs and track application status.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Form Validation**: Robust form validation using Zod.

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for styling.
- **Shadcn UI**: A set of pre-designed UI components.
- **Clerk**: Authentication and user management.
- **Zod**: TypeScript-first schema validation.

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/employhive.git
   cd employhive
2. **Install dependencies**

    bash
    Copy code
    npm install

3. **Set up environment variables**

    Create a .env file in the root directory and add the following variables:
    
    REACT_APP_CLERK_FRONTEND_API=<your-clerk-frontend-api>
    REACT_APP_CLERK_API_KEY=<your-clerk-api-key>

4. **Run the development server**

    npm start

Navigate to http://localhost:3000 in your browser to view the application.

**Usage**

*Register/Login*: Use Clerk authentication to sign up or log in.
*Browse Jobs*: Explore job listings on the homepage.
*Post a Job*: Employers can add new job listings via the dashboard.
*Apply for Jobs*: Job seekers can apply directly to job postings.

**Contributing**

1. Fork the repository: Click the "Fork" button at the top-right corner of this page.

2. Clone your fork:
   
    git clone https://github.com/your-username/employhive.git

3. Create a new branch:

    git checkout -b feature/your-feature

4. Make your changes and commit:

    git add .
    git commit -m "Add your commit message"

5. Push to your fork:

    git push origin feature/your-feature

6. Create a Pull Request: Go to the original repository and click "New Pull Request".

License
This project is licensed under the MIT License - see the LICENSE file for details.

**Acknowledgments**

React.js
Tailwind CSS
Shadcn UI
Clerk
Zod