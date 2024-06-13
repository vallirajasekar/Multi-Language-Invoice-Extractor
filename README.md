


# Multi-Language Invoice Extractor

This project aims to extract and understand content from multi-language invoices using Google Generative AI (Gemini Model). This reduces the need for traditional OCR methods such as Tesseract and OpenCV.


### Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/invoice-extractor.git
cd invoice-extractor
```

### Step 2: Create the Conda Environment
Create a new Conda environment with Python 3.10.
```bash
conda create -p venv python==3.10 -y
```

### Step 3: Activate the Environment
Activate the Conda environment.
```bash
conda activate "/Users/vallirajasekar/Desktop/gemini/Invoice Extractor/venv"
```

### Step 4: Install Dependencies
Install the required dependencies.
```bash
pip install -r requirements.txt
```

## Usage

1. **Set Up API Key**:
   Make sure to set up your Google Generative AI API key. You can store it in a `.env` file in the root directory of your project:
   ```plaintext
   GOOGLE_API_KEY=your_google_api_key
   ```

2. **Run the Streamlit Application**:
   Start the Streamlit application by running:
   ```bash
   streamlit run app.py
   ```

3. **Upload an Invoice**:
   - Open the Streamlit app in your web browser.
   - Input your prompt in the text box.
   - Upload an invoice image (supports `.jpg`, `.jpeg`, `.png` formats).
   - Click on the "Tell me about the Invoice" button to get the extracted information.

## Description

The **Multi-Language Invoice Extractor** project is designed to simplify the extraction of information from invoices in various languages. Traditional methods like Tesseract OCR and OpenCV require extensive preprocessing and are limited by the quality of the image and language support. By leveraging the power of Google Generative AI (Gemini Model), this project aims to directly understand and extract information from invoice images.

### Key Features:
- **Multi-Language Support**: Capable of understanding invoices in different languages.
- **AI-Powered**: Utilizes Google Generative AI to process the content, reducing the need for traditional OCR.
- **Easy to Use**: Simple web interface to upload images and get results.

### How It Works:
1. **Input Prompt**: The user provides a prompt describing the task (e.g., "Extract invoice details").
2. **Image Upload**: The user uploads an image of the invoice.
3. **AI Processing**: The image and prompt are sent to the Google Generative AI model, which processes the image and returns the extracted content.

## Acknowledgements

This project uses the following technologies:
- [Streamlit](https://streamlit.io/): An open-source app framework for Machine Learning and Data Science.
- [Google Generative AI](https://cloud.google.com/generative-ai): API for advanced AI models.

### Notes
- Ensure you have the necessary API key from Google Cloud for accessing the Generative AI services.
- This project is intended for educational and experimental purposes.

!!! Thank You !!! Visit Us Again :)
```

