# auto_contract_generator

An automation tool that reads data from an Excel spreadsheet and populates service provider contract templates, enabling mass contract generation. The completed contracts are automatically saved to a specific folder.

## Description

This project automates the creation of service provider contracts by:
1. Reading contractor information from an Excel spreadsheet (name, address, contact details, etc.)
2. Inserting this data into predefined fields in a contract template
3. Generating individual Word documents for each contractor
4. Saving the documents to a designated folder

## Features

- Batch processing of multiple contracts
- Automatic date insertion
- Customizable contract template
- Organized file naming based on contractor name

## Requirements

- Python 3.6+
- Required libraries:
  - openpyxl
  - python-docx

## Installation

```bash
pip install openpyxl python-docx
```

## Usage

1. Create an Excel file named `fornecedores.xlsx` with contractor information
2. Ensure the spreadsheet has the following columns:
   - Company name
   - Address
   - City
   - State
   - ZIP code
   - Phone
   - Email
   - Sector
3. Create a `contratos` folder in the same directory as the script
4. Run the script:

```bash
python app.py
```

## Important Note

The code in this repository is a simplified demonstration model. Personal and private information from the original request has been removed to protect privacy. You'll need to adapt the template and fields to your specific requirements.

## License

MIT

## Disclaimer

This tool is provided as-is without any warranties. Always review generated contracts before sending them to ensure accuracy and compliance with local laws.
