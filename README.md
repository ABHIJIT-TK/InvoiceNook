# # InvoiceNook

InvoiceNook is an advanced AI-powered application designed to analyze and understand invoice images. Utilizing the capabilities of Google's generative AI models, the application processes and interprets various elements within an invoice to provide detailed insights and answers to user queries.

## Key Features

- **Image Upload and Processing**: Users can upload images of invoices in various formats such as JPG, JPEG, and PNG. The application reads and processes these images to extract relevant data.
- **Generative AI Integration**: The application is integrated with Google's generative AI (Gemini model) to understand and interpret invoice details, generating meaningful responses based on the content of the uploaded invoice and user queries.
- **User Query Handling**: Users can input specific prompts or questions regarding the invoice, and the AI model generates accurate and contextually relevant responses.
- **Invoice Analysis**: The AI can identify and extract critical information from invoices such as dates, amounts, vendor details, itemized lists, and more.

## Technical Details

- **Environment Setup**:
  - Uses the `dotenv` package to manage environment variables securely.
  - Uses the `streamlit` library to create an interactive web application interface.
  - Uses `PIL` (Python Imaging Library) to handle and display image files.

- **API Integration**:
  - Integrates with Google's Generative AI (Gemini model) using the `google.generativeai` package.
  - Configures the AI using an API key stored securely in environment variables.

- **User Interface**:
  - Provides a simple and intuitive web interface for easy image uploading and input of text prompts.
  - Displays results in a readable and user-friendly format.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/InvoiceNook.git
   cd InvoiceNook
2.Requirements
  - pip install -r requirements.txt
3.Execution
 - streamlit run app.py

