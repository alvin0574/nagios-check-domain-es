# Introduction #

Here we explain how to use the script


# Script sintax #

check\_domain\_es - v1.0.4

Copyright (c) 2011 Juan Pedro Escalona Rueda <jpescalona@otioti.com> under GPL License

This plugin checks the expiration date of a domain name.

Usage: check\_domain\_es -h `|` -d `<domain>` `[`-c `<critical>``]` `[`-w `<warning>``]`

NOTE: -d must be specified

  * -h: Print detailed help
  * -d: domain name to check
  * -w: Response time to result in warning status (days). 30 days by default
  * -c: Response time to result in critical status (days). 7 days by default

This plugin will use whois service to get the expiration date for the domain name.

Example:
check\_domain\_es.py -d iavante.es -w 30 -c 10