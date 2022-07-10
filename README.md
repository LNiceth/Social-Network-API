# 📝 Homework #10: Social Media API

📌 [Walkthrough Video](https://youtu.be/-xoXbzhM09M)

## 🔨 Task
Using MongoDB and Mongoose, create an API for a social media platform where clients can create a user, create thoughts, react to thoughts, and add friends. Each of these methods should also have CRUD methods applied to them.

## 🧩 Tech Stack
- JavaScript
- [ExpressJS](https://expressjs.com/)
- [mongoose](https://mongoosejs.com/)

## 📎 How to Use
After forking the project and cloning it to your machine, run `npm install` to download all packages.

To begin with some seeded data, run `npm run seed` to fill the database with dummy data.

To start the server, run `npm start` and the server will begin listening for requests. Use your favorite HTTP Request software to test the routes! Available routes are:
* /api/users
* /api/users/:userId
* /api/users/:userId/friends
* /api/thoughts
* /api/thoughts/:thoughtId
* /api/thoughts/:thoughtId/reactions
* /api/thoughts/:thoughtId/reactions/:reactionId

## License

This project is licensed under the MIT license.


## Questions

If you have any questions about this repository, open an issue or contact me directly at lordnicethcuevas@gmail.com You can find more of my work at [lordnicethcuevas](https://github.com/LNiceth).
