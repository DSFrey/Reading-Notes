# Local Storage and How To Use It On Websites

1. HTTP cannot store information by itself; if you want a web app to remember its state, it either needs to be stored server-side with a login or with local storage. This can also be used to reduce the need for downloading through local caching.

2. Since local storage is not secure, storing sensitive personal information is a bad idea.

3. Local storage can only store strings, so the `JSON.stringify()` and `JSON.parse()` methods can be used to turn an object into a string and vide-versa.
