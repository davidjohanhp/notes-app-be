# Notes App Backend

## Overview

This repository hosts the backend code for a simple notes application, designed to handle CRUD (Create, Read, Update, Delete) operations for notes. 

## Features

- Create new notes
- Retrieve all notes
- Retrieve a specific note by ID
- Update an existing note by ID
- Delete a note by ID

## API Routes

The backend supports the following API routes for managing notes:

### Create a Note

- **Method**: POST
- **Path**: `/notes`

### Get All Notes

- **Method**: GET
- **Path**: `/notes`

### Get Note by ID

- **Method**: GET
- **Path**: `/notes/{id}`

### Update Note by ID

- **Method**: PUT
- **Path**: `/notes/{id}`

### Delete Note by ID

- **Method**: DELETE
- **Path**: `/notes/{id}`

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/davidjohanhp/notes-app-be.git
   ```
2. Navigate to the repository directory:
   ```sh
   cd notes-app-be
   ```
3. Install NPM packages:
   ```sh
   npm install
   ```

### Running the Application

To start the server, run:

```sh
npm start
```

The server will start, and you can begin making requests to the specified endpoints using a tool like Postman or via frontend integration.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
