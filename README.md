This Python script provides a graphical user interface (GUI) for encrypting text files using a simple substitution cipher. Here's a breakdown of its functionality:

<p align="center">
	<img width="460" alt="Enkrpt" src="https://github.com/jogamel/substitution_cipher_encryption/assets/123499578/ff90463f-7768-4545-9c11-3e1c46a4d89c">
</p>

The source code: *enkrpt.py*

**Importing Libraries**: The script imports the necessary libraries, including tkinter for GUI components and filedialog for file browsing dialogs.

**Encrypt Text Function**: This function (encrypt_text) takes three parameters: the path of the input file, the path of the output file, and a key for encryption. It reads the text from the input file, converts it to lowercase, performs encryption using a substitution cipher based on the provided key, and writes the encrypted text to the output file.

**Browse File Function**: This function (browse_file) is called when the user clicks the "Browse" button next to the input file entry. It opens a file dialog for selecting a file and populates the corresponding entry field with the selected file path.

**Encrypt Function**: This function (encrypt) is called when the user clicks the "Encrypt" button. It retrieves the input file path, output file path, and encryption key from the GUI inputs, calls the encrypt_text function, and displays the result in the GUI.

**GUI Setup**: The script creates a tkinter window (window). It then creates labels, entry fields, and buttons for input file selection, output file selection, key entry, encryption, and result display.

**Main Loop**: Finally, it starts the tkinter event loop (window.mainloop()), which keeps the GUI application running until the user closes the window.

You can use this script to encrypt text files using a substitution cipher and provide a simple GUI interface for users to interact with.
