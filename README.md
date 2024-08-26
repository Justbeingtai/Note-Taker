# Note Taker Application

## Description

The Note Taker Application is designed to help users organize their thoughts and keep track of tasks by allowing them to write, save, and manage notes. The application was built using an Express.js back end, with data being stored and retrieved from a JSON file. This project was motivated by the need to have a simple, yet effective tool for note-taking that can be used in various scenarios, from personal task management to business-related note keeping.

- **Motivation:** To create a user-friendly application that helps individuals manage their tasks and ideas efficiently.
- **Why:** This project was developed to address the common problem of disorganized notes and to provide a simple solution for saving and retrieving notes quickly.
- **Problem Solved:** It allows users to create, view, and delete notes as needed, providing a straightforward way to manage daily tasks and thoughts.
- **Learning:** Through this project, I gained a deeper understanding of Express.js, routing, and working with JSON data to simulate a database.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)

## Installation

To install and set up the development environment, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/note-taker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd note-taker/Develop
    ```

3. Install the necessary dependencies using npm:
    ```bash
    npm install
    ```

4. Start the application:
    ```bash
    node server.js
    ```

5. Open your web browser and go to `http://localhost:3001` to start using the application.

## Usage

To use the Note Taker Application:

1. Click on the "Get Started" button on the landing page.
2. You will be redirected to the notes page, where you can view existing notes in the left-hand column and create a new note by entering a title and text in the right-hand column.
3. Click the "Save" icon to save the note. The note will appear in the list of notes on the left.
4. To view a saved note, click on it in the list.
5. To delete a note, click the trash icon next to the note.

![Note Taker Application Screenshot](./Develop/images/Note%20taker%20screen%20.png)

![Note Taker Application Screenshot](./Develop/images/json%20and%20success%20terminal%20.png)

## Credits

This project was developed by [Tai](https://github.com/Justbeingtai/Note-Taker.git).

### Acknowledgments:
- [Express.js](https://expressjs.com/) - Used to build the back end of the application.
- [uuid](https://www.npmjs.com/package/uuid) - Used to generate unique IDs for each note.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/your-username/note-taker/blob/main/LICENSE) file for details.

## Badges

![Top Language](https://img.shields.io/github/languages/top/your-username/note-taker)
![License](https://img.shields.io/github/license/your-username/note-taker)

## Features

- Create, view, and delete notes.
- Persistent storage using JSON files.
- Responsive design.

## How to Contribute

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## Tests

To run tests for this application:

1. Ensure that Jest is installed:
    ```bash
    npm install --save-dev jest
    ```

2. Run the tests:
    ```bash
    npm test
    ```