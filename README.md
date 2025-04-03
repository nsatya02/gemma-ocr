# AI-Powered OCR and Data Analysis Suite with Airbnb Integration

This project combines powerful OCR capabilities using the Gemma-3 Vision model and Streamlit to create a 100% locally running computer vision app that can perform both OCR and extract structured text from the image.

A Streamlit-based OCR application that extracts text from images, PDFs, and Word documents using the Gemma-3 Vision model


## Repository Structure
```
.
├── gemma-ocr/                  # OCR application directory
│   ├── app.py                  # Basic OCR implementation for images
│   ├── app1.py                # Enhanced OCR with PDF/DOCX support
│   └── requirements.txt       # Project dependencies

```

## Usage Instructions
### Prerequisites

Required Python packages:
```
streamlit
ollama
PyPDF2
pillow
python-docx
```

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Install dependencies:
```bash
# Install OCR application dependencies
cd gemma-ocr
pip install -r requirements.txt

```

3. Install Ollama and the Gemma-3 model:
```bash
# macOS
ollama pull gemma3:12b
```

### Quick Start

1. Launch the OCR application:
```bash
cd gemma-ocr
streamlit run app1.py
```

### More Detailed Examples

#### OCR Usage
1. Navigate to the Streamlit application in your browser
2. Upload an image, PDF, or DOCX file using the sidebar
3. Click "Extract Text" to process the document
4. View the extracted text in structured Markdown format



## Data Flows

```ascii
Document Input → Gemma-3 OCR → Structured Text Output

```