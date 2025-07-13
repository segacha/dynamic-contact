# 📇 Dynamic Contact – QR-Enabled Digital Contact Card

**Dynamic Contact** is a simple and modern solution to share contact information through a **.vcf (vCard)** file hosted online. By scanning a QR code, users can automatically download and save the contact directly to their phone — no typing needed.

## 🚀 What It Does

- Hosts a `.vcf` file with contact details (name, email, phone number, etc.).
- Generates a **QR code** that links directly to the `.vcf` file.
- When scanned, the device recognizes the vCard and offers to **save the contact** immediately.

Perfect for:
- Networking events  
- Business cards  
- Portfolios and personal sites  
- Digital contact sharing without apps

## ✨ Features

- Fast and easy contact saving via QR scan
- Supports most smartphones and contact apps
- Lightweight and works without backend servers
- Fully customizable `.vcf` content

## 🛠️ Technologies Used

- HTML (to host and link the file)
- `.vcf` (vCard standard format)
- QR code generator (https://github.com/segacha/QR-Generator-with-Logo)

## 🔗 How It Works

1. Create a `.vcf` file with your contact information. Example:
   ```vcf
   BEGIN:VCARD
   VERSION:3.0
   N:Segale;Emilio;;;
   FN:Emilio Segale
   TEL;TYPE=CELL:+49-123456789
   EMAIL:emilio@example.com
   END:VCARD
   
2. Upload it to your repository (e.g., contact.vcf).

3. Generate a QR code that links to the raw .vcf file hosted online:
  https://dynamic-contact-k8i9wqmkq-segachas-projects.vercel.app/contact.vcf

4. Print the QR on a card. Scanning it will prompt the user to save the contact.
