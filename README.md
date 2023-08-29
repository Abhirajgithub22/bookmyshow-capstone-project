# BookMyShow Project

## Introduction

Welcome to the BookMyShow project! This is a web application that allows users to book movie tickets online. Users can browse available movies, select a movie, choose a showtime, and book their desired seats. The project uses both local storage and MongoDB for temporary and permanent data storage, respectively.

## Features

- Browse a list of available movies with details such as movie name and showtimes.
- Select a movie and view available showtimes for that movie.
- Reserve seats for a selected showtime.
- Store temporary booking details using local storage to allow users to continue their booking process even if they close the browser or refresh the page.
- Save completed bookings to MongoDB for permanent storage and retrieval.
- View the details of the last booked movie.

## Getting Started

### Prerequisites

Before running the project, make sure you have the following prerequisites installed on your system:

- Node.js and npm: Install from [https://nodejs.org/](https://nodejs.org/)

### Installation

1. Clone the repository from GitHub:

```
git clone https://github.com/Abhirajgithub22/bookmyshow-capstone-project.git
cd bookmyshow-capstone-project
```

2. Install the required dependencies:

```
npm install
```

3. Set up the MongoDB connection:

   - Ensure you have MongoDB installed and running on your system.
   - Create a MongoDB database for the BookMyShow project and note down the connection string.

4. Configure the application:

   - Create a `.env` file in the root directory of the project.
   - Add the following environment variables to the `.env` file:

   ```
   PORT=8080                  # The port on which the application will run
   MONGODB_URI=your_uri_here  # The MongoDB connection string
   ```

## Usage

1. Start the application:

```
npm start
```

2. Access the BookMyShow application in your web browser at `http://localhost:3000`.

3. Browse the list of available movies and select a movie to view available showtimes.

4. Choose a showtime and reserve your desired seats.

5. Complete the booking process by providing necessary information.

6. You can view your last booked movie on the homepage.

## Technologies Used

The BookMyShow project uses the following technologies:

- Node.js and Express.js for the server-side application.
- MongoDB with Mongoose for permanent data storage.
- Webpack for bundling and managing frontend assets.
- Babel for transpiling modern JavaScript code for better browser compatibility.
- React for building the user interface.

## Deployment links 

Frontend:- [https://bookmyshow-capstone-project-vqsp-1xym5ypll-abhirajgithub22.vercel.app/](https://bookmyshow-capstone-project-vqsp-1xym5ypll-abhirajgithub22.vercel.app/)

Backend:- [https://bookmyshow-ss.onrender.com/api/booking](https://bookmyshow-ss.onrender.com/api/booking)


## License

The BookMyShow project is licensed under the MIT License. You can find the license details in the [LICENSE](LICENSE) file.

---

Thank you for using BookMyShow! If you have any questions or need further assistance, feel free to contact us or open an issue in the repository. Happy movie booking!
