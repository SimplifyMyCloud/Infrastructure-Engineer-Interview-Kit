# Infrastructure Homework

### The Goals are to understand how an interview candidate:

* _thinks_ about infrastructure engineering.
* _documents_ what they are thinking.
* _tech pitches_ the solution.
* _responds to_ a challenge to their solution.

## The homework

## Storyboard of the infrastructure

What I would ask you to do for the homework is either:

  * Architect a POC of WordPress running on GCP, AWS, or Azure
  * Deploy a POC of WordPress running on GCP, AWS, or Azure

Listed below is the basic requirements and you build off of those using what you think is the best infrastructure. Anything not specified in the requirements is your decision. 

*Do not spend more than 2 hours on this homework*

*Do not use your current employers computer to complete the homework*

*Use Github to host your work and send a link to the repo or gist when you are complete*

If you hit the 2 hour mark and are not done, please stop working on the homework.  Come into the interview and we will discuss your progress, using it as part of the interview.  There is no way to fail this homework so not finishing in under 2 hours is perfectly ok.  The goal is to see how you think about infrastructure, scaling, self-healing and monitoring.

For the exercise if you choose to deploy onto GCP, we will provide you with a GCP project to build into or you use your own GCP.  If you do not have a GCP account, you can sign up and get $300 in credits to use for this homework, which should be less than $10.  

The requirements:

- WordPress on GCP
- Document your findings
- Any infrastructure automation code in Git (it is not a requirement to use automation to build this, but if you do, bring the code as part of the homework so we can discuss)

The usage patterns:

- 90% of customers live in San Francisco and Tokyo
- Current average hourly traffic is 1k active users
- Estimate adding 10k active users a month
- Social marketing on the 1st & 15th of the month bring in 1,000,000 users to the website over about 24 hours
- Cost is the least important factor
- Uptime and low complexity of infrastructure management is most important factor

Topics for discussion:

- High level overview of the infrastructure you built
- What other ways could this have been deployed?
- How would (or did) you automate it?
- What sites/blogs/documentation did you use while building?

If you have any questions at all please ask.