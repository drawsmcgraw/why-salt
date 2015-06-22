# Why Salt???
This document serves as a reference to those who have to answer the question 
"Why Saltstack?".

## Flexibility
Use the masterless minion setup for single fire-and-forget deployments or manage
hundreds (or thousands) of minions in multiple environments.

## Modular
Store your states in Git, Subversion or S3. Same with large binary files.

## Documentation
Have you seen [the docs](http://docs.saltstack.com) lately? Documentation is not
an afterthought with Saltstack. It's an entire project unto itself.

* Need an introduction to all things Salt? Start with [the tutorials](http://docs.saltstack.com/en/latest/topics/tutorials/index.html)
* Heard about the Reactor system? It's [right here](http://docs.saltstack.com/en/latest/topics/reactor/index.html)
* How about the Salt Mine? [Read on](http://docs.saltstack.com/en/latest/topics/mine/index.html)
* Or if you want to see it all, you can jump into the [Table of Contents](http://docs.saltstack.com/en/latest/contents.html).

## Windows!!
Yes, Windows! Run Powershell scripts, add/remove Features, even reach across
multiple domains from a single point. Install, manage, and monitor software
installations across all Windows machines.

Salt supports any scripted installation (i.e. more than just MSI packages)
and offers a central location for trusted bits.

Deploy Active Directory systems into a public or private cloud with 
Salt-cloud. Everything can be automated, from creating the first Domain Controller
to joining all domain members.
