# Product Ingredient Analyzer

**Product Ingredient Analyzer** is a Streamlit-based web application designed to help users analyze product ingredient lists. The application provides several options for image input, such as uploading an image, taking a photo with a camera, or selecting from predefined example images. The system processes the image and provides an analysis of the product's ingredients using a powerful AI model integrated with tools like Gemini and Tavily.

---

## Features

- **Upload Image:** Users can upload a product image containing an ingredient list for analysis.
- **Capture Photo:** Take a photo of the product directly using a connected camera.
- **Example Products:** Choose from a collection of example product images for testing.
- **Ingredient Analysis:** Analyze the ingredient list of any uploaded or selected product image.
- **API Integration:** Supports integration with Tavily and Google APIs for enhanced analysis capabilities.

---

## Setup and Requirements

### Prerequisites
- Python 3.8 or higher.
- API keys for:
  - **Tavily** (for ingredient analysis).
  - **Google** (if required by the analysis model).

### Libraries and Dependencies
The application relies on the following Python libraries:
- `streamlit`
- `os`
- `PIL` (Pillow)
- `phi.agent`, `phi.model.google`, `phi.tools.tavily`
- `tempfile`

Ensure you have these libraries installed in your environment. Use the command `pip install -r requirements.txt` to install dependencies if a `requirements.txt` file is available.

---

## How to Use

### 1. Run the Application
Start the Streamlit app by running:
```bash
streamlit run app.py
