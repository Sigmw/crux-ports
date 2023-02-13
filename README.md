# Sigma crux-ports

To download the repository (httpup or git):

```
curl -o /etc/ports/sigma.httpup  https://raw.githubusercontent.com/Sigmw/crux-ports/main/sigma.httpup
```
Or git:

```
curl -o /etc/ports/sigma.git https://raw.githubusercontent.com/sigmw/crux-ports/main/sigma.git
```


Be sure to let `prt-get` know of the repository's existence, add in your `/etc/prt-get.conf`:

```
prtdir /usr/ports/sigma
```

Fetch the port collection:

```
ports -u sigma
```
