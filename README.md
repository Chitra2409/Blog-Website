# Blog-Website

# Daily Journal - A Simple Blogging Website

This is a simple blogging website called "Daily Journal" where users can create, read, and publish their blog posts. The website is built using Node.js with the Express framework and EJS templates for the frontend. It allows users to compose new blog posts and view existing posts. The project is based on the starting files from the Udemy,The Complete 2023 Web Development Bootcamp by Angela Yu.

## Features

- **Home Page:** The home page displays a brief introduction and a list of existing blog posts. Each blog post shows the title and a truncated version of the content, along with a "Read More" link to view the full post.

- **Compose Page:** The compose page allows users to create new blog posts by providing a title and the post content. Upon submitting the form, the new blog post is added to the list on the home page.

- **Individual Post Pages:** Each blog post has its own page with a unique URL. Users can click on the "Read More" link on the home page to view the full content of a specific post.

- **Navigation:** The website has a navigation bar that provides links to the Home, About Us, Contact Us, and Compose pages.

## How to Use

1. Clone the repository from GitHub: https://github.com/Chitra2409/Blog-Website.git
2. Install the required packages by running `npm install`.
3. Run the application using `node app.js` or `npm start`.
4. Access the website by visiting `http://localhost:3000` in your web browser.

## Dependencies

The project uses the following Node.js modules and libraries:

- Express.js: A web application framework that simplifies building web servers.
- Body-parser: A middleware to parse incoming request bodies.
- EJS: A templating engine for generating dynamic HTML content.
- Lodash: A utility library for manipulating arrays, objects, and strings.

## Project Structure

The project is structured as follows:

- `app.js`: The main file that sets up the Express application, defines routes, and starts the server.
- `views`: Contains all the EJS templates used to render different pages.
- `public`: Stores static assets like CSS files and images.
- `partials`: Includes reusable components like the header and footer.

## Contributions

Contributions to this project are welcome! If you find any bugs or have ideas for improvements, feel free to open an issue or submit a pull request.

## Acknowledgments

This project is based on the starting files from the Udemy "The Complete 2023 Web Development Bootcamp by Angela Yu". Special thanks to the instructors for providing the initial resources and guidance.


Happy blogging!
