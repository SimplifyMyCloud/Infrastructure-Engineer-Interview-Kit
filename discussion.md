# Candidate Homework Discussion

## The premise

* The candidate is presenting their proposal for a POC of Wordpress on GCP
* The interviewers are assuming the role of the imaginary startup founder asking for the POC
* The goal of the discussion is to allow the candidate to show:
  * how they think about infrastructure
  * how they communicate how they think about infrastructure
  * how they can contribute to a healthy infrastructure culture

## What to look for

When the candidate is presenting their proposed solution you the interviewer are looking for certain indications on how they think.  

### An incomplete list of indicators

* Simplicity in engineering
* Cloud native services
* Following GCP best practices
* Referencing of documentation
* Clear communication

### A best practices infrastructure

The simplest, cloud native, GCP best practices solution for Wordpress on GCP would be:

* Wordpress server is just a content hydrator for the GCP CDN using a WP plugin that forces Wordpress to be a static website generator.
  * WP on a GCE VM
  * WP on GCP GAE
  * WP on GKE works but GKE is overly complex for a simple WP server
* Wordpress server uses GCP CloudSQL for the database

Pushing the marketing website into the CDN provides the following benefits that the candidate should be highlighting in their proposal:

* Simplest solution
* Unlimited scaling
* Simple text files
* No need for WAFs
* No server VMs to bake
* No logins anywhere
  
### Challenging the proposal

An important factor in a good engineer is willing to have their ideas challenged and will listen, accept the feedback, and then clearly answer the challenge.

Potential challenges:

* Why not just install Wordpress on a single VM?
* Why not just install MySQL on a VM?
* Why multiple Kubernetes clusters? (If offering a K8s cluster in Japan & West Coast USA, a common solution.)

## Links

[Schedule](schedule.md)

[The homework](homework.md)

[The homework discussion](discussion.md)

[GCP success links](gcp_success_links.md)