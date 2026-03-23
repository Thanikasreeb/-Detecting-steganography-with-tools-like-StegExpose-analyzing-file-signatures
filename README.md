# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures
## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

## DESIGN STEPS:
### Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

### Step 2:
Run StegExpose on a directory of suspected image files using the command:

### Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

## PROGRAM:
StegExpose and File Signature Analysis Commands Step 1: Download Image and Create Secret Message File • Download a .jpeg image from a trusted website or use own image

<img width="539" height="521" alt="image" src="https://github.com/user-attachments/assets/243e082e-b4aa-41fa-91fe-4e56a1e261a4" />

 Create a text file named secret with a confidential message:

<img width="640" height="586" alt="image" src="https://github.com/user-attachments/assets/63da00ab-f161-483d-a3f7-6ba35ec5dba1" />

Step 2: Install and Verify Steghide Tool • To install Steghide on Kali linux,run:

• Confirm the installation by checking its version:

<img width="648" height="337" alt="image" src="https://github.com/user-attachments/assets/e02b5b21-f600-4be5-ac46-1102ee008f36" />

Step 3: Embed the Secret Message into the Image • Use the following command to embed secret into jaimurughan.jpeg:

<img width="843" height="687" alt="image" src="https://github.com/user-attachments/assets/bee793a1-c7bb-41f3-b684-8f317e2e6cf0" />

Step 4: Delete the Original Secret File • After embedding, delete the plaintext file:

<img width="586" height="656" alt="image" src="https://github.com/user-attachments/assets/9ab0870b-028b-4e81-9c98-30ee773eba08" />

## OUTPUT:
List of Images with Steganography Detection Scores and File Signature Details
Step 1: Extract the Embedded Secret from the Image
<img width="507" height="187" alt="image" src="https://github.com/user-attachments/assets/e6cb8f86-59cd-4be5-8230-d496e1b4f8e6" />

• To retrieve the hidden file: • Enter the same passphrase used during embedding.

Step 2: Verify the Extracted Message • Display the extracted file content to verify:

• Ensure the message matches the original secret content.

• Another command to see the same secret message is

Step 3: Retrieve Information About the Embedded Data

<img width="513" height="197" alt="image" src="https://github.com/user-attachments/assets/16631902-94a5-40cf-9e72-9d5ea4b939a3" />

• This will display file type, size, and whether data is embedded.
## RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
