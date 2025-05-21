# Mophone Product Engineer Role Interivew

## Instructions !!
Please clone this project to your github profile

## Overview
This repository is designed for a live coding session covering both backend (NestJS) development. The session will focus on implementing a feature to reassign a payment from one customer to another. The backend will be built using NestJS, and the frontend will be developed using Next.js with Tailwind CSS and TypeScript.

## Backend: NestJS
### Features Included in the Boilerplate:
1. **Authentication**: Login and Signup endpoints using JWT strategy.
2. **Customer Management**: CRUD operations for managing customers.
3. **Payment Management**:
   - List of payments.
   - Adding a new payment.
  
### Feature to Implement: Reassign Payment
- Create an endpoint to reassign a payment from one customer to another.
- Validate the request:
  - Payment ID must exist.
  - Source and Target Customer IDs must exist.
- Update the payment record with the new customer.
- Return the updated payment details in the response.
- Write a test case for the "Reassign Payment" feature covering:
  - Successful reassignment.
  - Handling non-existent payment IDs.
  - Error handling for invalid customer IDs.

### API Endpoints
1. **Authentication**
   - `POST /auth/signup` – Sign up a new user.
   - `POST /auth/login` – Log in an existing user.

2. **Customers**
   - `GET /customers` – List all customers.
   - `POST /customers` – Add a new customer.

3. **Payments**
   - `GET /payments` – List all payments.
   - `POST /payments` – Add a new payment.
   - `PUT /payments/reassign` – Reassign a payment from one customer to another. *(This endpoint will be implemented during the live coding session)*

### Running the Backend
1. Clone the repository and navigate to the `backend` folder:
   ```bash
   git clone https://github.com/mophones/product-engineer-interview.git
   cd backend
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Run the application:
   ```bash
   npm run start
   ```

4. The application will be available at `http://localhost:3000`.

### Testing
Run the test suite using:
```bash
npm run test
```

## Final Notes

The following are the criteria for judgment
1. Database atomocity
2. Concurrency

Other things to take note of:

- Focus on clean code and good practices.
- Feel free to ask questions and get clarification on requirements.
- Take your time to understand the existing code structure before jumping into implementation.

## License
This project is licensed under the MIT License.

---

Welcome to Mophones
