**PROJECT REPORT**

Topic : Steganography Tool for Image/File Hiding

*Abstract*

This project demonstrates the concealment of secret text messages within images using Python's Tkinter library for a graphical user interface and the stegano/Pillow libraries for encoding and decoding data within pixel values. It provides a simple, interactive tool for secure, covert text-based message exchange.

*Introduction*

Steganography is the technique of hiding information inside non-text files such as images, ensuring undetectable transmission of private data. Unlike cryptography, which encrypts data, steganography camouflages its very existence, making it an effective tool for privacy and security.

*Objectives*

* Build a GUI-based application for hiding and revealing secret text messages inside image files.

* Implement encryption (hiding) and decryption (revealing) operations using Python.

* Enhance usability and accessibility with a Tkinter graphical interface.

*Technologies used*

* Python: Core programming language for algorithm and GUI.

* Tkinter: Framework for user interface design.

* Pillow (PIL): Library for image manipulation.

* Stegano: External library for steganography operations (LSB algorithm).

*Methodology*
Functional Workflow
1. Encoding (Hiding Message):

* User selects an image file through the GUI.

* The entered message is encrypted (embedded) into the image's pixel matrix using the Least Significant Bit technique, provided by Stegano.

* Output: A new image containing the hidden message.

2. Decoding (Revealing Message):

* User selects an encoded image.

* The application fetches and displays the secret text by extracting data from the pixel matrix.

*GUI Design*

* The main window includes file selection buttons, message input areas, encode/decode controls, and notification dialogs for operation status.

* Tkinter modules manage window layout, file dialogs, message boxes, and user interaction

*Result*

The developed tool successfully hides and recovers text messages from image files without visible change to the covers.
