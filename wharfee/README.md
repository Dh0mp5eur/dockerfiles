# Installation and running `wharfee

```
$ docker pull dh0mp5eur/wharfee
```

```
$ docker run --rm --privileged -v /var/run/docker.sock:/run/docker.sock -ti -e TERM=$TERM dh0mp5eur/wharfee
```

```
alias wharfee='docker run --rm --privileged -v /var/run/docker.sock:/run/docker.sock -ti -e TERM=$TERM dh0mp5eur/wharfee'
```
