# profquoc.github.io

This repository serves https://profquoc.github.io/, a password-protected page.

`index.html` holds only an encrypted page (AES-256-GCM, key derived from the password with PBKDF2-SHA256,
600,000 iterations) and a password form; the browser decrypts it once the password is entered.
