# SkipTheQ Website

This project provides a web application for SkipTheQ, a service that allows users to avoid waiting in lines. Users can register and get their order on the table itself.

**Features:**

* User registration and login
* Real-time order updates
* Push notifications for turn alerts for the employee who will take the food to the customer.

**Installation:**

This project is built using Docker. To run the application locally:

1. Clone this repository.
2. Build the Docker image: `docker build -t skiptheq-website .`
3. Run the container: `docker run -p 80:80 skiptheq-website`

**Usage:**

Visit `http://localhost:80` in your web browser to access the SkipTheQ website.

**Development Setup:**

* This project requires Node.js and npm (or yarn).
* Clone the repository and run `npm install` to install dependencies.

**Contributing:**

We welcome contributions to this project!