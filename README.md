# Red Carpet

Red Carpet is a WeChat mini-program for students in university to nominate and vote for people and groups to walk the red carpet in the university commencement.

## Hierachy

- backend: source code of backend system
- docs: documents
- frontend: the source code of management system designed for administrator

## Security

1. Use HTTPS to encrypt the access information
2. Use nginx to reverse proxy and hide the back end
3. The front-end source code has been escaped and cannot be read
4. The back-end uses JWT and cookie technology to maintain the session and ensure the security of administrator access rights and account passwords
5. Use log to record each database operation in detail
6. Back up the database every half an hour to ensure high availability of data
