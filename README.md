# Test Automation UI Project – IT3040 Assignment 1 (Option 2)

## Student Details

- **Registration Number:** IT23326222
- **Module:** IT3040 – ITPM
- **Assignment:** Assignment 1 (Option 2)

---

## Project Description

This project focuses on functional and usability testing of the website: https://www.pixelssuite.com/

Tested features include:

1. Document Conversion
2. PDF Editing
3. Image Resizing
4. Cropping
5. Compression
6. Image Format Conversion
7. Meme Generation
8. Color Picker
9. Image Rotation
10. Image Flipping

---

## Repository

GitHub Repository: https://github.com/sarfy-oss/Test_Aoutomation_UI_ITPM.git

---

## Project Contents

- Manual Test Cases (Excel file)
- Automated Test Script (`image_preview_test.py`)
- Execution Results (`execution_results.csv` and `IT23326422_execution_results.csv`)
- README file

---

## Setup Instructions

1. Install Python (version 3.x)

2. Install dependencies:

```bash
pip install playwright openpyxl
```

3. Install Playwright browsers:

```bash
playwright install
```

---

## Running the Automation Script

Run the script with the target URL and optional slow-motion delay (milliseconds):

```bash
python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
```

Adjust the `--url` parameter to point at different tools on the site when testing specific features.
---

## Notes


- Ensure all required files are inside the project folder before running the script.
- If running for the first time, Playwright will download browser binaries during `playwright install`.
- The automated script uses Playwright; ensure the environment can launch a browser (headless or headed).

---

## Submission Instructions

1. Rename all files using your registration number (e.g., `IT23326222_image_preview_test.py`).
2. Place all files inside one folder named with your registration number.
3. Zip the folder.
4. Upload the zipped folder to CourseWeb according to assignment guidelines.

---

## Author

<<<<<<< HEAD
IT23326222
=======
IT23326222
>>>>>>> 2c22a56b2878a649075a8a7e235736019a48d291
