# Investify

## A Self-Contained Stock Exchange Built for Risk-Free Paper Trading

---

# **ReadMe Guide for Investify-v2**

Investify-v2 is a full-stack stock broking web application designed for **beginners** who want to **learn investing and trading** without the risk of losing their capital. The application provides a **risk-free environment** where users can simulate real-world trading strategies and gain hands-on experience.

## **Investify Stock Exchange (ISE)**
Investify features its own **self-contained stock exchange (ISE - Investify Stock Exchange)**. This means that the stock prices in Investify **do not depend on real-world market conditions** but are instead affected by the trading activity of users within the application.

Users can perform trades, track their portfolio, and analyze market trends within this controlled environment, making it a great tool for **educational purposes** and **strategy testing**.

---

## **Running the Development Server: Investify-v2**
To start the development server, follow these steps:

1. **Fork the Repository:**
   - Go to the official Investify repository and fork it.

2. **Clone the Fork:**
   - Open a terminal and run the following command to clone your forked repository to your local system:
     ```sh
     git clone https://github.com/YOUR_GITHUB_USERNAME/investify-v2.git
     ```

3. **Navigate to the Frontend Directory:**
   - Change your working directory to `investify-frontend` by running:
     ```sh
     cd investify-frontend
     ```

4. **Install Dependencies:**
   - Run the following command to install all necessary packages:
     ```sh
     npm install
     ```
   - This will install all the required **Node.js packages** for the frontend to function properly.

5. **Start the Development Server:**
   - Once the installation is complete, start the development server using:
     ```sh
     npm start
     ```
   - The development server will start and will be available at:
     ```sh
     http://localhost:3000
     ```
   - Now, you can open the web application in your browser and start testing its features.

---

## **Running the Production Server: Investify-v2**
### **Prerequisites:**
Before running the production server, make sure your local machine has the following installed:
- **MongoDB** (for database management)
- **Nodemailer Application Password** (for email services)
- **MySQL** (for structured database storage)

### **Steps to Run the Production Server:**

1. **Navigate to the Frontend Directory:**
   - Open a terminal and move to the frontend directory:
     ```sh
     cd investify-frontend
     ```

2. **Build the Production Version:**
   - Run the following command to generate an optimized build for deployment:
     ```sh
     npm run build
     ```
   - This will create a production-ready build that Node.js can use as the frontend reference.

3. **Navigate to the Backend Directory:**
   - Change to the backend directory:
     ```sh
     cd investify-backend
     ```

4. **Install Backend Dependencies:**
   - Run the following command to install all backend dependencies:
     ```sh
     npm install
     ```

5. **Set Up Environment Variables:**
   - Create a `.env` file in the `investify-backend` directory and define the required environment variables:
     ```sh
     PORT=5000
     SECRET_KEY=your_secret_key
     MAIL_PASS=your_mail_password
     AUTH_PASS_API_KEY=your_auth_key
     JWT_SECRET=your_jwt_secret
     MYSQL_PASSWORD=your_mysql_password
     MYSQL_DATABASE=your_mysql_database
     MAIL_ID=your_email_address
     ```

6. **Start the Production Server:**
   - Run the following command to start the backend:
     ```sh
     node app.js
     ```
   - The backend server will start and will be accessible at:
     ```sh
     http://localhost:5000
     ```
   - Now, the production build is ready to use.

---

## **Navigating the Application**
- **Frontend URL (Development Mode):** `http://localhost:3000`
- **Backend API (Production Mode):** `http://localhost:5000`
- **Investify Stock Exchange (ISE) Simulation:** Built-in trading environment managed by user interactions

---

## **Contributing to Investify**
If you want to contribute to Investify, follow these steps:
1. **Fork the repository** to your own GitHub account.
2. **Clone the forked repo** to your local system.
3. **Create a new branch** for your feature or bug fix.
4. **Make changes and commit them** with clear commit messages.
5. **Push the changes** to your forked repository.
6. **Create a pull request (PR)** to the main repository.

---

## **License**
Investify is an open-source project licensed under the **MIT License**. You are free to use, modify, and distribute it with attribution.

---

### 🚀 Happy Trading on Investify! 🚀

