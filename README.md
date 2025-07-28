# Secrets API Project

A simple Node.js and Express application that fetches and displays random secrets from the [Secrets API](https://secrets-api.appbrewery.com/).

## Features

- Fetches random secrets from a public API
- Renders secrets and usernames using EJS templates
- Basic Express server setup

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [npm](https://www.npmjs.com/) installed

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/pawanthathsara987/secrets-api-project.git
    cd secrets-api-project
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the server:
    ```sh
    node index.js
    ```

4. Open your browser and go to [http://localhost:3000](http://localhost:3000)

## Project Structure

```
.
├── index.js
├── package.json
├── views
│   └── index.ejs
└── README.md
```

## Usage

- Visit the home page to see a random secret and its author.
- Refresh the page to get a new secret.

## License

This project is for educational purposes.
