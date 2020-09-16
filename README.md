# encryption-service
Generation of encrypted messages in NodeJs for sending user-password to an authentication endpoint in Spring Boot 

npm install
npm start

call the endpoint:
POST http://localhost:3000/encrypt


POST data:

	{"password": "mypassword",
	"username": "myuser",
	"key": "somekey=7hcNewuVXhqDNAMGYq3hbt3NYnKmw==FvpIOivTukSjxku7fMie"}
