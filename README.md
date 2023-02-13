# Sigma crux-ports

To download the repository:

```
curl https://raw.githubusercontent.com/Sigmw/crux-ports/main/sigma.httpup
```

Be sure to let `prt-get` know of the repository's existence, add in your `/etc/prt-get.conf`:

```
prtdir /usr/ports/sigma
```

Fetch the port collection:

```
ports -u sigma
```
