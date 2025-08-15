# QA Automation Test Assignment

## 📋 Overview
Your task is to create one automated test for the Electron application from this repository: https://github.com/ant1kdream/qa-manual-task

Installation instructions can be found in the repository's README file.

## 🎯 Requirements
Create **one test** using **TypeScript/Playwright** that covers the file upload functionality.

## 🛠 Test Setup
Before running the test, prepare a folder containing **2 random files** with different extensions (e.g., `.txt`, `.jpg`, `.pdf`, etc.).

## 📝 Test Case Steps
1. Launch the application
2. Perform login (use arbitrary credentials, e.g., `admin/admin`)
3. Simulate drag and drop of the **folder containing files** (folder drag & drop is mandatory)
4. Wait for the upload process to complete
5. Validate the number of files and total size in the upload history

## 📦 Deliverables
- Upload your test code to GitHub
- Include clear instructions for running the test

## 📁 Reference Materials
- Test scenario demonstration: `test-scenario.mov`
- File examples reference: `file-examples.png`

## ⚠️ Important Notes
**Addressing common questions in advance:**

1. **Mock Application**: This is a stub application - no files are actually uploaded anywhere (you can verify this by checking network requests)

2. **Security Warning**: The application lacks a digital signature and may trigger security warnings, as it was built specifically for this test assignment without a developer account

3. **Safety Verification**: You can run the application in a sandbox environment to verify its safety if needed
