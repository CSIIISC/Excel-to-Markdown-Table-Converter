# Excel to Markdown Table Converter

A simple web tool to convert raw Excel data into Markdown table format. Paste your Excel data and get instant Markdown table formatting.

![MIT License](https://img.shields.io/badge/License-MIT-green)

## Features

- Convert tab-separated Excel data to Markdown tables
- Automatic column width detection
- Clean markdown table formatting with header separator
- Zero dependencies
- Responsive design

## Usage

1. Clone repository or download `index.html`
2. Open in web browser
3. Copy Excel data (cells should be tab-separated)
4. Paste into input box
5. Click "Convert"
6. Copy formatted Markdown table from output area

## Example Input/Output

**Excel Input:**
Name Age Occupation
Alice 30 Engineer
Bob 25 Designer


**Markdown Output:**
```markdown
|------------|-------|------------|
| Name       | Age   | Occupation |
|------------|-------|------------|
| Alice      | 30    | Engineer   |
| Bob        | 25    | Designer   |
|------------|-------|------------|
```
## Installation

git clone https://github.com/CSIIISC/Excel-to-Markdown-Table-Converter.git
cd Excel-to-Markdown-Table-Converter

Or simply download:

index.html

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Contributions welcome! Please:

Fork the repository

Create your feature branch

Commit your changes

Push to the branch

Open a pull request
