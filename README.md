# AI Generated Art
This project allows users to generate AI artwork through a web interface. By utilizing advanced machine learning models, the app takes input prompts or parameters and processes them through a backend server to create unique pieces of art. The app provides both frontend and backend components for seamless interaction and the generation of AI-generated art.

## Features
- Web-based user interface for generating AI artwork.
- Backend server to handle user inputs and generate art.
- Customization options for artwork generation (e.g., outpainting, attention details).
- Generate unique pieces of art based on user inputs or parameters.

## Prerequisites
To run the project locally, ensure you have the following installed:
- Node.js (latest version)
- npm or yarn (for package management)
- A modern web browser (Chrome, Firefox, etc.)

## Installation
1. Clone the repository:  
   `git clone https://github.com/nvs0108/AI_Generated_Art.git`
2. Navigate to the project directory:  
   `cd AI_Generated_Art`
3. Install the necessary dependencies for both the client and server:
   - Navigate to the `client/` directory and run:  
     `npm install`
   - Navigate to the `server/` directory and run:  
     `npm install`
4. Run the server:  
   `cd server`  
   `npm start`
5. Run the client:  
   `cd client`  
   `npm start`

This will start the backend server and the frontend client. The frontend will be accessible at `http://localhost:3000`, and the server will be running on its port.

## Usage
Once the app is running, follow these steps:
1. Open the app in your web browser at `http://localhost:3000`.
2. Enter a prompt or set parameters for the AI artwork you'd like to generate.
3. Click the "Generate" button, and the app will process your input and display the generated artwork.
4. You can modify the parameters or enter a new prompt to generate different artwork.

## Project Structure
- **`client/`**: Contains the frontend code, built using JavaScript (React or Vue.js, depending on implementation). This folder allows users to interact with the AI art generation tool.
- **`server/`**: Contains the backend code, which handles requests from the frontend and generates art using machine learning models.
- **`README.md`**: Provides documentation and instructions for setting up and using the app.
- **`cmd.txt`**: A file that may contain command-line instructions or scripts for the project setup or deployment.

## Dependencies
- **Frontend**: React or Vue.js (depending on your setup) for building the user interface.
- **Backend**: Node.js and relevant machine learning libraries for generating AI artwork.

## Contributing
Contributions are welcome! If you'd like to contribute, follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your forked repository (`git push origin feature-branch`).
5. Open a pull request to submit your changes.

## License
This project is open source and free to use.

## Acknowledgments
- Thanks to the creators of the machine learning models used for generating AI artwork.
- Special thanks to [OpenAI](https://openai.com) and other AI researchers for their contributions to generative art technologies.
