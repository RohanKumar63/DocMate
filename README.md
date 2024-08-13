# Full-Stack Document App

This project is a full-stack document application, similar to Google Docs, built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The app allows users to create, edit, and store documents in real-time. It also includes user authentication to ensure that only registered users can access and manage their documents.

## Features

- **User Authentication:** Secure login and registration system using JWT tokens.
- **Document Storage:** Save, update, and retrieve documents using MongoDB.
- **Real-time Collaboration:** Edit documents with others in real-time.
- **Rich Text Editing:** Integrated rich text editor for a better document creation experience.
- **Responsive Design:** Fully responsive UI, optimized for both desktop and mobile devices.

## Installation

### Clone the repository:

```bash
git clone https://github.com/RohanKumar63/DocMate
cd DocMate
```

# Project Name

## Installation

### Server Setup

1. Install server dependencies:

    ```bash
    cd server
    npm install
    ```

### Client Setup

1. Install client dependencies:

    ```bash
    cd ../client
    npm install
    ```

### Environment Variables

1. Set up environment variables:

   - Create a `.env` file in the `server` directory with the following variables:

     ```makefile
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

## Running the Application

### Start the Server

1. Navigate to the `server` directory and start the server:

    ```bash
    cd server
    npm start
    ```

### Start the Client

1. Navigate to the `client` directory and start the client:

    ```bash
    cd ../client
    npm start
    ```

### Access the Application

- Open your browser and go to [http://localhost:3000](http://localhost:3000).

## Technologies Used

### Frontend

- React.js
- Axios (for API calls)
- Quill.js (for rich text editing)
- Tailwind CSS (for styling)

### Backend

- Node.js
- Express.js
- MongoDB (with Mongoose ORM)
- JWT (for authentication)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

