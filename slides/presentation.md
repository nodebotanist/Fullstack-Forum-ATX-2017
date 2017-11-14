# Serverless, IoT, and the new fullstack

---

## About Me

![left](img/profile.jpeg)

* DevRel Engineer at IOpipe
* B.S. in Computer Science, St. Edward's 2011
* B.S.E in Electrical Engineering, Arizona State University, est 2019-ish
* Baseball fan
* "The Nodebotanist"

---

## What we're gonna talk about

* Serverless
* IoT
* What about all that stuff we already use?
* The new Full Stack
* How we're going to have to work together

---

# Serverless

![inline](img/yaywut.jpg)

...Doesn't mean there aren't any servers.

---

## It's actually just a misnomer for the further abstraction of infrastructure from something you do yourself, to a service you pay a provider for

---

## [fit] Which is why another name for it, which I like, 
## [fit] is Functions as a Service (FaaS).

---

## So what does it do?

* Deploy functions to a cloud service
* Not have to worry about the infrastructure involved
	* Like, at all. You may not even know what OS is running!
* Cloud services takes care of scaling, multi-tenancy, routing
* You write code. You hit deploy. That's about it.

---

## No more setting up EC2 instances, Docker-izing your app, or writing a bash script to deploy to different instances!

![inline](img/yey.gif)

---

# Warning

Just like every other tool, architecture, or bikeshed, FaaS has good use cases, and not-so-good. There is tans of good writing out there about when and why FaaS can be right for you.

---

# [fit] Demo

---

## Okay, cool, but you know one case FaaS is really good at?
# [fit] The Internet of Things!

---

# Wait, what do I mean by IoT?

Any device that isn't running a full operating system with the sole purpose of providing the user with an ecosystem of applications for a wide range of uses but still connects to the internet, usually used to collect analytics from their surroundings or offering simplified UI for a given specific task.

---

![inline](img/what-marceline.gif)

---

# The short version

Anything that isn't a fully-fledged computer or smartphone, but often used in conjunction with them. They connect to the internet to complete specific tasks and/or collect specific data.

---

# Why does this matter to me as a Web Developer?

Because just as the lines between front-end and back-end have blurred to create the web development ecosystem we have today, technologies around Serverless and IoT are shifting the skill set of web developers, allowing you to do more with the same tools and use services to abstract away what you're not an expert at.

---

# Close your eyes and picture a firmware development environment.

Do you imagine a C file, a bunch of arcane tools, and someone with a Master's in Robotics?

---

# Hahaha no. Because I'm up here and I'm a firmware developer!

And I'll let you in on a little secret; just like when I was a web dev...

![inline](img/no-idea-what-im-doing.gif)

---

# How did this happen?

* Language Engines are becoming much smaller, with comparable power
* Microcontrollers (robot brains) are getting smaller, more powerful, and much less expensive!
* People decided they wanted to program hardware without having to use C all the time

---

# Add a dash of the magic that is the open-source movement...

![inline](img/katamari.gif)

---

## And you end up with hardware libraries for nearly all popular programming languages on the planet

---




