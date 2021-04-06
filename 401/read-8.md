# Access Control (ACL)

## When is Basic Authorization used vs. Bearer Authorization?

Since OAuth 2.0 was developed in the time of a growing API market, most of the use cases for API keys and Basic Authentication have already been considered within the protocol. It’s safe to say that it beats the competition on all accounts. For small, specific use cases, it might be ok to use API keys or Basic Authentication, but anyone building systems that plan to grow should be looking into a token-based architecture such as the Neo Security Architecture.

## What does the JSON Web Token package do?

JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

## What considerations should we make when creating and storing a SECRET?

Never store unencrypted secrets in .git repositories

Don’t share your secrets unencrypted in messaging systems like slack
Store secrets safely

Restrict API access and permissions

## Term

*Encryption* is the method by which information is converted into secret code that hides the information's true meaning.

*Token* is a peripheral device used to gain access to an electronically restricted resource.

*Bearer* Token is an opaque string, not intended to have any meaning to clients using it.

*Secret* key is the piece of information or parameter that is used to encrypt and decrypt messages in a symmetric, or secret-key, encryption.

*JSON Web Token* (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

