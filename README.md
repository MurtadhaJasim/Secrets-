

# Secrets-

**Secrets-** is a Node.js web application that allows users to anonymously share their secrets. Built with Express.js, EJS templating, and MongoDB, it provides a platform for users to submit and view secrets without revealing their identity.

## Features

* User authentication and session management
* Anonymous secret submission
* Display of all submitted secrets
* Secure storage of user data

## Demo

You can view the live demo here: [Secrets- Live Demo](https://murtadhajasim.github.io/Secrets-)

## Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/) (version 14 or higher)
* [MongoDB](https://www.mongodb.com/) (local or cloud instance)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MurtadhaJasim/Secrets-.git
   cd Secrets-
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:

   ```env
   PORT=3000
   MONGODB_URI=your_mongodb_connection_string
   SESSION_SECRET=your_session_secret
   ```

4. **Start the application:**([GitHub Docs][3])

   ```bash
   npm start
   ```

5. **Open your browser and navigate to:**([GitHub Docs][3])

   ```
   http://localhost:3000
   ```

## Project Structure

```
Secrets-/
├── public/
│   ├── css/
│   └── images/
├── views/
│   ├── partials/
│   └── pages/
├── routes/
├── models/
├── .env
├── app.js
├── package.json
└── README.md
```



## Technologies Used

* [Node.js](https://nodejs.org/)
* [Express.js](https://expressjs.com/)
* [EJS](https://ejs.co/)
* [MongoDB](https://www.mongodb.com/)
* [Mongoose](https://mongoosejs.com/)
* [Passport.js](http://www.passportjs.org/)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Submit a pull request

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

* Inspired by the desire to provide a platform for anonymous sharing
* Built with [Express.js](https://expressjs.com/) and [MongoDB](https://www.mongodb.com/) for robust backend support

