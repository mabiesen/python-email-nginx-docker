# python-email-nginx-docker
python + nginx + supervisor 


Build the project, then run with "sudo docker run -p 3000:80 -it image_name"

TODO:

1.  Proper queue for emails.  Current technique is fail silently, email site first with detail to insure detail is captured.  This is great but does not protect against failed email service.

2.  Proper logging.
