# Bash

## GPG

Import public key of someone

```bash
gpg --import some-one.key
```

See all imported public keys

```bash
gpg --list-keys
```

Encrypt a file

```bash
gpg --encrypt --armor -r some-one@server.com
```

## PDF

Count the words of a PDF file:

```bash
pdftotext myfile.pdf - | wc -w
```
