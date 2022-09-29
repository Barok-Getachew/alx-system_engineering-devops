# 0x0F. Load balancer

## Background Context
You have been given 2 additional servers:

	- gc-[STUDENT_ID]-web-02-XXXXXXXXXX
	- gc-[STUDENT_ID]-lb-01-XXXXXXXXXX
Let’s improve our web stack so that there is redundancy for our web servers. This will allow us to be able to accept more traffic by doubling the number of web servers, and to make our infrastructure more reliable. If one web server fails, we will still have a second one to handle requests.

For this project, you will need to write Bash scripts to automate your work. All scripts must be designed to configure a brand new Ubuntu server to match the task requirements

## Resources
- [Introduction to load-balancing and HAproxy](https://www.digitalocean.com/community/tutorials/an-introduction-to-haproxy-and-load-balancing-concepts)
- [HTTP header](https://www.techopedia.com/definition/27178/http-header)
- [Debian/Ubuntu HAProxy packages](https://haproxy.debian.net/)

## Table of contents
Files | Description
----- | -----------
[0-custom_http_response-header](./0-custom_http_response-header) | Bash script configuring a brand new Ubuntu server with Nginx so that its HTTP response contains a custom header
[1-install_load_balancer](./1-install_load_balancer) | Bash script configuring a brand new Ubuntu server and adds HAproxy with version equal or greater than 1.5
[2-puppet_custom_http_response-header.pp](./2-puppet_custom_http_response-header.pp) | Puppet manifest configuring a brand new Ubuntu server with Nginx so that its HTTP response contains a custom header
