# Openresty practice

use openresty to build APIs, and more!

## Usage

1. [download openresty](https://openresty.org/en/download.html), this repo is oriented to the `*nix` operating system, notice that the directory hierarchy is different in Windows operating system.

2. install openresty, we assume it is installed at `/usr/local/openresty`.

3. enter the directory and init git:

```shell
$ sudo cd /usr/local/openresty
$ sudo git init
```

4. add remote address for git:

```shell
$ sudo git remote add origin https://github.com/xitongjiagoushi/openresty-practice.git
```

5. pull it:

    $ sudo git pull origin master

6. run nginx, redis, and test:

```shell
$ sudo nginx/sbin/nginx
$ sudo redis-server --bind 127.0.0.1 --port 6379
$ curl http://127.0.0.1/api/valuebyredis
```

## Any problems

[mail to me](mailto:root@brctl.com)
