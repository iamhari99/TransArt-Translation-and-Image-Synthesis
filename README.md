# TransArt: A Multimodal Application for Vernacular Language Translation and Image Synthesis

This project is a unique application that translates Tamil text into English, generates a creative image based on the translated text, and provides an AI-generated creative description. It demonstrates the integration of Google Translate, Stable Diffusion for image generation, and GPT-2 for creative text generation using Gradio for a user-friendly interface.

## ✨ Project Features
- **Translate Tamil to English**: Converts Tamil input into English using Google Translate API.
- **Generate Images**: Uses Stable Diffusion to create an image inspired by the translated text.
- **Creative Text Generation**: Employs GPT-2 to generate creative descriptions based on the translated input.
- **Interactive Gradio Interface**: Provides an engaging, easy-to-use UI for users to input text and view outputs.

## 🚀 Technologies Used
- **Python**: Core language for the project.
- **Google Translate API**: For translating Tamil text to English.
- **Stable Diffusion**: To generate AI-based images from text prompts.
- **GPT-2 via Hugging Face Transformers**: To generate creative text.
- **Gradio**: For building an interactive web interface.
  
## 🎨 User Interface
The interface features:
- A **textbox** for Tamil text input.
- Display sections for **translated text**, **generated image**, and **creative text**.
- A **Generate** button for processing the input text.

The UI is customized with CSS for a visually appealing layout:
- Beige background, orange title, black descriptive text, and a red Generate button.

## 📷 Screenshot
![App Screenshot](./path-to-your-screenshot.png)

## 🛠️ Setup Instructions

### Prerequisites
- Python 3.7+
- Required libraries: `google-cloud-translate`, `torch`, `diffusers`, `transformers`, `gradio`
- Google Cloud account with API credentials for Translate API.

### Installation

1. **Clone this repository**:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up Google Translate API credentials**:
    - Get your `credentials.json` file from Google Cloud.
    - Place `credentials.json` in the root directory of your project.
    - Set the environment variable:
      ```python
      export GOOGLE_APPLICATION_CREDENTIALS="credentials.json"
      ```

4. **Run the application**:
    ```bash
    python app.py
    ```

### Running the App in Gradio
Gradio will launch the app and provide you with a local and a shareable link (optional) to access the app in a browser.

## 📚 Usage
1. **Enter Tamil Text**: Type in the Tamil text you want to translate.
2. **Generate Output**: Click on the **Generate** button.
3. **View Results**: See the translated text, generated image, and creative description in the output sections.

## 🔧 Configuration and Customization
- **CSS Styling**: Modify the CSS in the code to customize the background, text colors, and button styles.
- **Parameters**: Adjust GPT-2 and Stable Diffusion parameters (e.g., `temperature`, `max_length`) for different creative effects.

## 📄 License
This project is licensed under the MIT License.

---

Feel free to contribute to this project or suggest improvements. For any questions, open an issue or contact me.

**[Your Name]**  
[Your Contact Information or GitHub Profile Link]
