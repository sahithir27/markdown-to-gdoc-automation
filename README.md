# README: Markdown to Google Docs Converter

## Description
This project provides a Python script that converts Markdown content into formatted Google Docs using the Google Docs API. It supports various Markdown elements such as:
- Headings (`#`, `##`, `###`)
- Bullet points (`- ` and `* `)
- Checkboxes (`- [ ]`)
- Assignee mentions (`@`)
- Horizontal lines (`---`)

## Setup Instructions

### Set Up Google Docs API
1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project.
3. Enable the Google Docs API.

## Running the Script

### Google Colab
To run in Google Colab:
1. Go to https://github.com/sahithir27/markdown-to-gdoc-automation/blob/main/markdown_to_gdoc.ipynb and click on Open in Colab
4. Run all cells.
5. Validate the result in Google docs

   
### Locally
1. Install Dependencies
Ensure you have Python 3 installed. Install required dependencies using:
```bash
pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client
```
2. Run the script with:
```bash
python markdown_to_gdoc.ipynb
```
3. Validate the result in Google docs



## Dependencies
- Python 3+
- `google-auth`
- `google-auth-oauthlib`
- `google-auth-httplib2`
- `google-api-python-client`

## Notes
- Ensure that the Google Docs API is enabled and credentials are correctly set up.
- For troubleshooting, check the Google API quota limits and permissions.

