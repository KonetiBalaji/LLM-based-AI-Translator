# Polyglot LLM Translator

A professional multilingual translation web app powered by Facebook's MBART-50 model and Streamlit. Instantly translate text between 12 major languages, listen to translations with text-to-speech, and download results.

## Features

- Translate text between:
  - English, Hindi, French, Spanish, Russian, Chinese (Simplified), German, Italian, Arabic, Portuguese, Japanese, Korean
- Uses Facebook's MBART-50 transformer model for high-quality translations
- Text-to-speech audio playback and download using gTTS
- Download translated text as a file
- Keeps a short translation history in your session

## Requirements

- Python 3.10.13
- See [requirements.txt](requirements.txt) for Python dependencies

## Installation

1. Clone this repository or copy the files to your local machine.
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

Run the Streamlit app:

```sh
streamlit run app.py
```

Open the provided local URL in your browser to use the translator.

## File Structure

- `app.py` &mdash; Main Streamlit application
- `requirements.txt` &mdash; Python dependencies
- `.python-version` &mdash; Python version for the project
- `README.md` &mdash; Project documentation

## Acknowledgements

- [Facebook MBART-50](https://huggingface.co/facebook/mbart-large-50-many-to-many-mmt)
- [Streamlit](https://streamlit.io/)
- [gTTS](https://pypi.org/project/gTTS/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.