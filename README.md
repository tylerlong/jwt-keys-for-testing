# JWT keys for testing

This repository provides you with two key pairs for JWT testing purpose.
The two key pairs include both public key and private key.
It also provide hosting of public keys.


## Disclaimer

Please do NOT use the key pairs here for production!
Because both public key and private keys are available here. 
Everybody can encrypt/decrypt message with them.

For your production system, you need to generate your own key pairs and keep your secret keys secret.


## How to use the keys

Download `keys.json` file and use keys inside to encrypt/decrypt message.

If you need a public JWKS server, use https://chuntaoliu.com/jwt-keys-for-testing/jwks.json
