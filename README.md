# Email Template Builder

This project is an Email Template Builder that allows users to create, save, and render email templates. It also supports image uploads

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- Git

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/DecodersAdii/Email-Template-Builder.git
    cd Email-Template-Builder
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

## Running the Project

1. Start the development server:

    ```sh
    npm run dev (for vite)

    node server/index.js   (for backend server)
    ```

2. Open your browser and navigate to `http://localhost:3000`.

## API Endpoints

- `GET /api/getEmailLayout`: Fetch the email layout.
- `POST /api/uploadImage`: Upload an image.
- `POST /api/uploadEmailConfig`: Save an email template.
- `GET /api/templates`: Get all saved templates.
- `POST /api/renderAndDownloadTemplate`: Render and download a template.

## Project Structure

- `src/`: Contains the source code of the project.
  - `lib/api.ts`: Contains API functions to interact with the backend.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License.
