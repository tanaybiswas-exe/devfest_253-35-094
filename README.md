# Tender Package Builder | AI DevFest 2026

A high-performance, enterprise-grade frontend-only web application built for the **AI DevFest 2026 - Vibe Coding Contest (Solo)** at Daffodil International University.

## Developer Information
* **Full Name:** Tanay Biswas Bandhan
* **Registration / Student ID:** 253-35-094
* **Contest Date:** 6 October 2026

---

## Live Deployment Link
* **Live HTTPS URL:** https://tender-x.netlify.app/

---

## How to Run Locally
1. Clone the repository or download the source code:
   ```bash
   git clone [https://github.com/tanaybiswas-exe/devfest_253-35-094.git](https://github.com/tanaybiswas-exe/devfest_253-35-094.git)
Open the project folder.

Open index.html directly in any modern browser (Google Chrome recommended) or run it using a local development server like VS Code Live Server. No backend setup or database installation is required.

Main Features Completed
JSON Schema Initialization (Task 4.1): Dynamically loads requirements.json to display tender details and required document lists sorted by order.

Secure PDF Repository (Task 4.2): Uploads multiple PDF files at once with real-time page count extraction and safety filters for corrupted or encrypted files.

Exact Duplicate Detection (Task 4.6): Automatically scans file byte contents to flag duplicates and blocks them from separate document matching.

Strict Validation Matrix (Task 4.5 & Section 5): Real-time evaluation of document statuses (Missing, Expiry date needed, Expired, Not provided, OK).

Multi-Language Support (Task 4.9): Full runtime toggle between English and Bangla interface labels and dynamic document titles (title_en / title_bn).

Professional PDF Compilation (Section 6 & Task 4.7/4.8): Generates an official combined PDF package featuring an English Cover Page, structured document stacking, custom page numbering footers (Page X of Y), and a downloadable file format.

Bonus Features Implemented
Index Page: Appends an automated index page right after the cover page showing document start page numbers.

Seal & Signature Integration: Allows uploading a transparent PNG seal/signature and rendering it across custom page ranges.

CSV Audit Export: Exports the complete document checklist and status matrix as an Excel/CSV-compatible audit sheet.

Project Backup & Restore: Export and import workspace configurations via JSON project backup files.

AI Deep Matching: Integrated optional Gemini AI assistance using the user's custom API key to auto-allocate documents.

Known Problems & Limitations
Very large multi-gigabyte PDF bundles may occasionally approach local browser memory thresholds during high-speed page concatenation inside client RAM.

AI Tools Used
Primary AI Assistant: Google Gemini (Code architecture, layout optimization, and logic refinement)

Most Useful Prompt
"Write a robust browser-based JavaScript function using pdf-lib that merges multiple uploaded PDF files, generates an English cover page and index page, calculates exact 'Page X of Y' footers across all pages without overlapping content, and strictly enforces frontend-only constraints."

License
This project is shared under the MIT License.
