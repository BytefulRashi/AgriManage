# AgriManage

AgriManage is a web-based agriculture management system designed to empower farmers to efficiently manage their farms, crops, and resources, while enabling customers to browse and purchase fresh produce online.

## Installation

1. **Install Node.js and npm:**
   Ensure you have Node.js and npm installed on your machine.

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Database Configuration:**
   - Edit the database configuration file located at `config/database.js` to set up your MySQL database connection details.

4. **Create Database Schema:**
   - Run the following command to create the database schema:
   ```bash
   node scripts/create_database.js
   ```

## Usage

1. **Launch the Application:**
   Start the server using:
   ```bash
   node server.js
   ```

2. **Access the Application:**
   Open your web browser and visit:
   ```
   http://localhost:8080
   ```

## Technologies Used

- Frontend:
  - HTML
  - CSS
  - EJS (Embedded JavaScript)
  - JavaScript

- Backend:
  - Node.js
  - Express.js
  - MySQL

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
