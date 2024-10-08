# Blogify

Blogify is a blog website developed using the MERN stack (MongoDB, Express.js, React, Node.js). The application provides a robust platform for users to create, edit, and delete blog posts with a rich text editing experience powered by React-Quill. It features comprehensive user authentication and efficient data storage, ensuring scalability and persistent data management.

## Features

- **User Authentication:** Secure sign-up, login, and user management.
- **Blog Management:** Users can create, edit, and delete their blog posts.
- **Rich Text Editing:** Utilizes React-Quill for a sophisticated text editing experience.
- **Scalable Storage:** MongoDB is used for efficient and scalable data storage.

## Tech Stack

- **Frontend:** React, React-Quill
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB instance running

### Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Adarsh-Agrahari/Blogify-MERN.git
    cd Blogify-MERN
    ```

2. **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    ```

3. **Set up environment variables:**
    Create a `.env` file in the `backend` directory with the following content:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```

4. **Start the backend server:**
    ```bash
    npm start
    ```

5. **Install frontend dependencies:**
    Navigate to the `frontend` directory and install dependencies:

    ```bash
    cd ../frontend
    npm install
    ```

6. **Start the frontend development server:**
    ```bash
    npm start
    ```

7. **Access the application:**
    Open your browser and go to `http://localhost:3000`.

## Usage

- **User Authentication:** Register or log in to access the blog management features.
- **Create Blog Posts:** Use the rich text editor to compose and publish blog posts.
- **Edit/Delete Blog Posts:** Manage your blog posts from the user dashboard.

## Contributing

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, feel free to reach out via email at adarshagrahari0503@gmail.com

## Links

- **GitHub Repository:** [Blogify Repo](https://github.com/Adarsh-Agrahari/Blogify-MERN)

