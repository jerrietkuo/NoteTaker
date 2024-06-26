# Note Taker

## Introduction

Welcome to the **Note Taker** application! This app allows you to write, save, and delete notes, helping you organize your thoughts and keep track of tasks. Built with Express.js for the back end, this application seamlessly integrates front-end functionality with a robust server to manage and store your notes efficiently.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Add New Notes**: Write and save your notes with ease.
- **View Existing Notes**: See all your saved notes listed on the left-hand column.
- **Delete Notes**: Remove notes that are no longer needed.
- **Responsive Design**: Works seamlessly on any device.

## Installation

To get started with the Note Taker application, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/jerrietkuo/NoteTaker.git
   cd NoteTaker
   ```

2. **Install dependencies**:
   ```sh
   npm install
   ```

3. **Run the application**:
   ```sh
   node server.js
   ```

4. Open your browser and navigate to `http://localhost:3001`.

## Usage

1. **Homepage**: Start by clicking the "Get Started" button to navigate to the notes page.
2. **Add a Note**: Enter a title and text for your note, then click the save icon to store the note.
3. **View Notes**: Click on any note in the left-hand column to view its details.
4. **Delete Notes**: Click the trash icon next to a note to delete it.

## API Endpoints

- **GET /api/notes**: Retrieve all saved notes.
- **POST /api/notes**: Save a new note. Expects a JSON body with `title` and `text`.
- **DELETE /api/notes/:id**: Delete a note by its `id`.

## Technologies Used

- **Express.js**: Web application framework for Node.js.
- **Node.js**: JavaScript runtime for the server-side.
- **UUID**: Generate unique IDs for notes.
- **HTML/CSS/JavaScript**: Front-end structure and design.
- **Bootstrap**: Responsive design framework.

## Contributing

We welcome contributions to enhance the Note Taker application! To contribute, follow these steps:

1. **Fork the repository** on GitHub.
2. **Clone your forked repository**:
   ```sh
   git clone https://github.com/your-username/note-taker.git
   cd note-taker
   ```
3. **Create a new branch**:
   ```sh
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes** and commit them with a clear message:
   ```sh
   git commit -m "Add your feature description"
   ```
5. **Push to your forked repository**:
   ```sh
   git push origin feature/your-feature-name
   ```
6. **Create a pull request** on the original repository.

## Live Demo

Check out the live application [here](https://note-taker.onrender.com).

## Repository

View the source code on GitHub [here](https://github.com/jerrietkuo/NoteTaker).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using Note Taker! We hope this tool helps you stay organized and productive.
```