# postman-jwt
This collection contains a request with an example of how to create a JSON web token using the Postman Sandbox.

How to use it:
1. Add the header of the jwt to the `header` variable in the `Pre-request Script` section.
2. Add the payload of the jwt to the `payload` variable in the `Pre-request Script` section.
3. Create an environment variable called `secret` and add there the value of the jwt secret.
4. Create an environment variable called `expectedToken` and add there the value of a token built in the debugger from `https://jwt.io/` with exactly the same data you used in this request.
5. Send the request.
6. Check all tests from the `Tests` section passed.
