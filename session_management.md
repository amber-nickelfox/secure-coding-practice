# Session Management


- [ ] Use the server or framework’s session management controls. The application should only recognize
these session identifiers as valid
- [ ] Session identifier creation must always be done on a trusted system (e.g., The server)
- [ ] Logout functionality should fully terminate the associated session or connection
- [ ] Logout functionality should be available from all pages protected by authorization
- [ ] Establish a session inactivity timeout that is as short as possible, based on balancing risk and business
functional requirements. In most cases it should be no more than several hours
- [ ] If a session was established before login, close that session and establish a new session after a
successful login
- [ ] Protect server side session data from unauthorized access, by other users of the server, by
implementing appropriate access controls on the server
- [ ] Set cookies with the HttpOnly attribute, unless you specifically require client-side scripts within your
application to read or set a cookie's value
