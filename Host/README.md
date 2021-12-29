## Update System

```
apt update -y
```

## Install Certbot

```
apt install certbot -y
```

### Check Certbot Version

```
certbot --version
```

### Active Certbot in Domain

```
certbot certonly --standalone -d domain.com -d www.domain.com
```
