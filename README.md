# Accept_Payments_with_Python
🧾 UPI QR Code Generator in Python
This project allows users to generate QR codes for popular UPI payment apps like PhonePe, Paytm, and Google Pay using a single UPI ID. It uses the qrcode and Pillow libraries to generate and display QR codes.

📌 Features
Accepts UPI ID from the user

Generates UPI-compatible payment links

Creates QR codes for:

PhonePe

Paytm

Google Pay

Displays the QR codes using your system's image viewer

📦 Requirements
Python 3.x

qrcode library

Pillow (for image display)

Install dependencies using pip:

bash
Copy
Edit
pip install qrcode[pil]
🛠️ How to Use
Clone the repository or copy the script.

Run the script:

bash
Copy
Edit
python upi_qr_generator.py
Enter your UPI ID when prompted:

nginx
Copy
Edit
enter your upi id : = yourname@bank
The script will display 3 QR codes for PhonePe, Paytm, and Google Pay.

💡 Example UPI URL Format
perl
Copy
Edit
upi://pay?pa=UPI_ID&pn=Recipient%20Name&mc=1234
pa: Payee address (your UPI ID)

pn: Payee name

mc: Merchant code (optional)

🖼️ Sample Output
When you run the program, it opens 3 QR code images—one for each app. You can scan these using any UPI-compatible app to make payments.
