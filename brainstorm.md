# Kubernetes (is) for Developers

## Whoami

Diogo Correia
From Porto de Mós
Based in Aveiro
Work at MetaCell

<!-- Insert photo of our two apps -->

## Topic for the presentation

1. Context for this talk
2. A fast Kubernetes origins and what is solves
3. Minimal overview on How it works
4. Remember the design principles and why they mater
5. Advocate for a closer relationship between developers and kubernetes
6. An example of a real use-case for that

## Context

for 3 years I was a software developer a team lead and a developer advocate that tried to find need ways of boosting the company's technical excellence, foster innovation and be overall more efficient at doing our job. 

the devops team decided to transition to kubernetes and our team was the Guinea pig.
kubernetes was advocated inside the company fairly strongly, buy after 3 years, out of 5 teams, other than devops and mine, no one adopted it.

### Why was that

As advocate I had to answer this question and provide a plan.
So I gather feedback from the teams and internal in my team.

It was a mix of things, but for the most, these were the most prevalent:

- It is to complicated
- It is to restrictive

I was expecting this. I also worked with our cluster everyday for the past 3 years, so I understood their pains.

### It is to complicated

Kubernetes is a big project with a lot of things.
If your day to day is bringing business value to the table, you probably will be fairly far from operating a cluster.
Probably not even touching one.

### It is to restrictive

If you try to touch one you will be meet by some opinionated restrictive configuration that you will change, push to git and pray that it works on some continuous delivery system.

You are fully dependent on the platform team to respond to your requirements and that is overwhelming for both parts.

If you want to grab developer adoption you must give something back, not take things away.

### Step back

So lets take a steep back before we deal with these issue and put developers up to speed with kubernetes so we can come back to this.

## History

Key factors that created the big bang in 2014?

### Pre-history

You operated real machines in datacenters, so you had operations people and developer people. 

### DevOps

2008 DevOps: The ideia of DevOps was that teams were two sides of the same coin and should work together, from the design, development process, to production and support.
  by Partick Debois
Andrew Clay Shafer

It is not a team or a function, it is the process of developing and the action of functioning and delivering.


### Cloud Computing

The DevOps thinking aligned really well with infrastructure as a service. So the Cloud started to take a prominent place in the industry.
You now do not worry about building and maintaining machines. You pay for as much as you want and you receive it instantly.
It was a nice model for high growing companies.
AWS had the monopoly and was a growing cash cow.

### ??? (2013)

The last one. Anyone can guess?

### Ah ah, Docker

Suddenly we were able to write our software, package it in a nice and friendly way, and distributing it to be accessible and reproducible, local or in the cloud.
At the time most of the big companies were already heavily invested in containers. They are mostly just Linux kernel features: cgroups, namespaces and union-capable file system.
But prior to Docker, running containers was hard. If you were outside of the big technology companies, most probably, you would not have the technical capacity to use it at all.

### Missing thing - Scale

Docker brought a good abstraction for distributing software. But at a considerable scale, distributing software stops being your biggest problem. Manage and operate thousands of servers and their workloads it a much greater headache.

- How can we grab different pieces of software and run them together?
- How do we schedule containers across a bunch of different computers?
- How do we serve and scale things up as requirements change?

### Kubernetes beging

Google internally was already dealing with these things and cloud economics made a reality.
the rest is history

--> see: documentary on kubernetes

## Minimal overview on How it works

Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications."






