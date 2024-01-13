# Chat with PDFs using Streamlit

This Streamlit application allows users to interactively ask questions related to the content of uploaded PDF files. The application utilizes Streamlit for the user interface, PyPDF2 for PDF processing, and Google Generative AI for generating responses.

## Getting Started

### Prerequisites

- Python 3.x
- Pip (Python package installer)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/ChatwithPDF.git
    ```

2. Navigate to the project directory:

    ```bash
    cd ChatwithPDF
    ```

3. Create and activate a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate  # Windows
    ```

4. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

5. Set up environment variables:

    Create a `.env` file in the project directory and add your Google API key:

    ```
    GOOGLE_API_KEY=your_google_api_key
    ```

### Running the Application

Run the Streamlit app using the following command:

```bash
streamlit run app.py
```
[![Watch the video](thumbnail_image.jpg)](https://github.com/devadigapratham/ChatwithPDF/blob/main/pdfchat.webm)

