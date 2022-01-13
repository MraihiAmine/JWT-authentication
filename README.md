# JWT-authentication
A helloWorld project for jwt authentication
JSON Web Token (JWT) is an open standard (RFC 7519) for securely transmitting information between parties as JSON object.
It is compact, readable and digitally signed using a private key/ or a public key pair by the Identity Provider(IdP). So the integrity and authenticity of the token can be verified by other parties involved.
The purpose of using JWT is not to hide data but to ensure the authenticity of the data. JWT is signed and encoded, not encrypted.
JWT is a token based stateless authentication mechanism. Since it is a client-side based stateless session, server doesn’t have to completely rely on a datastore(database) to save session information.
The big advantage of JWT (Token-based Authentication) is that we store the Token on Client side: Local Storage for Browser, Keychain for IOS and SharedPreferences for Android
Backend jwt data flow 👇
![1 backend jwt](https://user-images.githubusercontent.com/81873005/149291469-26811ea6-04db-4c4c-827b-9dede9f68d60.png)

