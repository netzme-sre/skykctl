# skykctl
sysctl tunning for every type of service.

how to use :
curl the raw sysctl file and execute it as the root user
example :

```
curl https://raw.githubusercontent.com/sakayoga/skykctl/master/sysctl-postgres.sh -o sysctl-postgres.sh
chmod +x sysctl-postgres.sh
sudo ./sysctl-postgres.sh
```

if you use ssd for the disk, add ssd as variable
example :

```
sudo ./sysctl-postgres.sh ssd
```
