ModSecurity in NGINX
====================

General
-------

In a previous project I used the ModSecurity as a module in NGINX.
The setup was running in a Docker and actually used as a reverse proxy to send the request to the backend.

ModSecurity is a very powerfull engine to protect your resources on the Internet. Since cloud based setup are more common now, the Module gain's in popularitty.
Since ModSecurity Version 3+ the tight link with apache is gone, allowing the combination of NGINX and ModSecurity for better performance.

The github repository `here <https://github.com/vdveldet/nginx-modsecurity>`_ contains the code to create the docker.
You can use the docker and add mount your own configuration if needed.
