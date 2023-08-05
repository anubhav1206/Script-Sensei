# ScriptSensei - Powerful Script Generator



A powerful script generator built using the OpenAI API and the MERN stack (MongoDB, Express, React, Node.js). This application allows users to effortlessly generate high-quality scripts for Advertisements.

## Demonstration

https://github.com/suraj-mahato360/Script-Sensei/assets/97820189/f740e049-f388-4dc0-8fb4-48b03685f143




## Features

- Easy-to-use interface for generating scripts
- Integration with OpenAI API for advanced language processing
- Export scripts in different file formats (PDF, TXT, etc.)
- Responsive design with Tailwind CSS

## Technologies Used

- Front-end: React.js, Tailwind CSS
- Back-end: Open AI API, Express, NodeJs

## Installation

1. Clone the repository: `git clone https://github.com/suraj-mahato360/Script-Sensei.git`
2. Navigate to the project directory: `cd script-sensei`
3. Install dependencies: `npm install`
4. Navigate to the project directory: `cd server`
5. Install dependencies: `npm install`
6. Set up environment variables:
   - Create a .env file in server folder and add environment variable named as API_KEY and give it your openai API key as value.
5. Run the application(in script-sensei): `npm run dev`
5. Run the server: `nodemon server`
6. Open the application in your browser at `http://localhost:XXXX`.

## Usage

1. Access the script generator feature.
2. Customize the script parameters such as genre, length, characters, etc.
3. Click the "Generate Script" button to generate a script using the OpenAI API.
4. Export scripts in your preferred file format.

## To use OpenAI's API key in the ScriptSensei application, follow these steps:

1. Sign up for an OpenAI account:
   If you don't already have an account, go to the OpenAI website (https://openai.com/) and sign up for an account.

2. Obtain your API key:
   Once you have an account, log in to the OpenAI dashboard. Navigate to the API section and find your API key.

3. Set up environment variables:
   In the ScriptSensei project, you'll need to set up an environment variable to store your OpenAI API key securely. Here's how you can do it:

   a. Go to the "server" directory of the project.
   b. Create a new file named `.env` in the "server" directory if it doesn't already exist.
   c. Open the `.env` file in a text editor and add the following line:
      ```
      API_KEY=YOUR_OPENAI_API_KEY
      ```
      Replace `YOUR_OPENAI_API_KEY` with your actual API key obtained from the OpenAI dashboard.

4. Save the `.env` file.

Now, the ScriptSensei application will use the API key specified in the `.env` file when making requests to the OpenAI API.

Please note that it's essential to keep the `.env` file private and not share it publicly, as it contains sensitive information (your API key). The `.env` file is typically added to the `.gitignore` file, so it won't be committed to version control and remains local to your machine. This way, your API key stays secure and is not exposed to others.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Star the repository.
3. Create a new branch: `git checkout -b feature/your-feature`
4. Make your changes and commit them: `git commit -m 'Add your feature'`
5. Push to the original branch: `git push origin feature/your-feature`
6. Create a pull request and describe your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or questions, please contact [suryamahato081@gmail.com].
