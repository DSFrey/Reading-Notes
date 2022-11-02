# `Login` and `Auth`

## [What is Role Based Access Control (RBAC)?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

1. RBAC restricts a user's access to a system based on their role rather than allowing/denying access on a user-by-user basis.

2. A user can CRUD their own account but not affect others. Someone in billing might be able to read all accounts but not change them (CUD) in any way. An admin would be able to CRUD all accounts.

3. It streamlines managing access to different systems, reducing the work required for for administrators and IT; this will generally lead to better security because it is harder for mistakes in access assignment to slip slip through the cracks.

## [react-cookie](https://www.npmjs.com/package/react-cookie) and [react-cookies](https://www.npmjs.com/package/react-cookies)

1. Contains hooks to load a specified cookie, all cookies, or any cookie that matchas a regular expression. Can also save and remove cookies with options such as the path you can access it from, an expiration date, or making it only accessible through https. You can also use a wrapper to allow your cookies to be accessed from any component.

2. Contains methods to load a specified cookie, all cookies, or any cookie that matchas a regular expression. Can also save and remove cookies with options such as the path you can access it from, an expiration date, or making it only accessible through https.

3. `react-cookie` would be my preference, as it works with functional components
