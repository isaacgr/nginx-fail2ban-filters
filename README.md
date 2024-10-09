# Fail2ban filters to protect NginX

Each filter has 2 parts:

-   a configuration part that is in /etc/fail2ban/nginx.conf
-   a definition part that is in a file in /etc/fail2ban/filter.d/<filter>.conf

To configure:

1. Copy the filter files

`sudo cp nginx-*.conf /etc/fail2ban/filter.d/`

2. Copy the jail configuration file

`sudo cp nginx.conf /etc/fail2ban/jail.d/`
