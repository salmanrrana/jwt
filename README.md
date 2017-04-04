# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?
Header
Payload
Signature

2. What information does each part contain?

Header contains the token and the hashing algorithm being used
Payloads contains claims, Like reserved claims, public claims, and private claims.They also can hold additional metadata
Signatures contain the encoded headed, the encoded payload and an algorithm specified in the header

3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.

It is less verbose than an XML, so it is smaller and it hightlights the ease of client side processing on multiple platforms, especially mobile
