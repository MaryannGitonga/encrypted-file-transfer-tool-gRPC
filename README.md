# Encrypted File Transfer Tool using gRPC
A file transfer tool using gRPC

## Architecture
As shown in the architecture below, the gRPC client encrypts the file metadata and the contents of the file, and sends them as a request to the gRPC server. The gRPC server 
decrypts the metadata and the contents of the file before writing them to a new file (symbolizing the transfer).

![image](https://github.com/MaryannGitonga/encrypted-file-transfer-tool-gRPC/assets/34104277/b8632526-ff9e-4b62-a2da-d1f17e0ea05c)
