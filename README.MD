## Tor proxy server with docker 

Based on 

https://www.arulraj.net/2015/05/docker-container-for-tor-with-privoxy.html

# Install

Clone files at your directory

Run

```
docker-compose up -d
```

Go to your browser newtork settings and add at "Socks Host"
```
yourip:9050
```

and check SOCKS v5

This is for Firefox. Maybe another browser have different options

For more information go to:

https://www.arulraj.net/2015/05/docker-container-for-tor-with-privoxy.html

Edit tor/torrc file to change tor settings
