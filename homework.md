# Infrastructure Homework

## Please document:

* Architect out a POC of WordPress running on GCP in documentation
* Do Not actually build anything, just document it
  
All documentation will be contained in a Github repo shared back to the interviewing team.  

Please:

*Do not spend more than 2 hours on this homework*

*Do not use your current employers computer to complete the homework*

*This is a POC of Wordpress, think development environment quality, not production which requires more than 2 hours*

If you hit the 2 hour mark and are not done, please stop working on the homework.  Come into the interview and we will discuss your progress, using it as part of the interview.  There only way to fail this homework is to not start it at all.  

## The requirements:

* POC architecture diagram of WordPress on GCP that will scale to the usage patterns
* Documentation of your proposal in a slide deck

## The usage patterns:

* 90% of customers live in San Francisco and Tokyo
* Current average hourly traffic is 1k active users
* Estimate adding 10k active users a month
* Social marketing on the 1st & 15th of the month bring in 1,000,000 users to the website over about 24 hours
* Wordpress web content is built once and then updated no more than twice a year
* There are no customer logins for Wordpress, it is just a static informational website
* Database queries are rare and DB usage is very low
* Cost is the least important factor
* Uptime and low complexity of infrastructure management is most important factor
* Cloud native & best practices GCP infrastructure is preferred

## Topics for discussion:

* High level overview of the infrastructure you are proposing
* What other ways could this have been deployed?
* What sites/blogs/documentation did you use while architecting?

If you have any questions at all please ask.

## Subject Matter Experts tracks:

There are three SME tracks that you may be assigned to follow.  If you are assigned one of these SME tracks, we want the homework solution to focus heavily on that track.  These SME tracks are in addition to the standard Cloud Consultant role and we will have discussed with you the track during the screening call.  If we did not discuss these SME tracks with you and you feel you have an expertise in any of the three, feel free to choose your strongest track for the homework.  Otherwise please skip this section.

### Security SME:

For the homework, please engineer the Wordpress architecture to be highly secured on GCP.  Again we want GCP native security tooling and services to be used.  A few areas we will focus on:

* Wordpress Admin page defensive lockdown
* Common web vulnerabilities defense
* DDoS defense
* Offensive security
* Ongoing security plan to address future security issues

### Networking SME:

For the homework, please engineer the Wordpress architecture so the Wordpress Server is hosted inside an on-prem datacenter.  That datacenter is then "cloud connected" to GCP to utilize GCP for hosting.  A few areas we will focus on:

* GCP cloud connect
* Routing
* Firewalling
* Logs exported back to on-prem

### Kubernetes SME:

For the homework, please engineer the Wordpress architecture so the Wordpress server is hosted on GKE.  A few areas we will focus on:

* Wordpress hosting on GKE
* GKE configuration
* GKE securely hosting Wordpress
* Logging from the Wordpress container to Stackdriver and a Log Warehouse
* GKE auditing with a focus on security
* GKE deployments to CiCd Wordpress content
* GKE deployments to update Wordpress itself
