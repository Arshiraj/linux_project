Secure File Transfer Setup in Linux
 Overview:-

This project shows how to transfer files securely between Linux systems using SCP, SFTP, and FTPS.
It protects data using SSH and SSL/TLS encryption.

 Objectives:-

Set up secure file transfer in Linux.

Use SCP, SFTP, and FTPS for encrypted file sharing.

Generate SSL certificates for security.

Configure firewall for safe communication.

 Requirements:-

Software: Linux OS, OpenSSH, vsftpd, OpenSSL, UFW
Hardware: 1 GB RAM, 2 GB free space

🛠️ Commands Used
Command	Description
sudo apt install openssh-server	Install SSH server
scp file.txt user@IP:/path/	Secure file copy
sftp user@IP	Secure file transfer
sudo apt install vsftpd	Install FTP server
openssl req -x509	Create SSL certificate
ufw allow 21, ufw allow 22	Allow firewall ports

 Steps:-

Install and start OpenSSH server.

Use SCP and SFTP for file transfer.

Install vsftpd and enable SSL for FTPS.

Generate SSL certificates using OpenSSL.

Allow ports 21 and 22 in firewall.

Test secure transfer between systems.

 Result:-

Secure file transfer works successfully using encryption.
Data remains safe and protected during transmission.
