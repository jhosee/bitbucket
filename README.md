# BitBucket Apache HTTPS Reverse Proxy

This was one of of the most painful and lengthy application deployments I had to perform, primarily due to the lack of clear and concise documentation. I've attached my final configuration settings which finally allowed my Bitbucket instance to be properly reverse-proxied by Apache 2.4 on the same system.

## Prerequisites

Atlassian Bitbucket 5.7
Apache 2.4

### Files

/etc/apache2/000-default.conf
var/atlassian/application-data/bitbucket/shared/bitbucket.properties

## References

* [Proxying and securing Bitbucket Server](https://confluence.atlassian.com/bitbucketserver/proxying-and-securing-bitbucket-server-776640099.html)
* [Atlassian Bitbucket](https://bitbucket.org)
* [HTTP Apache Reverse Proxy Settings for Bitbucket](https://stackoverflow.com/questions/43815873/set-apache-subdomain-reverse-proxy-for-bitbucket?answertab=active#tab-top)

## Acknowledgments

* Hat tip to all the Atlassian support engineers who steering me in the right direction over many months when they really obligated to do so.