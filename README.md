# ISS-Overhead-Notifier
This script sends an email notification when the International Space Station (ISS) is overhead and it's nighttime at your location.

# Features
Uses Open Notify API to track the ISS's location
Uses Sunrise-Sunset API to determine sunrise and sunset times for your location
Sends an email notification when the ISS is overhead and it's nighttime

# Getting Started
Clone the repository or download the code.
Replace MY_LAT and MY_LONG with your own latitude and longitude coordinates.
Replace my_email and password with your own email address and password.
Run the script using Python (e.g., python script.py).

# Requirements
Python 3.x
requests library (install with pip install requests)
datetime library (built-in)
smtplib library (built-in)
time library (built-in)
Gmail account with SMTP access enabled

# Security Note
Make sure to keep your email credentials secure and do not share them with anyone.
Consider using a secure password storage method, such as environment variables or a secrets manager.
