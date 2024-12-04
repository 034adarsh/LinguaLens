# Still Work In Progress
# AI-Based Language Translation for Financial Data Files

This project provides a robust solution for translating file headers and content from various languages (e.g., Arabic) into English. It is designed specifically for use in auditing and assurance processes, enabling teams to work seamlessly with multilingual data.

## Features
- **File Type Recognition**: Automatically detects and processes files of types:
  - Excel (.xlsx)
  - CSV (.csv)
  - PDF (.pdf)
- **Accurate Translation**: Utilizes advanced translation models to translate text effectively.
- **User-Friendly Interface**: Supports easy file upload and translation display.
- **Modular Design**: Backend is ready for integration with any frontend framework.

---

## Project Structure
```
├── app
│   ├── model.py           # Core translation logic
│   ├── file_processor.py  # Handles file reading and parsing
│   ├── requirements.txt   # Python dependencies
├── tests                  # Unit tests for model and file processing
├── frontend               # Placeholder for frontend integration
├── README.md              # Project documentation
```

---

## Installation

### Prerequisites
1. Python 3.8+
2. Virtual Environment (optional but recommended)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/LinguaLens/language-translation-project.git
   cd language-translation-project
   ```
---

## Usage

### Running the Translation Model
1. Place your file (Excel, CSV, or PDF) in the working directory.
2. Execute the main script:
   ```bash
   python app/model.py
   ```
3. The translated content will be saved or displayed as per the configuration.

---

## Core Functionality

### File Processing
The system automatically recognizes and processes files:
- **Excel & CSV**: Extracts tabular data and translates text in specified columns (e.g., `Account name`, `Description`).
- **PDF**: Extracts and translates textual content using `PyMuPDF`.

### Translation
Uses the `googletrans` library for translating Arabic (or other languages) into English. Can be extended to use advanced models from Hugging Face or OpenAI for improved performance.

---

## Future Enhancements
1. **Frontend Integration**:
   - Build a Streamlit-based UI for file upload and results display.
2. **Custom Translation Models**:
   - Replace `googletrans` with in-house or advanced translation models for better domain-specific accuracy.
3. **Error Handling**:
   - Add detailed error messages for unsupported file types or processing failures.

---

## Contributing
We welcome contributions! To contribute:
1. Fork this repository.
2. Create a new branch for your feature/bugfix.
3. Commit and push your changes.
4. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact
For any queries or support, please reach out to:
- **Developer**: Adarsh Kumar Singh
- **Email**: adarsh36jnp@gmail.com
