File Encryption and Decryption Tool
This tool provides a secure way to encrypt and decrypt files via the command line on Linux systems. Designed specifically for Kali Linux, it should also be compatible with other Linux-based distributions. Below are the steps to get started, including installation, command usage, and examples.

Prerequisites
Operating System
Linux Distribution: This project is developed for Linux environments, tested specifically on Kali Linux.
Dependencies
OpenSSL: The tool uses OpenSSL for encryption and decryption. If it’s not already installed, you can add it by running:
bash
Copy code
sudo apt-get install openssl
Virtual Machine Setup (if applicable)
If running on a VM such as VMware, ensure it’s correctly configured and has appropriate file access permissions.
Installation
Clone the Repository Clone this repository to your local machine using:

bash
Copy code
git clone https://github.com/yourusername/your-repo-name.git
Replace yourusername and your-repo-name with your actual GitHub username and repository name.

Navigate to the Directory

bash
Copy code
cd your-repo-name
Make the Script Executable Ensure the shell script is executable:

bash
Copy code
chmod +x encrypt_decrypt_script.sh
Usage
This tool offers two main commands:

Encrypt a File
Decrypt a File
Encrypting a File
To encrypt a file, use the following command:

bash
Copy code
./file-encrypt-decrypt -i test.txt -o output.txt
<input_file>: Path to the file you want to encrypt.
<output_file>: Name of the output encrypted file.
<encryption_key>: A secure key for encryption. This should be a strong password that combines letters, numbers, and special characters.
Example:



Decrypting a File
To decrypt a file, use the following command:

bash
Copy code
./file-encrypt-decrypt -i output.txt -o test1.txt


