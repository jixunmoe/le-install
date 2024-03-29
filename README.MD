# LE-Install

A set of helper scripts to distribute certs securely, to nginx hosts.

## Install

```sh
git clone https://github.com/jixunmoe/le-install /opt/le-install

# When acme.sh is installed as root to default location '/root/.acme.sh/':
ln -sf /root/.acme.sh/acme.sh /opt/le-install/acme.sh
```

## Usage

Auto distribute certs via SSH:

```sh
/opt/le-install/le-register '*.example.com' 'user@host1.example.com' 'user@host2.example.com'
```
