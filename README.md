## TLS-Certificates-with-Subject-Alternative-Name
## Generate TLS certificates with openssl command containing the Subject Alternative Name and signed by existing CA authority

## The CA certificate and key file must be present.
`[root@ayush certs]# ls
ca.crt  ca.key`

## Genereate a new private key.
`[root@ayush certs]# openssl genrsa -out server.key 2048
Generating RSA private key, 2048 bit long modulus
...+++
...........................................................+++
e is 65537 (0x10001)`
