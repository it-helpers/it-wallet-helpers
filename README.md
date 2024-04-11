# EUDI Wallet Technical Specifications

 [https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/)

---

##
## Table of Contents

#### Eid Provider
- [eID Credential](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html)
    - [eId Model](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-data-model.html#id1)
    - [Access Token](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#access-token)

    #### Authorization Server Par Endpoint (/as/par)
    - [Par Request](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#pushed-authorization-request-par-request)
    - [WTE](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/wallet-attestation.html#id1)
    - [Entity Configuration](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/trust.html#entity-configuration)
    - [Par Response](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#pushed-authorization-request-par-response)


    #### Authorization Server Authorization Endpoint (/authorize)
    - [Authorization Request](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#authorization-request)
    - [Authorization Response](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#authorization-response)
    - [DPoP](https://datatracker.ietf.org/doc/html/rfc9449)
    - [DPoP Proof JWT - DPoP-bound Access Token](https://datatracker.ietf.org/doc/html/rfc9449#name-dpop-proof-jwts)

    #### Authorization Server Token Endpoint (/token)
    - [Token Request](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#token-request)
    - [Token Response](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#token-response)


    #### Credential Issuer Credential Endpoint (/credential)
    - [credenziale eID](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-data-model.html#id1)
    - [Credential Request - Openid4vci proof JWT ](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#credential-request)
    - [Credential Response](https://italia.github.io/eudi-wallet-it-docs/v0.6.0/en/pid-eaa-issuance.html#credential-response)