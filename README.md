# double-key-security-system
Here's a Python script that implements a double key security system:  This script does the following:  We define two functions:  hash_password: Takes a password as input and returns its SHA-256 hash. check_password: Takes a password and a hashed password as input and checks if the password matches the hashed version. We set up two secret keys, key1 and key2, which act as the double keys for the security system.  We hash both keys using the hash_password function and store the hashed versions as hashed_key1 and hashed_key2.  We prompt the user to enter the first key using input() and store it in entered_key1.  We check if the entered first key matches the hashed version using the check_password function.  If the first key is correct, we print "First key accepted." and proceed to the next step. If the first key is incorrect, we print "First key incorrect. Access denied." and the script ends. If the first key is correct, we prompt the user to enter the second key using input() and store it in entered_key2.  We check if the entered second key matches the hashed version using the check_password function.  If the second key is correct, we print "Second key accepted. Access granted." and the script ends. If the second key is incorrect, we print "Second key incorrect. Access denied." and the script ends. This double key security system requires the user to enter two correct keys in sequence to gain access. The keys are hashed using SHA-256 for added security, so the actual keys are not stored in plain text.  You can save this code in a file with a .py extension (e.g., double_key_security.py) and run it using a Python interpreter to test the double key security system.
