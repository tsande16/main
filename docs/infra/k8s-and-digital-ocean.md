

## Doctl

The command line tool for interacting with [Digital Ocean](https://www.digitalocean.com) is [doctl](https://docs.digitalocean.com/reference/doctl/)

```bash
$ doctl version
doctl version 1.77.0-release
```

You will require an [access token](https://docs.digitalocean.com/reference/api/create-personal-access-token/) to interact with your [Digital Ocean](https://www.digitalocean.com) account.
You can add your token using the `auth init` command as shown below

```bash
doctl auth init
```


### K8s Commmands

The following commands help to identify [k8s](https://kubernetes.io) resources within [Digital Ocean](https://www.digitalocean.com).

```bash
doctl k8s options regions
```

You will probably see something like

| Slug | Name |
| --- | --- |
| nyc1 | New York 1
| sgp1 | Singapore 1
| lon1 | London 1
| nyc3 | New York 3
| ams3 | Amsterdam 3
| fra1 | Frankfurt 1
| tor1 | Toronto 1
| blr1 | Bangalore 1
| sfo3 | San Francisco 3
