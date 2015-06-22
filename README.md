# Why Salt???
This document serves as a reference to those who have to answer the question 
"Why Saltstack?".

## Flexibility
Use the masterless minion setup for single fire-and-forget deployments or manage
hundreds (or thousands) of minions in multiple environments.

## Modular
Store your states in Git, Subversion or S3. Same with large binary files.

## Windows!!
Yes, Windows! Run Powershell scripts, add/remove Features, even reach across
multiple domains from a single point. Install, manage, and monitor software
installations across all Windows machines.

Salt supports any scripted installation (i.e. more than just MSI packages)
and offers a central location for trusted bits.

Deploy Active Directory systems into a public or private cloud with 
Salt-cloud. Everything can be automated, from creating the first Domain Controller
to joining all domain members.
