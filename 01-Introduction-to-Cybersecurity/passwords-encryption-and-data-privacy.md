# Password Security, Encryption and Data Privacy

## 1. Password Security

Passwords help prevent unauthorized access to accounts, devices, and information.

### Password Best Practices

- Use a unique password for every account.
- Avoid common passwords, names, dictionary words, and easily guessed information.
- Use long passwords or passphrases.
- Never share passwords with others.
- Use a password manager to securely store passwords.
- Enable Multi-Factor Authentication (MFA) whenever available.

### Strong Passwords and Passphrases

**Strong Password:** A password that is difficult to guess or crack.

**Passphrase:** A longer sequence of words or a sentence used as an authentication secret.

Best practices:
- Prefer long, unique passwords or passphrases.
- Avoid predictable patterns and personal information.
- Do not reuse passwords across accounts.
- Follow the password requirements of the service.

### Password Reuse

Using the same password on multiple accounts increases risk. If one account is compromised, attackers may try the same credentials on other services.

### Password Manager

A password manager stores passwords securely, usually in an encrypted vault.

**Key Takeaway:** Use unique passwords and MFA to strengthen account security.

---

## 2. NIST Password Guidelines

NIST publishes digital identity guidelines that inform secure password practices.

Important principles include:

- Require sufficient password length.
- Block commonly used and compromised passwords.
- Avoid arbitrary composition rules, such as always requiring a specific combination of uppercase letters, numbers, and symbols.
- Support a broad range of characters and spaces.
- Avoid mandatory periodic password changes unless there is evidence of compromise or another reason to change them.
- Do not rely on knowledge-based security questions as a secure authentication method.

Exact requirements may vary according to the applicable NIST guidance and service implementation.

**Key Takeaway:** Password length, uniqueness, and resistance to guessing are more useful than relying only on complex-looking character combinations.

---

## 3. Encryption and Decryption

### Encryption

**Definition:** Encryption transforms readable data (plaintext) into an unreadable form (ciphertext) using a cryptographic process.

**Purpose:** Protect information from unauthorized access.

### Decryption

**Definition:** Decryption converts ciphertext back into readable information using the required cryptographic key.

### Important Points

- Encryption protects the confidentiality of data.
- The appropriate key is required to decrypt protected data.
- Encryption does not prevent someone from intercepting data; it helps prevent unauthorized parties from reading it.
- Secure key management is essential.

### Ransomware

**Ransomware** is malware that can encrypt or otherwise deny access to data and demand payment for restoring access.

**Protection:** Keep software updated, maintain backups, and avoid suspicious links and attachments.

---

## 4. Windows Encrypting File System (EFS)

**EFS (Encrypting File System):** A Windows feature that encrypts files and folders on supported NTFS volumes.

Important points:
- EFS encryption is associated with the user's encryption credentials.
- Access to recovery credentials or certificates may be necessary to recover encrypted files.
- Back up important files and the required recovery information securely.

**Key Takeaway:** Encryption helps protect stored data, but losing the necessary keys or recovery information can make data inaccessible.

---

## 5. Data Backup and Recovery

**Backup:** An additional copy of data stored separately so it can be recovered after data loss.

### Backup Options

- **External Storage:** External HDDs, USB drives, and other storage media.
- **Network Storage:** NAS devices or other network-based storage.
- **Cloud Storage:** Online storage accessible through an account.

### Best Practices

- Back up important data regularly.
- Keep backups separate from the primary device.
- Protect backups with strong access controls and encryption where appropriate.
- Test recovery procedures periodically.
- Maintain an offline or otherwise isolated backup to help protect against ransomware.

**Key Takeaway:** A backup is useful only if the data can be restored when needed.

---

## 6. Secure Data Deletion

Deleting a file normally does not guarantee that its contents are permanently unrecoverable.

### Important Points

- Deleted data may remain recoverable depending on the storage medium and deletion method.
- Secure deletion methods depend on the device and storage technology.
- Overwriting may be appropriate for some storage devices, but it is not equally effective for every type of media.
- Use trusted sanitization methods appropriate for the storage device.
- Physical destruction may be used when a storage device must be permanently disposed of and other sanitization methods are unsuitable.

Examples of tools include Microsoft's SDelete and the `shred` utility on Linux. Their effectiveness depends on the storage medium and configuration.

**Key Takeaway:** Choose a secure data-sanitization method appropriate for the storage device.

---

## 7. Terms of Service and Data Privacy

### Terms of Service (ToS)

The Terms of Service describe the rules and conditions governing the use of an online service.

Before accepting, understand:
- How the service may use your content.
- What rights you grant to the provider.
- How your account and data are handled.
- What happens when you close your account.

### Data Use Policy

Explains how a provider collects, uses, processes, and shares user data.

### Privacy Settings

Control what information is visible to others and how certain account information is shared.

### Before Signing Up

- Read the Terms of Service and Privacy Policy.
- Understand how your data may be used.
- Check whether you can obtain a copy of your data.
- Review privacy settings.
- Understand what happens to your data after account closure.

### Protect Your Personal Data

- Share information only with the intended audience.
- Avoid publishing unnecessary sensitive personal information.
- Review application permissions and privacy settings.
- Use strong passwords and MFA.
- Never share another person's private information without permission.

**Key Takeaway:** Understand the service's data practices before sharing personal information.

---

## 8. Multi-Factor Authentication (MFA)

**Definition:** MFA requires two or more different types of authentication factors to verify a user's identity.

### Common Authentication Factors

- **Something You Know:** Password or PIN.
- **Something You Have:** Security key or registered device.
- **Something You Are:** Fingerprint or facial recognition.

### Two-Factor Authentication (2FA)

2FA is a form of MFA that requires two different authentication factors.

Examples include:
- Password plus a security key.
- Password plus an authenticator-generated code.
- Password plus a verification code sent through a supported channel.

### Limitations

MFA improves account security but does not eliminate every risk. Phishing, malware, and compromised recovery methods can still threaten accounts.

**Best Practice:** Prefer phishing-resistant authentication, such as passkeys or security keys, when available.

---

## 9. OAuth

**OAuth 2.0:** An authorization framework that allows an application to obtain limited access to resources without receiving the user's password for the external service.

Example:
A user authorizes a third-party application to access specific information from an existing account.

### Important Points

- OAuth is primarily an authorization framework.
- The third-party application does not need to receive the user's account password.
- Access can be limited by permissions and scopes.
- Review requested permissions before granting access.
- Revoke access to applications that are no longer needed.

**Important Distinction:** OpenID Connect builds on OAuth 2.0 to provide an identity layer for authentication.

---

## 10. Quick Revision

- **Password Manager:** Securely stores passwords.
- **Passphrase:** A longer sequence of words used as an authentication secret.
- **Encryption:** Converts plaintext into ciphertext.
- **Decryption:** Converts ciphertext back into readable data.
- **EFS:** A Windows feature for encrypting supported files and folders.
- **Backup:** An additional copy of data for recovery.
- **Terms of Service:** Rules governing the use of a service.
- **Privacy Settings:** Controls for managing information visibility and sharing.
- **MFA:** Uses multiple authentication factors.
- **2FA:** Uses two different authentication factors.
- **OAuth 2.0:** An authorization framework for delegated access.
- **OpenID Connect:** Adds an authentication and identity layer to OAuth 2.0.

## Cybersecurity Relevance

Password security, encryption, backups, secure deletion, privacy controls, and strong authentication help protect accounts, devices, and sensitive information.
