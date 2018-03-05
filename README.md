# VPS Configuration files (Nginx, supervisor, gunicorn)

This repository contains configuration files for a VPS, using django.

## Getting Started

You should follow the tutorial:
[Setting up Django with Nginx, Gunicorn, virtualenv, supervisor and PostgreSQL](http://michal.karzynski.pl/blog/2013/06/09/django-nginx-gunicorn-virtualenv-supervisor/) - by Michal

### Prerequisites

What things you need to follow tutorial

```
VPS with Ubuntu
```

# Take note

The configuration files are 99% the same as in the tutorials. However, it was necessary to configure ``proxy_pass`` based on where my ``gunicorn.sock`` was.
