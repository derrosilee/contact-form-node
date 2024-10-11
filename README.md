# Contact Form Project

This project is a simple Node.js application that provides a contact form. When the form is submitted, the details are sent to an email address using Nodemailer.

## Requirements

- Node.js
- npm (Node Package Manager)

## Packages

The following packages are required for this project:

- express: ^4.21.1
- body-parser: ^1.20.3
- nodemailer: ^6.9.15
- dotenv: ^16.4.5

## Installation

1. Clone the repository:
   ```sh
   git clone <repository-url>
   
2. Initialize Project and Install Dependencies:
   ```sh
   npm init -y
   npm install express body-parser nodemailer dotenv

3. Install the required packages:
   ```sh
    npm install
   
4. Create a `.env` file in the root directory of the project and add the following environment variables:
   ```sh
   EMAIL_USER=<email-address>
   EMAIL_PASS=<email-password>
   
5. Run the application:
   ```sh
   npm start
   
6. Open a web browser and navigate to `http://localhost:3000` to view the contact form.