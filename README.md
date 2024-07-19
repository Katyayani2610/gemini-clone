# Gemini Clone

Gemini Clone is a web application that leverages Google's Gemini Generative AI model to provide users with a platform for generating and interacting with AI-generated content. It features an intuitive sidebar for navigation and a dynamic main content area for displaying results.

## Live Demo

Explore the live demo of Gemini Clone at [Gemini Clone Live Demo](https://gimini-alter.netlify.app/).

## Features

- **Interactive Sidebar**: Navigate through recent prompts and access sections like Help, Activity, and Settings.
- **Content Generation**: Generate content using the Gemini Generative AI model based on user input.
- **Recent Prompts**: View and re-use recently entered prompts for convenience.
- **Loading Indicator**: Provides visual feedback during content generation.
- **Responsive Design**: Optimized for various screen sizes and devices.

## Technologies Used

- **Frontend**: React with Vite
- **Styling**: CSS
- **Backend**: Google Generative AI

## Installation

To run the Gemini Clone project locally, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/gemini-clone.git
   cd gemini-clone

2. **Install Dependencies**
   
   Ensure you have Node.js installed. Install the project dependencies using:
   
   ```bash
   npm install

3. **Set Up Environment Variables**
   
   Create a .env file in the root directory of the project and add your API key. The .env file should look like this:

   ```bash
   VITE_REACT_APP_GOOGLE_GEN_AI_API_KEY=your_api_key_here

  Replace your_api_key_here with your actual API key from Google Generative AI.
  
4. **Start the Development Server**
   
   Run the development server with the following command:

   ```bash
   npm run dev
The application will be available at http://localhost:5173.

## Usage

- **Sidebar**: Click on the menu icon to expand or collapse the sidebar. Use the sidebar to access recent prompts and navigate to different sections of the app.
- **Main Area**: Enter a prompt in the input field and click the send icon to generate content. The results will be displayed in the main content area.
- **Settings**: Adjust settings and preferences through the sidebar menu.

## Troubleshooting

- **API Key Issues**: Ensure that your API key is correctly set in the `.env` file and that it is valid.  
- **Loading Issues**: Check the browser console for errors and ensure that all dependencies are correctly installed.

   
