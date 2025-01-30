# README: Markdown to Google Docs Converter

## Description
This project provides a Python script that converts Markdown content into formatted Google Docs using the Google Docs API. It supports various Markdown elements such as:
- Headings (`#`, `##`, `###`)
- Bullet points (`- ` and `* `)
- Checkboxes (`- [ ]`)
- Assignee mentions (`@`)
- Horizontal lines (`---`)

## Setup Instructions

### 1. Clone the Repository
```bash
git clone <repository_url>
cd <repository_directory>
```

### 2. Install Dependencies
Ensure you have Python 3 installed. Install required dependencies using:
```bash
pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
```

### 3. Set Up Google Docs API Credentials
1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project.
3. Enable the Google Docs API.

## Running the Script

### Locally
Run the script with:
```bash
python markdown_to_gdoc.py
```

### Google Colab
To run in Google Colab:
1. Upload the `markdown_to_gdoc.ipynb` notebook.
2. Upload the `credentials.json` file to the Colab session.
3. Install dependencies within Colab:
   ```python
   !pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
   ```
4. Run all cells.

## Dependencies
- Python 3+
- `google-auth`
- `google-auth-oauthlib`
- `google-auth-httplib2`
- `google-api-python-client`

## Notes
- Ensure that the Google Docs API is enabled and credentials are correctly set up.
- For troubleshooting, check the Google API quota limits and permissions.

