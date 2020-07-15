# Infrastructure Homework

## Interview Jeopardy

"Interview jeopardy" is an insult to every candidates intelligence.  "How do you show the contents of a Linux directory?" - the only appropriate answer is "Why do you think I am lying about working in infrastructure for the past xx number of years?".  If you are asking my how to `ls` a directory on Linux, and my resume shows xx+ years of Linux SysAdmin experience, you are accusing me of lying about those xx+ years since running `ls` is done within the first 5 seconds of logging into a Linux box for the first time on the very first day of being a SysAdmin.  During a technical interview, asking *any* question that can be googled, is insulting to everyones intelligence.  The goal of a interview is not to see how well someone searches the web, but how they think and communicate.  Thinking and communicating are the two basic tenets of any technical engineering job.

## Infrastructure Engineer Interviewing Kit

The infrastructure homework kit is designed to showcase how the candidate thinks about building infrastructure and how the candidate communicates those ideas to the customer.  For this homework the interviewing engineer will act as a semi-technical startup founder looking to build a marketing website for the startup.  During the architectural discussion the "founder" may ask questions about the infrastructure proposal.  There are no trick questions, hidden answers, or "gotchas" as we just want to see how the candidate builds resilient infrastructure to get the job done.

There are two paths to complete the homework:

* Architect out a POC of WordPress running on GCP in documentation
* Build out a POC of WordPress running on GCP using a deployment
  
All documentation will be contained in a Github repo shared back to the interviewing team.  

Please:

*Do not spend more than 2 hours on this homework*

*Do not use your current employers computer to complete the homework*

*Automation code is not expected for this homework*

*This is a POC of Wordpress, think development environment quality, not production which requires more than 2 hours*

If you hit the 2 hour mark and are not done, please stop working on the homework.  Come into the interview and we will discuss your progress, using it as part of the interview.  There only way to fail this homework is to not start it at all.  

For the exercise if you choose to deploy onto GCP, we will provide you with a GCP project to build into or you use your own GCP.  If you do not have a GCP account, you can sign up and get $300 in credits to use for this homework, which should be less than $10.  

The requirements:

* POC architecture of WordPress on GCP that will scale to the usage patterns
* Documentation of your proposal

The usage patterns:

* 90% of customers live in San Francisco and Tokyo
* Current average hourly traffic is 1k active users
* Estimate adding 10k active users a month
* Social marketing on the 1st & 15th of the month bring in 1,000,000 users to the website over about 24 hours
* Wordpress web content is built once and then updated no more than twice a year
* There are no customer logins for Wordpress, it is just a static informational website
* Database queries are rare and DB usage is very low
* Cost is the least important factor
* Uptime and low complexity of infrastructure management is most important factor

Topics for discussion:

* High level overview of the infrastructure you built
* What other ways could this have been deployed?
* What sites/blogs/documentation did you use while building?

If you have any questions at all please ask.
