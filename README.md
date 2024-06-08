# file-handling-MASM
File Handling by MASM x86 based Architecture

# Description:
This assembly code is designed to perform file handling and string comparison tasks using x86 assembly language. The main routine, main PROC, opens a file named "hello.txt", checks if the file is valid, and proceeds to read its contents if it is. The code includes a mechanism for identifying the file type based on its extension, which currently distinguishes between text and PDF files. If the file fails to open, an error message is displayed. The txt_file_identity and pdf_file_identity procedures are used to print messages indicating the type of the file, though the PDF identification part is not fully integrated.

The code also includes a string comparison functionality. The compareStrings procedure compares two strings character by character, returning zero if they are equal and one if they are not. This is demonstrated in the second part of the code, which compares two predefined strings, "hello" and "world". Depending on the result of the comparison, an appropriate message is displayed. Additionally, the GetFileExtension procedure is provided to extract the file extension from a filename, which aids in determining the file type. This comprehensive approach to file handling and string operations showcases the versatility of assembly language in performing low-level system tasks efficiently.


# File Opening and Error Handling

![image](https://github.com/A1iw4r3/file-handling-MASM/assets/124252109/c5b8f986-06e5-48bd-84d0-4d5cd5b94555)


# File Processing

![image](https://github.com/A1iw4r3/file-handling-MASM/assets/124252109/be2daf2a-338b-43f0-98be-c3c4a6761cd9)


![image](https://github.com/A1iw4r3/file-handling-MASM/assets/124252109/c1085620-30d9-43a4-b201-065e1d6eed00)


# Handling Different File Format

![image](https://github.com/A1iw4r3/file-handling-MASM/assets/124252109/1d8096f9-158f-480f-bd62-63f47fc0f49e)


![image](https://github.com/A1iw4r3/file-handling-MASM/assets/124252109/416d4aee-d42b-465a-8260-a191476cc341)

