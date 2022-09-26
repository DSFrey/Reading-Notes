# Authentication

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1. Hashing is a algorithm that changes your pattern into a different string of characters. Because the algorithm is not reversible, you can stored hashed passwords without giving away the actual plaintext passwords.

2. BCrypt is an adaptive algorithm that uses key stretching to increase security.

3. By adding computation time to the hashing algorithm it becomes more difficult to brute force a password, even if it is a weak password. Because it is an adaptive algorithm, it can be modified to increase this effect in response to computers getting faster.

## [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1. >Basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.

2. The authorization method (e.g. Basic) is followed by a space and then the username and password separated by a colon then encoded in Base64.

3. They are encoded in Base64

## [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

1. >Authentication is the process of verifying that an individual, entity or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.

2. Any error responses should be generic, not giving any information about whether the problem is an incorrect password, incorrect username, or a locked/disabled user account.

3. This link has been bookmarked.
