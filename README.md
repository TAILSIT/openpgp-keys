# TAILSIT OpenPGP Public Keys

Official OpenPGP public certificates for TAILSIT software releases.

## Software signing key

**Identity:** TAILSIT Software Signing <software@tailsit.com>

**Primary fingerprint:**

`DFD5 ED95 92B8 B3AC 7A8D AC72 C5E5 8D4E CE25 ECA9`

**Public certificate:** [software-signing.asc](software-signing.asc)

### Import

```bash
gpg --import software-signing.asc
```

A valid signature confirms the integrity of the signed file relative
to the imported public key. Verify the primary fingerprint through an
independently trusted TAILSIT channel before relying on it.
