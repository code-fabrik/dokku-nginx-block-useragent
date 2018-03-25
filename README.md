# Dokku Nginx Blocklist

Easily block malicious user agents by setting an environment variable.

## Installation

```shell
# on 0.4.x+
sudo dokku plugin:install https://github.com/code-fabrik/dokku-nginx-blocklist.git
```

## Usage

```shell
# To set a max body size, set the MAX_UPLOAD_SIZE env var
# If you unset the variable, a default of 2M will be used
dokku config:set BLOCKED_USER_AGENTS=AcoiRobot|BaiduSearch
```
