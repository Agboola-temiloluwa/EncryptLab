# EncryptLab
Educational encryption repository demonstrating AES &amp; RSA encryption, key generation, and integrity verification with OpenSSL.
This project started from a conversation between two friends exploring how to protect business ideas and cutomer transactions. The goal is to demostrate how data privacy and security can be implemented through encryption and decryption techniques.

## Background Story 
I was chilling outside when i saw kemi rushing toward me with that "guess what just happened" face. Before i could speak, she dropped her bag and said, "Temi, I think I just found the craziezt business idea ever." She explained how someone at the store struggled to send money for a simple payment, and she thought, why not build a platform that makes small transactions easier and faster? We spent the evening discussing it like a secret mission.

## WHY This Repo Exists
This repo documents my learning journey from the idea stage to implementing encryption and decryption for privacy and data protection.
## Coming Next : Encryption and Decryption Walkthrough
- Encrypting sensitive data
- Decrypting safely
- Veryfing data integrity.

In this documentation, we simulate a scenario where two friends, Temi and kemi are discussing a business idea involving a transaction platform. To secure the conversation, we will demonstrate how to encrypt and decrypt sensitive messages in kali Linux.

## Tools used 
1. Kali LInux
2. OpenSSL

## Step 1
Open your terminal to create a file by inputing the command "touch" and any file name and using "nano" for the contents of the file 
<img width="291" height="91" alt="create file" src="https://github.com/user-attachments/assets/37974b38-1e9d-47f2-9524-cf45d0f77ea6" />
You list and then run commands by creating a private key and extracting a public key from the private key
<img width="1365" height="338" alt="bash" src="https://github.com/user-attachments/assets/6c311865-ce48-43f6-a2f3-b36d61c2c0ac" />
<img width="555" height="124" alt="public key" src="https://github.com/user-attachments/assets/61a3ac74-178d-41ed-aac6-74ccdb97bc3f" />

## Step 2 Encrypting the file using the public key
I had to run the following commands whih led me to encrypting the content of the file
<img width="1290" height="149" alt="correct encryption" src="https://github.com/user-attachments/assets/3c971862-fe5e-47b8-871f-784850199fc1" />

## Step 3 Decrypting the file using the private key 
I had to change the encrypt to decrypt command and then tried cheking the content 
<img width="1087" height="173" alt="correct decrypted" src="https://github.com/user-attachments/assets/9eaeb370-cafb-4024-8c6e-096633b61363" />

##  Conclusion
This project demonstrates how sensitive business ideas can be protected through encryption. In this simulation, Temi and kemi shared confidential plans for a transaction platform, and encryption ensued that even the file was intercepted, its content remained unreadable. By encrypting and decrypting the message securely, I reinforced my understanding of hybrid encryption and the importance of data confidentiality in cybersecurity.
