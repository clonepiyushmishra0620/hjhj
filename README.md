# hjhj

---

## 🛠️ Set-up Procedure

```bash
# 1. Fork the GitHub repository and clone your fork
`git clone` https://github.com/<your-username>/test-interface.git

# 2. Navigate to the project folder
`cd` test-interface

# 3. Initialize a Node.js project (creates package.json)
`npm init -y`

# 4. Install all required dependencies
`npm install` express cors express-validator mongodb mongoose dotenv nodemon

# 5. Create a .env file in the root directory and add:
# PORT=5000
# MONGO_URI=mongodb://localhost:27017/test-interface

# 6. Start the development server with nodemon
`nodemon` server.js
