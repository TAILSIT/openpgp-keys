# TAILSIT OpenPGP Public Keys

Official OpenPGP public certificates for TAILSIT software releases.

## Software signing key

**Identity:** TAILSIT Software Signing <software@tailsit.com>

**Algorithm:** NIST P-384 (ECDSA)

**Primary key fingerprint:**

`DFD5 ED95 92B8 B3AC 7A8D AC72 C5E5 8D4E CE25 ECA9`

### Obtain the public certificate

The public certificate is available from:

- **GitHub:** [software-signing.asc](software-signing.asc)
- **OpenPGP keyserver:** [keys.openpgp.org](https://keys.openpgp.org/vks/v1/by-fingerprint/DFD5ED9592B8B3AC7A8DAC72C5E58D4ECE25ECA9)

To import the certificate from the downloaded file:

```bash
gpg --import software-signing.asc
```

Alternatively, retrieve it directly from the keyserver:

```bash
gpg --keyserver hkps://keys.openpgp.org \
    --recv-keys DFD5ED9592B8B3AC7A8DAC72C5E58D4ECE25ECA9
```

A valid signature confirms that the file was signed using the private key corresponding to the imported certificate and that the signed contents have not been modified.

**Important:** Always compare the full primary-key fingerprint against an independently trusted source, such as the official [TAILSIT website](https://www.tailsit.com/). A valid signature alone does not establish the signer's identity.
