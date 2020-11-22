## How To

This how to is relating to the article <https://www.rinproduction/en/posts/004-r-web-server-with-docker/>. There you find reasons and instructions.

Is this useful? Leave a Star to the project!


### Security Notes

The code was written with the purpose of testing the possibility and ease of use of Docker Compose applied to our problem. In case you want to use it in production, depending on the situation, there may be other safety measures to be taken. Definitely **you must** regenerate the SSL key in the `config/ssl/` directory as the secret key is shared on a public repository (for the benefit of dissemination). Find out how to regenerate self-signed certificates [here](../003-web-r-platform-with-https/#enable-https).




