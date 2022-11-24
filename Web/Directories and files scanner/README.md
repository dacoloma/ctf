# Scan tools
## Directories and files
### Gobuster
Gobuster is a tool used to brute-force URIs including directories and files as well as DNS subdomains.
```sh
gobuster -h
gobuster dir -u http://[ip] -w /path/to/wordlist/file
gobuster dir -u http://[ip] -w /path/to/wordlist/file -x php
```
### Dirsearch
This package contains is a command-line tool designed to brute force directories and files in webservers.

As a feature-rich tool, dirsearch gives users the opportunity to perform a complex web content discovering, with many vectors for the wordlist, high accuracy, impressive performance, advanced connection/request settings, modern brute-force techniques and nice output.
```sh
dirsearch -y
dirsearch -u http://[ip] -w /path/to/wordlist/file -e php
```
## CMS
### wpscan
Wpscan is a tool to scan websites created with Wordpress.
```sh
wpscan --url [url]
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc0MjczMDc2OCwtMTY3Mzg1MDAyOV19
-->