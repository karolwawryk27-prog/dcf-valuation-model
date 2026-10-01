# Automated DCF Valuation & Pitchbook Generator

A financial analysis web application built with React that automates the corporate valuation process. The tool fetches historical financial statements, projects future cash flows, calculates the Weighted Average Cost of Capital (WACC), and generates an implied share price. 

Designed to streamline investment banking workflows, it features a one-click export to a formatted PowerPoint slide for immediate use in pitchbooks.

## Key Features
* **Live Financial Data Integration:** Fetches 5 years of historical Income Statements, Balance Sheets, and Cash Flows using the Financial Modeling Prep (FMP) API.
* **Automated Valuation Engine:** Dynamically calculates WACC and runs a 5-year Discounted Cash Flow (DCF) model based on current market conditions.
* **Presentation Ready:** Integrates `pptxgenjs` to automatically generate and download a professional PowerPoint summary slide.
* **Modern UI:** Built with React, Vite, and Tailwind CSS for a clean, responsive, dashboard-style interface.

## Tech Stack
* **Frontend:** React, Vite, Tailwind CSS
* **Data Provider:** Financial Modeling Prep (FMP) API
* **Export:** pptxgenjs
