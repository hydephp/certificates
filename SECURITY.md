# HydePHP Certificate Security

If you are curious how we secure our certificates and private keys, here is a brief overview:

To ensure the security of our certificates and private keys, we implement a multi-layered approach:

- Our private key is safeguarded through several redundancy measures. This includes encrypted storage via GitHub Actions Secrets for cloud builds, alongside master copies and physical recovery keys stored in a vault in an undisclosed location.
- In the unlikely event of a compromise, the key can be revoked and replaced with a new key. The new key will be signed by the old key to ensure continuity of trust.
- Additionally, the public key is made available on several independent platforms, making it much more difficult for an attacker to spoof the key.

This comprehensive strategy reinforces our commitment to safeguarding the integrity and security of our cryptographic assets.

## Reporting Security Issues

If you discover a security vulnerability within HydePHP code or related service, please send an e-mail to the creator, Caen De Silva, via caen@desilva.se. All security vulnerabilities will be promptly addressed.
