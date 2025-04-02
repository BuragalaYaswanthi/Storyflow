# StoryFlow

StoryFlow is an AI-powered image-based storytelling web application built with Flask and OpenAI's GPT model. Users can upload multiple images, select a story genre, and generate engaging stories based on AI-generated image captions.

## Features
- Upload multiple images
- Generate captions using BLIP (Bootstrapping Language-Image Pretraining)
- AI-generated story creation based on image captions
- Choose different genres (Comedy, Horror, Action, Romance, Fantasy, Mystery)
- Simple and interactive web interface

## Tech Stack
- **Backend**: Flask, OpenAI GPT, Transformers (BLIP model)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: None (currently using real-time processing)
- **AI Models**: OpenAI GPT-3.5, BLIP for image captioning

## Installation
### 1. Clone the repository
```sh
git clone https://github.com/BuragalaYaswanthi/Storyflow.git
cd Storyflow
```

### 2. Set up a virtual environment (optional but recommended)
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate    # On Windows
```

### 3. Install dependencies
```sh
pip install -r requirements.txt
```

### 4. Set up OpenAI API Key
Replace `your-openapi-key-here` in `app.py` with your actual OpenAI API key.

### 5. Run the Flask application
```sh
flask run
```

The application will be available at `http://127.0.0.1:5000/`.

## Usage
1. Open the web app in a browser.
2. Upload multiple images.
3. Choose a story genre.
4. Click "Generate Story" to receive an AI-generated story based on the uploaded images.

## Future Improvements
- Implement user authentication.
- Store generated stories in a database.
- Improve UI/UX with a modern design.
- Deploy on a cloud platform (Heroku, Render, or AWS).

## Contributing
Contributions are welcome! Fork the repository, create a new branch, and submit a pull request with your improvements.

## License
This project is open-source and available under the MIT License.

## Authors
- [@manu9986](https://github.com/manu9986)
- [@BuragalaYaswanthi](https://github.com/BuragalaYaswanthi)

