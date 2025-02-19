# IBM-SKILLSBUILD-SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY

This project demonstrates image steganography, where secret messages are hidden inside images by modifying pixel values. The messages can be later extracted using the correct passcode.

Features
1. Hide a secret message inside an image
2. Retrieve the message using the correct password
3. Uses OpenCV for image processing
4. Simple and lightweight implementation
Installation
1. Clone the Repository
   cd image-steganography
   
2. Install Dependencies
Make sure you have Python installed. Install the required packages:
  pip install opencv-python numpy

3. Usage
Encoding a Message into an Image
    Place an image (e.g., mypic.jpg) in the same directory.
    Run the script and enter a secret message and passcode:
   python steganography.py
   The encoded image (encryptedImage.jpg) will be generated.
     
4. Decoding the Message from the Image
Run the script again and enter the correct passcode:
   python steganography.py
If the passcode is correct, the hidden message will be displayed.

Example
Encoding
Enter secret message: Hello, World!
Enter a passcode: 1234
Message encoded successfully in encryptedImage.jpg

Decoding
Enter passcode for Decryption: 1234
Decryption message: Hello, World!

If the wrong password is entered:
Enter passcode for Decryption: 0000
YOU ARE NOT auth

5. Requirements
Python 3.x
OpenCV (opencv-python)
NumPy
