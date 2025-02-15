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

## Notes
- Ensure your SharePoint credentials and site URL are correctly configured.
- Update ChromeDriver if your browser is updated.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

