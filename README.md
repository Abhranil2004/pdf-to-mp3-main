![pdf-to-mp3-main](https://github.com/Abhranil2004/pdf-to-mp3-main/blob/general/image.png)

# PDF to MP3 Converter

This project **pdf-to-mp3.py** is a Python script that converts text extracted from PDF files into speech (MP3 format) using the `PyPDF2` and `gTTS` (Google Text-to-Speech) libraries.

## Features

- Extracts text from PDF files.
- Converts the extracted text to speech in MP3 format.
- Supports multiple languages for text-to-speech conversion.
- Easy to use and lightweight.

## Requirements

- Python 3.x
- [PyPDF2](https://pypi.org/project/PyPDF2/) - Library for reading PDF files.
- [gTTS](https://pypi.org/project/gTTS/) - Google Text-to-Speech library.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/pdf-to-mp3.git
2. Install the required dependencies:

    ```bash
    pip install PyPDF2 gTTS
## Usage
Place the PDF file in the same directory as the pdf-to-mp3.py script.

Run the script:
  ```bash
  python pdf-to-mp3.py
```
Follow the prompts to:

Enter the path of the PDF file.
Provide the output MP3 filename.
The script will extract the text from the PDF and save the generated MP3 file in the same directory.

### Example:
```bash
  python pdf-to-mp3.py sample.pdf
```
This will generate sample.mp3 from the text content of sample.pdf.

### How It Works
The PyPDF2 library is used to extract text from each page of the PDF.
The extracted text is passed to the gTTS (Google Text-to-Speech) engine, which converts it into speech.
The speech is saved as an MP3 file.
Contributing
Contributions are welcome! If you'd like to contribute, feel free to fork the repository and submit a pull request.

### License
This project is licensed under the MIT [License](https://github.com/Abhranil2004/pdf-to-mp3-main/tree/general?tab=security-ov-file) - see the LICENSE file for details.

Author
Abhranil Dutta - [GitHub Profile](https://github.com/Abhranil2004)


### Instructions:
1. Replace `https://github.com/Abhranil2004/pdf-to-mp3-main` with your actual GitHub repository URL.
2. Replace `[GitHub Profile](https://github.com/Abhranil2004)` with the link to your GitHub profile.

This `README.md` file will give users a clear overview of how to use your **PDF to MP3 Converter** project and its requirements.

