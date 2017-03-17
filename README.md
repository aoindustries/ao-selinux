# [<img src="ao-logo.png" alt="AO Logo" width="35" height="40">](https://aoindustries.com/) [AO SELinux](https://aoindustries.com/ao-selinux/)
Java API for managing Security-Enhanced Linux (SELinux).

## Features
* Clean programmatic access to [semanage](https://fedoraproject.org/wiki/SELinux/semanage).
* Implementation of `semanage port` commands:
    * Easily reconfigure all ports for a given SELinux type.
    * Automatically coalesces adjacent port ranges.
    * Presents a single cohesive view of all ports, hiding the nuance and complexity of the interactions between default policy and local policy.
    * Supports seamlessly overriding default policy.
    * Detects conflicts in local policy between different SELinux types.
* Small footprint, minimal dependencies - not part of a big monolithic package.

## Motivation
While migrating our servers to CentOS 7 we are running with SELinux in enforcing mode.  Our server configuration process, [AOServ Daemon](https://aoindustries.com/aoserv/daemon/), is written in the Java programming language.  We desire a clean interface to SELinux without having to operate with `semanage` and other commands directly.

## Evaluated Alternatives
We were unable to find any existing implementations via [GitHub](https://github.com/search?utf8=%E2%9C%93&q=java+selinux&type=Repositories&ref=searchresults), [The Central Repository](http://search.maven.org/#search|ga|1|selinux), or [Google Search](https://www.google.com/search?q=java+api+for+selinux).

## Project Links
* [Project Home](https://aoindustries.com/ao-selinux/)
* [Changelog](https://aoindustries.com/ao-selinux/changelog)
* [API Docs](https://aoindustries.com/ao-selinux/apidocs/)
* [Maven Central Repository](https://search.maven.org/#search%7Cgav%7C1%7Cg:%22com.aoindustries%22%20AND%20a:%22ao-selinux%22)
* [GitHub](https://github.com/aoindustries/ao-selinux)

## Contact Us
For questions or support, please [contact us](https://aoindustries.com/contact):

Email: [support@aoindustries.com](mailto:support@aoindustries.com)  
Phone: [1-800-519-9541](tel:1-800-519-9541)  
Phone: [+1-251-607-9556](tel:+1-251-607-9556)  
Web: https://aoindustries.com/contact
