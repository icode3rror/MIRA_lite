# Mira Password Manager (Lite)

Mira is our innovative password management solution designed specifically for the command-line interface (CLI). With a streamlined and efficient approach, Mira provides a robust solution to the vulnerabilities associated with password management in the digital era. 
                                                                                     
## Objectives

- **Offline Security**: Mira prioritizes offline functionality to ensure password management without dependence on internet connectivity. This approach enhances security by minimizing the attack surface and reducing exposure to online threats.                     
- **Local Storage**: The password manager facilitates secure storage and retrieval of passwords locally on the user's machine, ensuring data confidentiality and reducing reliance on external servers or cloud services.

- **No Cloud Dependencies**: Mira does not rely on external servers or cloud services for enhanced privacy and control. This approach eliminates the risk of unauthorized access or data breaches associated with online storage.

- **Data Confidentiality**: To ensure the privacy of user data, Mira implements encryption and secure storage procedures, employing Argon2 for hashing the user data. This ensures that even if the device is compromised, the stored passwords remain unreadable without the decryption key.

- **Isolated Environment**: Mira operates within the user's system, minimizing exposure to external threats or vulnerabilities. This isolated environment enhances security by reducing the likelihood of unauthorized access or data breaches.

- **Usability**: Mira provides a user-friendly command-line interface for easy interaction, allowing users to efficiently manage their passwords without the need for complex technical knowledge.

- **Security Best Practices**: The password manager encourages secure practices such as safeguarding master keys, enabling Two-Factor Authentication (2FA), and emphasizing password complexity to enhance overall security.

- **Control**: Mira empowers users with complete control over their password manager, as it operates locally within the system and functions entirely offline. This provides users with a sense of independence and control over their sensitive information.

## Why MIRA is Considered Secure?

- **Limited Attack Surface**: Operating offline reduces the potential attack surface, minimizing vulnerabilities and enhancing overall security.

- **No Cloud Dependency**: Mira does not store user data in the cloud, reducing the risk of unauthorized access or data breaches associated with online storage. Users have direct control over their data, enhancing privacy and security.

- **Lower Exposure to Online Threats**: Due to its offline nature, Mira is less susceptible to phishing attacks or server breaches common with online password managers. Offline managers are not reliant on online authentication, reducing exposure to online threats.

- **Local Encryption**: Mira employs strong encryption algorithms to protect user data. Data is stored locally, and encryption ensures that even if the device is compromised, the stored passwords remain encrypted and unreadable without the decryption key.

- **Zero-Knowledge Architecture**: Mira ensures the privacy of user data by handling passwords without actually knowing what they are. It encrypts and decrypts data locally, ensuring sensitive information stays private, even from the password manager itself.

- **User Independence**: Users have full control over their password manager since it operates within their system. There's no reliance on external services, providing a sense of independence and reducing potential points of failure.

- **No Password Retrieval Over Network**: Password retrieval and storage occur locally, eliminating the need to transmit sensitive information over the network. This reduces the chances of interception or man-in-the-middle attacks.

- **Offline Password Generation**: Mira can generate passwords without requiring an internet connection, offering convenience and security, especially in situations where online access is limited.

- **No Third-Party Involvement**: Mira operates autonomously without any reliance on external service providers, ensuring enhanced security by eliminating potential risks associated with third-party entities. Users can fully trust the locally implemented security measures without involving external platforms.

- **Increased Privacy Control**: Users benefit from enhanced privacy control as their sensitive data remains within their own environment. There is no need to trust external servers with personal information, contributing to a more private and secure user experience.

- **No Connection Latency**: Users experience minimal latency since their password data is instantly accessible locally. This absence of network communication reduces the risk of delays or disruptions that might be exploited by attackers attempting to compromise the system.

*While offline password managers provide significant security benefits, users should remain vigilant about security best practices. It's crucial to store the master key and decryption key in a secure location on their device. Unfortunately, human error often poses the primary challenge in adhering to these practices.*

## MIRA's Credential Storage Capabilities

Mira supports various types of credentials, including:

- **Account Passwords**: For websites, applications, and services.
- **Credit/Debit Card PINs**: Secure storage for financial information. (PREMIUM)
- **API Keys**: Authentication credentials for accessing web services or APIs. (PREMIUM)
- **SSH Keys**: Secure Shell keys for remote access to servers and systems. (PREMIUM)

## Features

- **Secure Storage**: Passwords are encrypted using the Fernet symmetric encryption algorithm, ensuring data confidentiality and integrity.
- **Master Password**: Users can protect their password vault with a master password, adding an additional layer of security.

## Installation (PIP)
```bash
sudo pip3 install MIRA-passwdmng
```

## Usage

To use Mira effectively:

- Run the program with elevated privileges using `sudo mira`.
- Typing `h` or `help` in the Mira prompt provides guidance.
- Before logging in, create a master user to secure the password vault.

## Commands

Once logged in, users can utilize various commands, including (FOR LITE ONLY):

- **add_platform_passwd** - Add a new password for the desired account ID
- **get_platform_passwd** - Display the plaintext version of the password for the desired account ID
- **del_platform_passwd** - Delete a saved password according to your desired account ID
- **ch_platform_pass** - Change the password for the desired account ID
- **list_passwd** - List all the stored credentials on your vault
- **lout** - Logout
- **exit** - Terminate MIRA
## Security Recommendations

To enhance security:

- Keep master and encryption keys secure to prevent unauthorized access.
- Use complex passwords to safeguard against brute-force attacks and unauthorized access attempts.

## Go Premium for Lifetime Access
Unlock a world of possibilities with our Premium membership:
- **Debit/Credit Card PINs are supported**
- **API Keys are supported**
- **SSH(RSA) Keys are supported**
- **No storage limit for Passwords/PINs/SSH(RSA) Keys/API Keys**
- **2-Factor Authentication**
- **User can change the Master Password anytime**
- **Password Generator**
- **Password Strength Checker**
- **Password/PIN Expiry Checker**
- **Password/PIN Expiry Alerts**
- **Account Lockout**
- **Mnemonic Option for encryption key**
- **Reset Option**

*Upgrade today for lifetime access and experience the robustness of GiraSec's MIRA for only $5 (250 PHP)!*

## License

- Mira is licensed under the EULA License.

## For Premium Access, Concerns, and Issues please email us here:
- girasesolutions@gmail.com
- fredmarkivand@gmail.com
- johnrussel205@gmail.com

## Acknowledgements

- GiraSec Solutions
- veilwr4ith
- icode3rror