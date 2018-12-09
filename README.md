# SOUL-Airport-luggage-security
Virtually binds a passenger’s identity to his/her luggage using biometrics (fingerprint) and artifact (QR code) to ensure that a passenger can only access luggage he/she owns. SOUL (Security Of Your Luggage) system is a desktop application built using Python, Tkinter and OpenCV.

# Departure
* The passenger inputs his/her fingerprint using a fingerprint scanner which is recorded by the system.  
* The system then generates an encrypted token using this fingerprint and encodes it in the form of a QR code.   
* The QR code is printed and attached to the passenger's luggage.  

# Arrival  
* The passenger picks up his/her luggage and reaches the checkpoint for baggage verification.  
* The passenger inputs his/her fingerprint  
* Next the system scans the QR codes on the luggage and decodes the encrypted token stored within.  
* Now only if the currently given fingerprint matches the one pointed by the QR code, access to bag is allowed.  

# Security  
1. Prevents theft of bags by matching fingerpints at arrival to confirm ownership.  
2. Facility for backup fingerpint at departure.  
