# Authentication

## What is OAuth

1. >OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

2. You log in to your google account, then on another website, you log in with your google account.

3. Website 1 connects to website 2 providing the user's verified identity. The website 2 passes a one-time request token and secret to website 1 who passes it to the client. The client is asked to approve the authorization to website 2 then to website 1. Website 2 gives the client an approved access token, which is then passed to website 1 who passes it back to website 2 as proof.

4. OpenID is for authentication; originally stand-alone, but realeased as an suthentication layer for OAuth in 2014.

## Authorization and Authentication flows

1. Authentication is making sure you are who you say you are. Authorization is making sure you are allowed to access what you are trying access.

2. The process by which an authorization code is exchanged for an access token.

3. Similar to above but used when the app cannot securely store the client secret.

4. A simplified flow for when you don't need access tokens for APIs

5. Used when authenticating and authorizing an app instead of a user.

6. Authorizes the user on another device when the first device does not have an appropriate input.

7. Requests the username and password; must be completely trustworthy, as you are giving it sensitive information. Not the most secure flow.
