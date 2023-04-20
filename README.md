# Autoproxy
This is a simple script that iterates through available proxies from proxyscrape and configures the proxies on **MacOS only*. This can also be implemented into web scrapers. 

## Install
Simply clone the repo: `git clone https://github.com/hainesdata/autoproxy.git` or download the zip from Github.

## Dependencies
Currently, this runs in a Python environment. For now, dependencies must be installed manually, as needed. 

## Usage
Simply replace `us` in the last line `enable_proxy('us')` to your desired proxy region. Expects one of the following values:
```
all, us, id, br, kh, ua, mx, de, th, ar, cn, mn, ru, tr, rs, pl, co, vn, ng, kr, in, bd, cl, fr, bg, it, sg
```
Then run~
