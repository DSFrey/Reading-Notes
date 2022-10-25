# Bearer Authorization

## [Intro to JWT](https://jwt.io/introduction/)

1. >JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

2. JWTs are useful for both authorization (due to its low overhead) and information exchange (due to the fact that it is calculated using the header and payload, so it would give evidence of any tampering).

3. Claims are found in the payload

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

1. The signature is calculated by hashing the payload and the secret together; if you do not have the secret, you cannot get the same hash.

2. Both sender and receiver need the hash.

3. When a message is sent, a hash is calculated using the content of the message and a secret that only the sender and receiver know. When the message is received, the content and secret are again put through the calculations to see if the result is the same. The only way for it to be the same is if both the content and the secret match.

## [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

1. JWT is a good option because it verifies the transfer of data and it is an open standard, so anyone can use it.

2. Compact means that it is small and thus quick to transfer. Self-contained means that the token itself contains the user information, so there do not need to be additional database queries.

3. A JWT signature consists of the header, payload, and secret put the a hashing algorithm.
