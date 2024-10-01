## Installation

To run the bot application locally, follow these steps:

### Prerequisites

Ensure you have the following installed on your machine:

- **Node.js** (v14 or later): Download from [nodejs.org](https://nodejs.org/).
- **Yarn** (optional, but recommended) or **npm**: Available at [yarnpkg.com](https://yarnpkg.com/).
- **Git**: Install from [git-scm.com](https://git-scm.com/).
- add new file with name of ".env" and past : GEMINI_API_KEY=AIzaSyBAyfIYFwknJl6VI-FdUgM6yI_v-gW3KvI
 

### Steps

1. **Clone the repository**:
   Open your terminal and run the following command:
   ```bash
   git clone https://github.com/vpbaqir/bot.git
Navigate to the project directory:

bash
 
cd bot
Install dependencies: Use either Yarn or npm to install the required packages:

For Yarn:
bash
 
yarn install
For npm:
bash
 
npm install
Install nodemon globally: To use nodemon for automatic server restarts during development, install it globally:

For Yarn:
bash
 
yarn global add nodemon
For npm:
bash
 
npm install -g nodemon
Set up environment variables: Create a .env file in the root directory and add the necessary environment variables:

plaintext
 
PORT=3000
GEMINI_API_KEY=your_api_key_here
Database setup (if applicable): If your bot requires a database, ensure it’s running and that you have the connection string in your .env file.

Start the application: Run the bot server:

For Yarn:
bash
 
yarn start
For npm:
bash
 
npm start
Access the application: Visit http://localhost:3000 in your browser or API client.

vbnet
 

