# Russia Magnit Sales Automation

## Description
This project automates the process of logging into the Russia Magnit Seller Portal, generating a sales report, downloading it, and merging it with existing data from SharePoint. The script ensures duplicate-free updates and re-uploads the final file back to SharePoint.

## Features
- Automated login to Russia Magnit Seller Portal using Selenium
- Sales report generation and download handling
- Data merging and duplicate removal with Pandas and OpenPyXL
- Integration with SharePoint for file upload and download

## Prerequisites
- Python 3.10+
- Google Chrome & ChromeDriver
- A SharePoint account with access permissions

## Required Libraries
- `selenium`
- `pandas`
- `openpyxl`
- `office365`

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/RussiaMagnitAutomation.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Configure your credentials inside the script (`username`, `password`, `site_url`, etc.)
4. Set the path to your download folder in `download_folder`

## Usage
To run the script, execute:
```bash
python magnit_sales_automation.py
```
The report will be downloaded, merged with existing data, and uploaded to SharePoint.

## Notes
- Ensure your SharePoint credentials and site URL are correctly configured.
- Update ChromeDriver if your browser is updated.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

