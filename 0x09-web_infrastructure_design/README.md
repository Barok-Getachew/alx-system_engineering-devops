# 0x09. Web infrastructure design
This is a team of 3 project but can be done alone.
This project contains links to diagrams representing different web infrastructures. Its goal is to understand, on a very high-level, how web infrastructures are organized and what are their components.
## Resources
- Read or watch:
	* Network basics concept page
	* Server concept page
	* Web server concept page
	* DNS concept page
	* Load balancer concept page
	* Monitoring concept page
	* [What is a database](https://www.techtarget.com/searchdatamanagement/definition/database)
	* [What’s the difference between a web server and an app server?](https://www.youtube.com/watch?v=S97eKyv2b9M)
	* [DNS record types](https://pressable.com/?s=DNS&post_type=knowledgebase)
	* [Single point of failure](https://en.wikipedia.org/wiki/Single_point_of_failure)
	* [How to avoid downtime when deploying new code](https://softwareengineering.stackexchange.com/questions/35063/how-do-you-update-your-production-codebase-database-schema-without-causing-downt#answers-header)
	* [High availability cluster (active-active/active-passive)](https://docs.oracle.com/cd/E17904_01/core.1111/e10106/intro.htm#ASHIA712)
	* [What is HTTPS](https://www.instantssl.com/http-vs-https)
	* [What is a firewall](https://www.webopedia.com/definitions/firewall/)


	## Table of content
FIiles | Description
---------- | ----------
[0-simple_web_stack](./0-simple_web_stack) | On a whiteboard, design a one server web infrastructure that hosts the website that is reachable via www.foobar.com. Start your explanation by having a user wanting to access your website.
[1-distributed_web_infrastructure](./1-distributed_web_infrastructure) | On a whiteboard, design a three server web infrastructure that hosts the website www.foobar.com.
[2-secured_and_monitored_web_infrastructure](./2-secured_and_monitored_web_infrastructure) | On a whiteboard, design a three server web infrastructure that hosts the website www.foobar.com, it must be secured, serve encrypted traffic, and be monitored.
[3-scale_up](./3-scale_up) | Readme: [Application server vs web server](https://www.nginx.com/resources/glossary/application-server-vs-web-server/)
