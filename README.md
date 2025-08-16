Fingerprint Based 0n ATM System

📌 Project Overview

This project simulates an ATM System with Fingerprint Authentication using Python. Instead of traditional ATM PINs, users authenticate using fingerprint images, making transactions more secure. The system provides features like depositing money, withdrawing money, checking balance, and user authentication.

📂 Project Structure

FingerprintATM/
│── Main.py              # Main application entry point
│── DB.txt               # User database with account details
│── req.txt              # Python dependencies
│── run.bat              # Script to run the project on Windows
│
├── BiometricImages/     # Sample fingerprint images
├── static/              # CSS, images, and user assets
├── templates/           # HTML templates (Deposit, Withdraw, Balance, etc.)

⚙️ Requirements

Make sure you have the following installed:

Python 3.7.0

Flask

OpenCV

Numpy

Pillow

Install dependencies from req.txt:

pip install -r req.txt

▶️ How to Run

Clone or download this repository.

Navigate to the project directory:

cd FingerprintATM

Run the application:

python Main.py runserver

Or on Windows:

run.bat

Open your browser and go to:

http://127.0.0.1:5000/index

💡 Features

🔐 Fingerprint Authentication instead of ATM PINs.

💰 Deposit Money into your account.

💸 Withdraw Money securely.

📊 Check Account Balance.

🖼️ User-specific Profiles with fingerprint images.

📷 Screenshots

Fingerprint authentication samples are available in BiometricImages/.

User profile pictures are stored in static/users/.

🚀 Future Enhancements

Integrate with real fingerprint sensors.

Add transaction history.

Improve database (migrate from DB.txt to MySQL/SQLite).

Enhance UI/UX with modern frontend frameworks.

📝 Author

Developed as a Biometric Security + Banking Application Simulation project.

