# Changelog since v5.1.7
- Merge pull request #176 from dfigus/proxy-pass-ipv4-address

Use IPv4 Address in NGINX proxy pass 
- Use IPv4 Address in NGINX proxy pass
Avoid that localhost is resolved to IPv6 adress in NGINX proxy pass
by using 127.0.0.1 instead of localhost. This should solve the errors
connect() failed (111: Connection refused) while connecting to upstream
as TVHeadend is not listening on IPv6. 
