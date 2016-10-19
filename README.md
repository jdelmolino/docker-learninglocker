# docker-learninglocker

Learning Locker image with Supervisor.
These services are automatically executed:
* apache2
* mongod
* sshd (optional)

The built follows the steps described in http://docs.learninglocker.net/installation/:
* It neither changes the encryption key nor configures the email in step "Configuration" (http://docs.learninglocker.net/installation/#configuration).
* It does not include the last step "Register yout first user" (http://docs.learninglocker.net/installation/#register-your-first-user).
