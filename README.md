# Cryptography
All about cryptography and Crypto Algos and Providers

## SSH Key Generation on CentOS:

### Generation of public-private keyPair via ssh-keygen command: 
```sh
$ ssh-keygen -t rsa
```

- Command console Log:

```
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/1556025/.ssh/id_rsa): /c/study/Crypto/keygen/keypair
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/study/Crypto/keygen/keypair.
Your public key has been saved in /c/study/Crypto/keygen/keypair.pub.
The key fingerprint is:
SHA256:4CmtKkoA0Egwdbu1CHHiulKH8b7qG5QiEtXCVyVUk0Y TEST@SGZZF0NVJV6
The key's randomart image is:
+---[RSA 2048]----+
|**=.oo++E.       |
|o++=o. .o.       |
|o +o. o.         |
|.o * * +         |
|* = * = S        |
|+= o o           |
|o.. o            |
|+  o .           |
|oo=o.            |
+----[SHA256]-----+
```

### Output files:
- privateKey: keypair
- publicKey: keypair.pub

### Contents will be:
