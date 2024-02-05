# Random Quotes Generator

A simple and lightweight random quotes generator that provides inspirational and motivational quotes for your projects.

## Overview

This project is a random quotes generator that allows users to retrieve a variety of quotes for inspiration and motivation. It's designed to be easy to integrate into different applications or websites.

## Features

- Generates random quotes on-demand.
- Provides a RESTful API for easy integration.
- Supports different categories of quotes.

## Getting Started

### Prerequisites

- Node.js installed
- npm package manager

### Installation

1. Clone the repository:

    ```bash
    [https://quotsgenrator.netlify.app/]
    ```

2. Navigate to the project directory:

    ```bash
    cd random-quotes-generator
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

### Usage

1. Start the server:

    ```bash
    npm start
    ```

2. Access the API to get a random quote:

    ```bash
    curl "https://api.quotable.io/random"
    ```

    Example response:

    ```json
    {
      "quote": "The only way to do great work is to love what you do.",
      "author": "Steve Jobs"
    }
    ```

## API Endpoints

- **Get a Random Quote:**
  - Endpoint: `/quotes/random`
  - Method: `GET`

- **Get Quotes by Category:**
  - Endpoint: `/quotes/category/{category}`
  - Method: `GET`

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

Please follow our
 ```bash
    [https://github.com/Chandruvijayakumar/]
    ```
for more details



