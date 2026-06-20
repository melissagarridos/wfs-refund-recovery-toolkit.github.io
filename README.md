<div align="center">

# WFS Settlement Tools

### Browser-Based Toolkit for Walmart Settlement Analysis and Refund Recovery

A lightweight operations tool designed to help eCommerce account managers, reimbursement specialists, and supply chain teams identify refund transactions, analyze Walmart settlement files, and convert raw reports into Excel-ready datasets.

<br>


<br>

<a href="https://melissagarridos.github.io/">Portfolio</a> •
<a href="https://www.linkedin.com/in/melissavgs/">LinkedIn</a> •
<a href="https://github.com/melissagarridos">GitHub</a>

<br><br>

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-Processing-green?style=for-the-badge)
![CSV](https://img.shields.io/badge/CSV-Parser-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production-success?style=for-the-badge)

</div>

---

## Overview

Managing Walmart Fulfillment Services settlement reports can be time-consuming, especially when searching for specific refund transactions across thousands of records.

This project provides a browser-based toolkit that allows users to:

- Search settlement files for refund transactions.
- Filter results by GTIN.
- Export refund data to Excel.
- Convert CSV, TSV, and TXT reports into clean Excel workbooks.
- Process data entirely in the browser without uploading files to external servers.

The application was designed to streamline reimbursement workflows and reduce manual investigation time.

---

## Business Problem

Operations teams often receive large settlement reports containing thousands of rows of transaction data.

Finding refund transactions manually requires:

- Opening large spreadsheets
- Applying multiple filters
- Searching for GTINs individually
- Extracting matching records
- Creating separate reports

This process can be repetitive, error-prone, and time-consuming.

---

## Solution

WFS Settlement Tools automates settlement analysis directly in the browser.

Users upload a settlement report, provide a list of GTINs, and instantly receive all matching refund transactions.

The tool also includes a file conversion utility that transforms CSV, TSV, and TXT files into formatted Excel workbooks.

No backend services are required.

No data leaves the user's device.

---

## Key Features

### Refund Finder

- Upload CSV, XLSX, or XLS settlement files
- Search multiple GTINs simultaneously
- Automatically identify refund transactions
- Filter by Reason Code
- Copy individual values
- Copy complete refund records
- Export results to Excel

### CSV to Excel Converter

- CSV support
- TSV support
- TXT support
- Automatic header detection
- Auto column sizing
- Preview before export
- Excel workbook generation

### Privacy First

All processing occurs locally in the browser.

Files are never uploaded to external servers.

---

## Workflow

```text
Settlement Report
        │
        ▼
 Upload File
        │
        ▼
 Parse CSV / Excel
        │
        ▼
 Filter by GTIN
        │
        ▼
 Detect Refund Transactions
        │
        ▼
 Export Results
```

---

## Technical Highlights

### Client-Side Processing

All file parsing and analysis happens directly in the browser using JavaScript.

### Excel Integration

Supports:

- XLSX
- XLS
- CSV
- TSV
- TXT

### Smart File Detection

Automatically detects:

- Settlement file headers
- Walmart export structures
- Column mappings

### Export Engine

Generates clean Excel reports for reimbursement analysis.

---

## Tech Stack

| Category | Technology |
|-----------|------------|
| Frontend | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript |
| CSV Parsing | PapaParse |
| Excel Processing | SheetJS (XLSX) |
| Deployment | GitHub Pages |

---

## Business Impact

This tool helps operations and reimbursement teams:

- Reduce manual settlement review time
- Accelerate refund investigations
- Improve reporting accuracy
- Simplify GTIN-based searches
- Eliminate repetitive spreadsheet work
- Generate export-ready reports instantly

---

## Skills Demonstrated

- Frontend Development
- File Processing
- Data Parsing
- Browser APIs
- Spreadsheet Automation
- Workflow Optimization
- Business Operations Tooling
- User Experience Design

---

## Future Improvements

- Bulk Settlement Analysis
- Advanced Refund Analytics
- Dashboard Metrics
- Saved Search Templates
- Multi-File Processing
- Reason Code Trend Analysis
- Automated Refund Summaries

---

## Author

### Melissa Garrido

Business Intelligence • Operations Analytics • Product Analytics

Portfolio  
https://melissagarridos.github.io/

LinkedIn  
https://www.linkedin.com/in/melissavgs/

GitHub  
https://github.com/melissagarridos

---

## Project Status

Production-ready and actively used for operational settlement analysis workflows.
