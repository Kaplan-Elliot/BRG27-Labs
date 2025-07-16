# Building my server

## Acquring DNS and SSL Certificate

### Setting up a DNS

To ensure that my server can be accessed other than through its IP address, I had to get a DNS for it. I used Cloudflare as the provider.

1. <img width="1117" height="1035" alt="using cloud flare" src="https://github.com/user-attachments/assets/3c2aa711-21ff-4a56-94c5-a78593e8e2c0" />

2. <img width="1751" height="823" alt="setting up a DNS" src="https://github.com/user-attachments/assets/3beb36ac-b995-46a5-8a5b-8c98dac84078" />

3. <img width="921" height="558" alt="dns worked" src="https://github.com/user-attachments/assets/2aa5f845-e196-4abb-9ed1-6e30ca784d35" />

The DNS was configured so that if i typed in my websites name into the search bar, I would be able to access it.

1. <img width="1837" height="584" alt="dns made" src="https://github.com/user-attachments/assets/b1acc7c6-660b-4f15-95ec-86aea6ce4672" />

### Setting up the SSL Certificate

For my server to be secure, I had to ensure that access to it was encrypted. Using CertBot and a SSL guide, the set up for encryption was done.

1. <img width="1073" height="751" alt="install snapd n certbot" src="https://github.com/user-attachments/assets/6245ed4c-5be1-4072-a2db-2396f1f5edd0" />

### Encryption enabled

1. <img width="1509" height="460" alt="sometypeofweb with HTTPS" src="https://github.com/user-attachments/assets/b2dace06-27f5-4ba6-9903-a3afa9bfb8bc" />


### SSL guide for cloud flare
1. https://scriptstown.com/how-to-setup-cloudflare-ssl-and-configure-origin-certificate-for-apache/
