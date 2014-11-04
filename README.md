# Quick Start

1. Copy your SSL private key as p12 to a directory of your choice
2. Rename it to tomcat.p12
3. Encrypt your key with the password `changeit`
4. `docker run -v /path/to/certs:/certs -p 8000:8443 phylor/tomcat-ssl`

# Advanced 

- Edit `server.xml` to change location and password of your SSL private key
