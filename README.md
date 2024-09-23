# OAuth with Google Sign-In

This project utilizes OAuth with Google Sign-In to allow users to sign up and authenticate using their Google accounts.

## Prerequisites

Before getting started, make sure you have the following:

- A Google Cloud Platform (GCP) project with the necessary credentials set up.
- The required client ID and client secret from the GCP project.

## Installation

To install and run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-project.git
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Set up the environment variables:

    - Create a `.env` file in the root directory of the project.
    - Add the following variables to the `.env` file:

      ```bash
      CLIENT_ID=your-client-id
      CLIENT_SECRET=your-client-secret
      ```

4. Start the development server:

    ```bash
    npm start
    ```

## Usage

Once the server is running, you can access the application at `http://localhost:3000`. The application provides a Google Sign-In button on the sign-up page. Clicking on the button will initiate the OAuth flow and allow users to sign up using their Google accounts.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

# O Basics
Open Authorization
<<<<<<< HEAD

Open authorization is an open prptocol to allow secure authorization in a simple and standard method from web, mobile and desktop applications.

It is used in 
- Web apps
- Desktop apps
- Mobile apps
- JavaScript or browser-based apps
- Server-side apps
- Mashups

-> Getting protected data from an application. It is safer and more secure than asking users to login with passwords.
-> Use OAuth to let application developers securely get access to user's data without sharing their passwords.

