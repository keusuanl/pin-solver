# 🔐 4-Digit PIN Brute-Force Script
This is a Python script that performs a brute-force attack on a **4-digit PIN authentication system**. It automates the process of trying all possible PINs (`0000` - `9999`) to find the correct one.

# Best Use Cases
This script is useful in scenarios like:
- 🔍 **CTF Challenges** – Trying PIN-based challenges in Capture The Flag (CTF) competitions.  
- 🛠️ **Pentesting Web Applications** – Testing the security of web apps with **4-digit PIN authentication**.  
- 🔓 **Password Recovery** – If a user forgets a **simple PIN code**, this can help recover access (with permission).  
- 🧪 **API Testing** – Checking how a server handles repeated PIN attempts.  

> ⚠️ **Important:** This script is for **legal penetration testing and ethical hacking**. Unauthorized use is strictly prohibited! 

## 🚀 Features
- Uses **requests** to send HTTP requests to a target server.
- Brute-forces **numeric PINs** efficiently.
- Stops when the **correct PIN** is found.
- Allows **user input** for IP, port, and target URL.

# 🛠️ **Usage**
### 📌 **Prerequisites**
- Install Python (>= 3.x)
- Install the `requests` library if not installed:
  ```bash
  pip install requests
  ```


# RUNNING THE SCRIPTS 

## Clone the Repo
git clone https://github.com/keusuanl/hacktavis.git
cd hacktavis

## Run the Scripts 
python3 pin-solver.py

Enter the IP address, port, and the target endpoint when prompted

#Example Output

```
└─$ python3 pin-solver.py 
Enter Target IP:  94.237.54.190
Enter Target Port:  55358

<SNIP>
Attempted PIN: 0001
Attempted PIN: 0002
Attempted PIN: 0005
Attempted PIN: 0006
Attempted PIN: 0007
Attempted PIN: 2072
Attempted PIN: 2073
Correct PIN found: 2073
```




