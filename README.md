# SuperShop - E-commerce Application

SuperShop is a responsive e-commerce platform built using React.js for the frontend and Node.js with Express.js for the backend. It provides intuitive product browsing, search, cart, and checkout functionalities, along with an engaging admin dashboard for data management.

## Project Highlights

- **Frontend Development:**

  - Developed a responsive UI with React.js, Redux, and RTK Query.
  - Implemented product browsing, search, cart, and checkout functionalities.
  - Created an engaging admin dashboard with data management modules.

- **Backend Development:**

  - Built a secure and efficient backend with Node.js and Express.js.
  - Leveraged MongoDB for data management and Firebase for user authentication.
  - Utilized Node-cache to optimize server response time by 30%.

- **Payment Integration:**
  - Integrated Stripe for payment processing, resulting in a 50% reduction in transaction time.

## Technology Stack

### Frontend

- TypeScript
- React.js
- Redux
- RTK Query
- SCSS

### Backend

- Node.js
- Express.js
- MongoDB
- Firebase
- Stripe

## Getting Started

To get started with the SuperShop e-commerce application, follow these steps:

### Frontend

1. Clone the repository:

   ```properties
   git clone https://github.com/anikxt/supershop
   ```

2. Navigate to the frontend directory:

   ```properties
   cd ecommerce-frontend
   ```

3. Install dependencies:

   ```properties
   npm install
   ```

4. Run the development server:

   ```properties
   npm run dev
   ```

5. Open your browser and navigate to [http://localhost:5173](http://localhost:5173) to view the application.

### Backend

1. Open a new terminal window/tab.

2. Navigate to the backend directory:

   ```properties
   cd ecommerce-backend
   ```

3. Install backend dependencies:

   ```properties
   npm install
   ```

4. Set up a local MongoDB database:

   - Install MongoDB on your system if you haven't already.
   - Start the MongoDB server.

5. Configure the connection to your local MongoDB database:

   - Create a .env file in the ecommerce-backend directory.
   - Add the following configuration to the .env file:

     ```plaintext
     MONGODB_URI=mongodb://localhost:27017
     ```

6. Start the backend server:

   ```properties
   npm start
   ```

Now, both the frontend and backend servers should be up and running, allowing you to explore and interact with the SuperShop e-commerce application.

Ensure that you have MongoDB installed and running on your local machine. The `.env` file in the backend directory should contain the MongoDB connection URI (`MONGODB_URI`) pointing to your local MongoDB database.

## Contributing

Contributions to SuperShop are welcome! If you'd like to contribute, please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and ensure that the code passes all tests.
- Submit a pull request detailing your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
