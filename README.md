User logs in → Server gives Access Token and Refresh Token.
2. Access Token is used for all API requests.
3. Access Token expires after a short time (e.g., 15 mins).
4. When it expires, the client sends the Refresh Token to the server.
5. Server checks the Refresh Token → if valid, gives a new Access Token.
6. Client uses the new Access Token to continue working.
7. When the Refresh Token also expires, the user must log in again.
8. On logout, both tokens are deleted.
