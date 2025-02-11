Currying in Javascript:

Currying in JavaScript is a technique where a function doesn’t take all its arguments at once. Instead, it takes one argument and returns another function that takes the next argument, and so on, until all arguments are provided.


Stateless Behaviour of Spotify:

Spotify’s backend services are stateless. This means each request from the app to the server is independent, and no user-specific information is stored between requests. Spotify uses tokens (like access tokens) to identify and authenticate users with each request.

When you log in and give Spotify permission to access your data, it generates an access token. This token allows Spotify to interact with your account (e.g., retrieve playlists) without storing your password.
Example: When you connect Spotify to another app (like Discord), you grant permission (authorization) to access certain data.

Authentication is the process of verifying your identity. Spotify lets you log in via email/password, Facebook, Google, or Apple. Once authenticated, Spotify generates a token, proving that you are the user you're claiming to be.
Example: When you log in to your Spotify account, it confirms your identity (authentication).