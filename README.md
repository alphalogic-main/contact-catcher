# contact-catcherv-1.0
Contact Card Web Page
A responsive, mobile-first web page that serves as a digital contact card for Jabari Alleyne. Visitors can download contact information and an introductory PDF, with options to save the contact card or scan a QR code to access the page.

Features
Circular profile image (automatically styled)

Download buttons for contact card and PDF

QR code section for easy mobile access

Responsive design that works on all devices

Professional styling with hover effects

Required Files
For full functionality, these files should be in the same directory as index.html:

File Name	Description
index.html	Main HTML file (this is the complete web page)
profile.jpg	Your profile photo (will be displayed as a circle)
contact.vcf	Contact card file (vCard format)
intro.pdf	Introductory PDF document
qrcode.png	QR code image that links to this page (optional)
How to Use
Place all files in the same directory

Replace profile.jpg with your own square profile photo

Update the contact.vcf and intro.pdf with your actual files

For QR code functionality, generate a QR code pointing to your page and save as qrcode.png

V1 Update Key Features:
Phone-to-Phone NFC Sharing:

Uses Web NFC API for direct Android-to-Android transfers

Provides real-time status updates during the sharing process

Includes visual feedback with icons and colors

Cross-Platform Support:

Android: Direct vCard transfer via NFC

iOS: Falls back to Web Share API

Desktop: Downloads vCard file

Enhanced User Experience:

Clear instructions for NFC positioning (back-to-back for Android, top for iPhone)

Automatic timeout after 20 seconds

Visual feedback for success/error states

Technical Improvements:

Proper MIME type for vCard transmission

Comprehensive error handling

Clean, modular JavaScript code

How to Use:
For Android Users:

Tap "Share via NFC"

Hold your phone back-to-back with another Android device

The contact will transfer automatically

For iPhone Users:

Tap "Share via NFC"

The system share sheet will appear as a fallback

Choose AirDrop, Messages, etc. to share your digital card

Manual Save:

Tap "Save Contact" to download the vCard on any device
