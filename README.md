# pswhatevdevmustknowhttps
## 6. Beyond the Basics
### 2 TLS and HTTPS Acronyms
SNI
- Server Name Indication
- Enables multiple certs on the one IP address

SAN
- Subject Alternative Name
- Combine multiple domain names on the one cert

PFS
- Perfect Forward Secrecy
- Protects past session sagainst future key compromise

DANE
- DNS Based Authentication of Named Entities
- Specifies the cert keys at the DNS level

CAA
- Certificate Authority Authorization
- Specifies allowable CAs for the domain at the DNS level

CRL
- certificate Revocation List
- list of revoked certificates maintained by the CA

PKP
- Public Key Pinning
- Ensure a client will only accept predefined certs
