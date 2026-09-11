# Easy To Finance Service - Digital Loan Application Portal

A modern, responsive, and fully digital loan application and documentation platform for **Easy To Finance Service** (Kalna-713409).

## 🚀 Key Features

1. **Fully Digital Multi-Section Form**:
   - Covers all fields from the physical 4-page loan agreement:
     - Customer Personal Details (Name, Guardian, Mother's Name, DOB, Age, Gender, Religion, Address, Landmark, Village, Town/City, District, State, PIN).
     - Employment & Occupation Details (Govt / Private Salaried, Self Employed, Monthly Income).
     - KYC Details (PAN, Aadhaar, Mobile, WhatsApp, Alternate Mobile, Email).
     - References (2 Family/Personal References with Name, Relation, and Mobile).
     - Customer Bank Details (Bank Name, Account Holder Name, Account Number, Branch, IFSC Code, Account Type, Dealer Name).
     - Product & Financing Details (Product Name, Model, Dual IMEI numbers, Price, Down Payment, Tenure, Monthly EMI, Processing Charges, Other Charges, Total Finance Amount, Amount in Words).

2. **📸 Live Camera Photo Capture & Upload**:
   - Direct web camera integration (`navigator.mediaDevices.getUserMedia`) with live face guideline overlay.
   - 1-click snapshot capture and instant preview.
   - Retake button and optional file upload fallback.

3. **✍️ Interactive Digital Signature Pads**:
   - Touch and mouse-enabled HTML5 Canvas signature pads for both **Customer Signature** and **Sales Officer's Signature**.
   - Clear/Redo controls with automatic embedding into all 4 document pages.

4. **⚡ Smart Automation & Helpers**:
   - Auto-calculates Age from Date of Birth (DOB).
   - WhatsApp number sync toggle ("Same as Mobile").
   - Real-time loan mathematics: Finance Amount and Monthly EMI calculation.
   - Automatic Indian Currency Number-to-Words converter (e.g., `Rs. 15,500` -> `Fifteen Thousand Five Hundred Rupees Only`).
   - "Fill Sample Data" button for testing and verification.

5. **📄 Exact 1:1 Replica 4-Page Output**:
   - **Page 1**: Customer Details, Live Photo Box, Occupation, KYC, References, and Signatures.
   - **Page 2**: Customer Bank Details, Product Details, Loan Calculations, Agreement Clause, and Signatures.
   - **Page 3**: Self-Declaration with official 5 clauses, penalty terms (472, 128, 230), Date, Place (KALNA), and Customer Signature.
   - **Page 4**: Formal Application Letter addressed to The Manager, Easy to Finance Service, Kalna-713409, with verified attachments list and signature.

6. **🖨️ Pixel-Perfect Print & "Save as PDF"**:
   - Native browser print optimization (`@media print`) configured with exact A4 portrait dimensions (`210mm x 297mm`).
   - Clean page-breaks ensuring zero blank pages or accidental spillover.

## 💻 Tech Stack
- Pure HTML5 / CSS3 / Vanilla JavaScript (Zero npm dependencies, zero build step needed).
- Tailwind CSS for modern responsive screen design.
- HTML5 MediaDevices API for camera capture.
- HTML5 Canvas API for digital ink signatures.
- Standard CSS Paged Media (`@page`, `@media print`) for exact A4 physical replication.
