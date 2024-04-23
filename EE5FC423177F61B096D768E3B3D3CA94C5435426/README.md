# HydePHP CLI Bravo RSA Key

| Fingerprint / Identifier                                           | Status | Scope           | Type               |
|--------------------------------------------------------------------|--------|-----------------|--------------------|
| `EE5FC423177F61B096D768E3B3D3CA94C5435426B51864558707C8B514DB0EC0` | Active | OpenSSL Signing | RSA 4096 / AES 256 |


## Details

```bash
# Identifier is made using the SHA256 sum of the armored public key file.
sha256sum  public_key.pem  EE5FC423177F61B096D768E3B3D3CA94C5435426B51864558707C8B514DB0EC0

# The fingerprint is the first 40 characters of the checksum.
sha256sum  public_key.pem | head -c 40  EE5FC423177F61B096D768E3B3D3CA94C5435426
```

## Scope

This key is used to sign binaries of the standalone HydePHP executable project in the 0.x series development range. See https://github.com/hydephp/cli/
