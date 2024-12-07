# Netflix Clone  

A Netflix-inspired streaming platform built using the MERN stack, showcasing movie and TV show trailers, user authentication, and content browsing functionality.  

## Features  

### Frontend  
- **ReactJS**: Built a responsive and modern UI.  
- **Redux Toolkit**: State management for efficient data handling.  
- **Tailwind CSS**: Styled components for a sleek and mobile-friendly design.  
- **TMDB API Integration**: Fetching movie and TV show data dynamically.  
- **Interactive Features**:  
  - Browse and search movies.  
  - View trailers upon clicking on thumbnails.  

### Backend  
- **NodeJS and ExpressJS**: Backend server for handling API requests.  
- **MongoDB**: Database for user data and authentication.  
- **Custom APIs**: Endpoints for fetching content and user authentication.  
- **Authentication**: JWT-based login, logout, and registration.  
- **Route Protection**: Ensuring secure access to specific features.  

## Technology Stack  
- **Frontend**: ReactJS, Redux Toolkit, Tailwind CSS  
- **Backend**: NodeJS, ExpressJS  
- **Database**: MongoDB  
- **API**: TMDB  

## Installation  

1. Clone the repository:  
    ```bash
    git clone https://github.com/<your-username>/netflix-clone.git  
    cd netflix-clone  
    ```

2. Install dependencies and start the project:  

    ```bash
    npm install  
    cd client && npm install  
    cd ..  
    npm start # Start backend server  
    cd client && npm start # Start frontend server  
    ```

3. Add a `.env` file for environment variables:  

    ```plaintext
    TMDB_API_KEY=<your_tmdb_api_key>  
    MONGO_URI=<your_mongodb_connection_string>  
    JWT_SECRET=<your_jwt_secret_key>  
    PORT=5000  
    ```

4. Open your browser and visit:  
    ```
    http://localhost:3000
    ```


Screenshots
![netflix clone ss](https://github.com/user-attachments/assets/1c8ab9c8-4595-4a51-b769-c45246d8d54e)


Contributions
Feel free to contribute! Fork the repository and submit a pull request.

License
This project is licensed under the MIT License.
