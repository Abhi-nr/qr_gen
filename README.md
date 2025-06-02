#  QR-Based Registration System
This is a Flask-based web application that allows event organizers to:
Upload a list of authorized participant emails (via Excel)
Automatically generate a unique QR code for registration
Allow participants to register their details (name, interest, LinkedIn, etc.)
Automatically verify their email against the uploaded list
Collect and store all registration data in a secure Excel file
Let the admin share a compiled list of registered participants to everyone via email (with one click)

Features
Admin upload (Excel of allowed emails)
Email verification for participants
Auto-generated QR code for registration link
Participant registration with form (name, interest, LinkedIn, org)
Automatic email distribution of compiled participant data
Excel export with clickable LinkedIn links
Clean, modern UI with blurred background form

Technologies Used
Python 3
Flask
Pandas
openpyxl
Flask-Mail
qrcode
HTML/CSS (no frontend frameworks)




Author
Made by Abhinandana – feel free to reach out!
