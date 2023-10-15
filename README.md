Welcome to MovieLand, a React application that allows you to search and explore movies!

# MovieLand React Project

Welcome to *MovieLand*, a React project inspired by the concepts covered in the [React JS Full Course 2023](https://www.youtube.com/watch?v=b9eMGE7QtTk). In this project, we've implemented a simplified version of the Filmpira application, allowing users to search for movies and view details dynamically.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- *Dynamic Movie Search*: Users can search for movies using the provided input field.
- *Live Movie Data*: Utilizes the OMDB API to fetch real-time data about the searched movies.
- *Responsive Design*: The application is designed to work seamlessly on both desktop and mobile devices.
- *Modular Components*: Leveraging React components for a clean and maintainable code structure.
- 

## Technologies Used

- *React*: The core library for building the user interface.
- *OMDB API*: Provides movie data for dynamic content.
- *CSS*: Styling the components for a visually appealing interface.


## Installation

1. Clone the repository:

    ```bash
    git clone  https://github.com/onkaryemul/MovieLand-React-Project.git
    ```

2. Navigate to the project directory:

    ```bash
    cd MovieLand
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

1. Get your OMDB API key by following the instructions in the [OMDB API](https://www.omdbapi.com/apikey.aspx) documentation.

2. Create an `.env` file in the root directory and add your OMDB API key in it:

   ```env
   REACT_APP_API_KEY=your_api_key_here
   ```
   
   Replace `your_api_key_here` with your actual OMDB API key.

3. Start the development server:

    ```bash
    npm start
    ```
    
4. Open your browser and go to [http://localhost:3000](http://localhost:3000) to see the MovieLand website in action.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.
