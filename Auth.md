# Web Auth
- client -> username & password -> server
- server -> check username & password
- server -> session -> user data

- client -> server (auth content)
- server -> check session
- server -> respond (auth content)

# Api Auth
- client -> username & password -> server
- server -> check username & password
- server -> respond (access token)

- client -> access token -> server (auth content)
- server -> check token
- server -> respond (auth content)