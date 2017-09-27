---
layout: post
title:  Productize me!
description:
date:   2017-09-26
categories:
    - devops
tags:
    - devops
author: Henrik Axelsson
excerpt:
    Have you thought about how to make your work a product?
---

### Where we were
A large client of ours has recently started their cloud migration journey. I was brought in as an iteration manager to help one of the recently renamed *Cloud Foundation* squads manage their work.

The team had previously been known as *Technology Automation* team. Strangely enough their goal was trying to automate things for other teams as much as possible.

### The challenge
Unfortunately there were some problems with automation the team tried to provide in the past. Firstly, there was often changing priorities. Secondly, when things did get built, other teams didn't tend to use them.

In addition to this, it seemed like the team was doing a lot of manual work for other teams. Things like getting firewall changes done or setting up direct connect for AWS accounts. The team didn't actually do the task, but knew who could so often took it upon themselves to help coordinate these activities.

It seemed like there were two different types of work the team was trying to do.

* Building products.
* Providing services.

#### What is a service?
Here I am using the definition of a service in the traditional sense. For example, helping get a firewall change done and not in the Software as a Service (SaaS) sense.


#### What is a product?
A techy thing that has to be built, that will be used by a customer. This could be SaaS or some other kind of consumable digital product.

### Focus
While doing both building products and providing services could possibly be done by the team, I felt that better outcomes would be achieved by focusing on one or the other.

The view from management was the team should be building things that other teams can use. Having this direction was very helpful, as it meant the service aspect could be reduced to supporting the products that we would build.

As the team had tried to build things for other teams in the past and not had the success they were hoping for, how could we increase our chances of hitting the mark this time?

### Product centric view
I decided that software/infrastructure/SaaS/scripts/automation that the team would provide should be treated as any other product:

* It must have people willing to use it (customers).
* It must be owned by a team.
* That team must have the people, responsibility, time, equipment and funding to:
  * Maintain the product.
  * Support the product.
  * Enhance the product.
  * Adapt the product.

### This product is just like the other product
My previous work as a BA has drummed into me that the most important thing to keep in mind when building any product is the customers. Ultimately they will determine the success or failure of any product. Who were our customers?

For the cloud migration initiative, the customers were teams across the organisation that were:
* Moving applications in the cloud.
* Building new applications in the cloud.
* Storing data in the cloud.

We needed to make their life easier. We needed to build products that they wanted to use.

### Putting the customer first
So far the team has built three products since Cevo engagement started.

Two of the products are being used in over 20 AWS accounts across the organisation while the third is being used by the team internally until the user experience is up to scratch. There are already two teams asking when it will be ready for them to use.

We have focused carefully on the user experience, in particular:
* Is it easy to install?
* Is it easy to use?
* Is it easy to maintain?

### Woodstock

I'll use one of the products built as an example. We called it Woodstock and it's used aggregate CloudTrail logs.

At our client, any team running a workload in AWS must send their CloudTrail logs back on premise so they can be analysed for suspicious activity. Prior to Woodstock, each workload owner had to spend several weeks liaising with security to get Splunk integration sorted out.

To get Woodstock working takes about 10 minutes for a team. The process entails:
1. Contact us on the #Woodstock slack channel with their AWS account number.
2. Configure CloudTrail to point to the correct S3 bucket.

We have also set up Confluence pages that explain what Woodstock is and how it works which makes it very easy to socialise it amongst the organisation.

### Closing thoughts
Next time you are developing something that will be used by another team, try treating it like a first class product and see how it goes! Sometimes a small shift in mindset can lead to a big difference in outcome.