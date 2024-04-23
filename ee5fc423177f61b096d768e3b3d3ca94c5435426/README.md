# HydePHP CLI Bravo RSA Key

| Fingerprint / Identifier                                           | Status | Scope           | Type               |
|--------------------------------------------------------------------|--------|-----------------|--------------------|
| `ee5fc423177f61b096d768e3b3d3ca94c5435426b51864558707c8b514db0ec0` | Active | OpenSSL Signing | RSA 4096 / AES 256 |


## Details

```bash
# Identifier is made using the SHA256 sum of the armored public key file.
sha256sum  public_key.pem  ee5fc423177f61b096d768e3b3d3ca94c5435426b51864558707c8b514db0ec0

# The fingerprint is the first 40 characters of the checksum.
sha256sum  public_key.pem | head -c 40  ee5fc423177f61b096d768e3b3d3ca94c5435426
```

## Scope

This key is used to sign binaries of the standalone HydePHP executable project in the 0.x series development range. See https://github.com/hydephp/cli/
