# CalCount

## Overview
CalCount is a calorie counting application designed to help users track their food intake and manage their dietary goals. The application allows users to log meals, understand nutritional content, and monitor progress over time.

## Features
- **User Authentication**: Secure login and registration.
- **Meal Logging**: Easily log your meals and snacks.
- **Nutritional Information**: Access comprehensive nutritional data for a wide variety of foods.
- **Progress Tracking**: Visual graphs to track intake and progress towards goals.
- **User-Friendly Interface**: Intuitive navigation and design for an effective user experience.

## Architecture
CalCount is built using a modern web stack:
- **Frontend**: React.js for a dynamic user experience.
- **Backend**: Node.js with Express for a RESTful API.
- **Database**: MongoDB for storing user data and meal information.
- **Authentication**: JWT for securing user sessions.

## Setup Instructions
To set up the project locally, follow these steps:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/swapnilwajpe/CalCount.git
   cd CalCount
   ```
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Setup environment variables**:
   Create a `.env` file in the root directory and add the following:
   ```plaintext
   DATABASE_URL=your_mongo_db_url
   JWT_SECRET=your_jwt_secret
   ```
4. **Run the application**:
   ```bash
   npm start
   ```
5. **Open your browser** and navigate to `http://localhost:3000` to use the application.

## Contributing
Feel free to fork the repository and submit pull requests for any improvements or features!