# Wavelength Guessing Game Backend

This repository contains the backend code for a multiplayer guessing game. In this game, one player secretly chooses a number between 1 and 10, while the other players attempt to guess the chosen number within three attempts. The guessing players ask comparison questions to the chooser, who answers based on their subjective rankings. Using these answers and knowledge of the chooser's preferences, the guessing players attempt to deduce the chosen number.

## Technologies Used

- Node.js
- Express.js
- Socket.IO
- PostgreSQL

## Installation

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Configure your PostgreSQL database settings in `db.js` or you can configure your non-sql database client such as MongoDB using the Mongoose library of Node.JS .
4. Run the server using `npm start`.

## Usage

To use this backend for your game:

1. Connect your frontend application to this backend using Socket.IO for real-time communication.
2. Implement the game's logic on the frontend, including sending and receiving messages between players and processing game state changes.
3. Ensure that the frontend interacts with the backend to handle user authentication, game sessions, and database operations.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request for review.

## Credits

The initial version of this backend was developed by Erjon Hasanaj, and Drinor Berisha.
