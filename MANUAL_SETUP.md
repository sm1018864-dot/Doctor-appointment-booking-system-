# Manual Setup Instructions

This guide provides detailed steps to run the "doc-appointment-mern" project (Doctor Website) manually in VS Code.

## Prerequisites

Ensure you have the following installed:
- **Node.js**: [Download](https://nodejs.org/) (Version 18+ recommended)
- **MongoDB**: [Download](https://www.mongodb.com/try/download/community) (Ensure it's running locally or use Atlas URI)
- **VS Code**: [Download](https://code.visualstudio.com/)

## Project Structure

- **`doctor/`**: Contains the backend server code.
- **`doctor/client/`**: Contains the frontend (React + Vite) code.
- **`admin panel/`**: (Optional) Contains the admin dashboard code.

## Step-by-Step Instructions

### 1. Open the Project in VS Code
- Open VS Code.
- Go to `File` > `Open Folder...`.
- Select the `doctor-website` folder.

### 2. Setup and Run the Backend

1.  Open a Terminal in VS Code (`Terminal` > `New Terminal`).
2.  Navigate to the `doctor` directory:
    ```bash
    cd doctor
    ```
3.  Install dependencies (if not already done):
    ```bash
    npm install
    ```
4.  Ensure the `.env` file exists in the `doctor` folder with the following keys:
    ```env
    PORT=8080
    MONGO_LOCAL_URI=mongodb://localhost:27017
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key
    CLIENT_URL=http://localhost:5173
    ```
5.  Start the backend server:
    ```bash
    npm start
    # OR
    node server.js
    ```
    *You should see "Node Server Running" and "MongoDB Connected Successfully".*

### 3. Setup and Run the Frontend (Client)

1.  Open a **New Terminal** (click the `+` icon in the terminal panel).
2.  Navigate to the `doctor/client` directory:
    ```bash
    cd doctor/client
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Start the development server:
    ```bash
    npm run dev
    ```
    *You should see a message like `Local: http://localhost:5173/`.*

### 4. Setup and Run the Admin Panel (Optional)

1.  Open a **New Terminal**.
2.  Navigate to the `admin panel` directory:
    ```bash
    cd "admin panel"
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Start the admin panel:
    ```bash
    npm run dev
    ```

## Accessing the Application

- **Doctor/Patient Website**: Open [http://localhost:5173](http://localhost:5173) in your browser.
- **Backend API**: Running on [http://localhost:8080](http://localhost:8080).

## Troubleshooting

- **MongoDB Connection Error**: Ensure MongoDB is running locally on port 27017.
- **Module Not Found**: Run `npm install` in the respective directory (`doctor`, `doctor/client`).
- **Port In Use**: If port 8080 or 5173 is busy, stop the process using it or change the port in `.env` (backend) or vite config (frontend).

