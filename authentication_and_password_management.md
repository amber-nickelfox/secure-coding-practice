### Authentication and Password Management

- [ ] Require authentication for all pages and resources, except those specifically intended to be public
- [ ] All authentication controls must be enforced on a trusted system (e.g., The server)
- [ ] Use a centralized implementation for all authentication controls
- [ ] Segregate authentication logic from the resource being requested and use redirection to and from the
centralized authentication control
- [ ] All authentication controls should fail securely
- [ ] Validate the authentication data only on completion of all data input
- [ ] Authentication failure responses should not indicate which part of the authentication data was
incorrect. For example, instead of "Invalid username" or "Invalid password", just use "Invalid
username and/or password" for both. Error responses must be truly identical in both display and
source code
- [ ] Use only HTTP POST requests to transmit authentication credentials
- [ ] Only send non-temporary passwords over an encrypted connection or as encrypted data, such as in an
encrypted email. Temporary passwords associated with email resets may be an exception
- [ ] Password entry should be obscured on the user's screen. (e.g., on web forms use the input type
"password")
- [ ] Enforce account disabling after an established number of invalid login attempts
- [ ] Password reset and changing operations require the same level of controls as account creation and
authentication.
- [ ] If using email based resets, only send email to a pre-registered address with a temporary
link/password
- [ ] Temporary passwords and links should have a short expiration time
- [ ] Enforce the changing of temporary passwords on the next use
- [ ] Notify users when a password reset occurs
- [ ] Disable "remember me" functionality for password fields
- [ ] Use multi factor Authentication (MFA) ex: Google Authenticator
- [ ] If using third party code for authentication, inspect the code carefully to ensure it is not affected by
any malicious code
- [ ] The last use (successful or unsuccessful) of a user account should be reported to the user at their next
successful login
