# HydePHP Certificates

Official HydePHP Certificates and Public Keys

## About

This repository is essentially a mirror of the https://trustservices.hydephp.com/certificates directory.

This repository is handled independently of the trust services platform, meaning that the two separate platforms would need to be compromised in order to spoof a key.

Additionally, all public keys are pushed to the following keyservers:
- [OpenPGP Keyserver](https://keys.openpgp.org/)
- [Ubuntu Keyserver](https://keyserver.ubuntu.com/)
- [MIT Keyserver](https://pgp.mit.edu/)

## Public Key Index

Public keys are provided in both formats in the GitHub repository, as well as in the trust services directory.

We use `.asc` for ascii armored GPG/PGP keys and `.sig` for binary formats. Both contain the same information.
For OpenSSL keys we use the `.pem` format.


| Label                                | Fingerprint                                | Expiration             | GitHub&nbsp;Directory                                             | Trust&nbsp;Services                                                                                                                                                                                              | Status | Scope   | Type    |
|--------------------------------------|--------------------------------------------|------------------------|-------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|---------|---------|
| HydePHP&nbsp;CLI&nbsp;Alpha&nbsp;GPG&nbsp;Key | `657B4D97184E9E6E596E6EA13B829782D5B7BA59` | 2026&#8209;04&#8209;20 | [GitHub&nbsp;Directory](657B4D97184E9E6E596E6EA13B829782D5B7BA59) | [`.asc`](https://trustservices.hydephp.com/certificates/657B4D97184E9E6E596E6EA13B829782D5B7BA59.asc)&nbsp;[`.sig`](https://trustservices.hydephp.com/certificates/657B4D97184E9E6E596E6EA13B829782D5B7BA59.sig) | Active | Signing | rsa3072 |
| HydePHP&nbsp;CLI&nbsp;Bravo&nbsp;RSA&nbsp;Key | `EE5FC423177F61B096D768E3B3D3CA94C5435426` | Never                  | [GitHub&nbsp;Directory](EE5FC423177F61B096D768E3B3D3CA94C5435426) | [`.pem`](https://trustservices.hydephp.com/certificates/EE5FC423177F61B096D768E3B3D3CA94C5435426.pem)                                                                                                            | Active | Signing | rsa4096 |
