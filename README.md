# 2018 Talks by Donna Malayeri - [@lindydonna](https://twitter.com/lindydonna)

## Upcoming talks

### June 26-27 - [GeekWire Cloud Tech Summit](https://www.geekwire.com/events/geekwire-cloud-tech-summit-2018/), Bellevue, WA

#### Serverless and Containers: a Match Made in the Cloud

At its core, serverless represents an evolution of cloud computing. In the early days, there were only virtual machines, and now there are containers, container orchestrators, serverless computing, and more. Even though serverless has created a big shift in how modern applications are developed, most applications are not architected in an entirely serverless way--nor should they be.

In fact, we’re seeing an emerging trend: applications now use a combination of serverless and containers. Each have their own strengths: when you want code to scale on demand, without explicitly provisioning compute resources, serverless is a good fit. For existing code, or when you need control over the execution environment, containers are a great choice. And, lightweight container services such as AWS Fargate and Azure Container Instances further blur the boundary between containers and serverless. Serverless is not all-or-nothing, it’s really a spectrum.

Through real application examples, this talk will describe guidelines for when to use containers and when to use serverless functions. Serverless and containers really are better together--learn how to have the best of both worlds!

### May 16 - [GlueCon 2018](http://gluecon.com/#agenda), Denver, CO

#### For Immutable Infrastructure, Real Code beats DSLs 

As DevOps has evolved, developers are more often responsible for creating and managing the infrastructure their application code depends on. Unfortunately, cloud tools are designed around the previous ops model, where there were organizational silos between dev and ops teams. We’ll describe a novel idea: what if you could write code in a general purpose language, code that defines both your declarative infrastructure and your application logic? What if we go beyond the idea of infrastructure-as-code, and treat infrastructure as software? We’ll show how this approach creates a fundamental shift in the way in which modern cloud applications are designed and developed.

### June 14 - [Velocity 2018](https://conferences.oreilly.com/velocity/vl-ca)

#### [Tooling in the age of serverless computing](https://conferences.oreilly.com/velocity/vl-ca/public/schedule/detail/67950)

At its core, serverless can be considered “service-full” computing, a trend that’s been around for a while. Instead of running your own Redis cluster, you use a managed cache service. Instead of running a database server on VMs, you use a database service. Serverless simply pushes this notion further: rather than keep a container active when it’s not processing requests, use a managed functions-as-a-service platform such as AWS Lambda, Azure Functions, or Google Cloud Functions.

This trend creates an architectural shift: strangely, your application becomes simultaneously simpler and more complex. Simplicity comes from managed services, which allow you to focus on your business problem instead of infrastructure. Complexity comes from the extra moving parts once you’re juggling dozens of services and hundreds of individual components. While managed services simplify your application, you must now control and understand each of them.

There are a growing number of tools that aim to wrangle this complexity. Of course, we’ve now traded one problem for another: determining which tools are best for your project, application, or organization—or if you even need a tool at all.

Tooling is necessary for serverless and service-full applications. Donna Malayeri shares a decision framework for choosing infrastructure deployment tools, based on whether you need flexibility and control or simplicity and ease-of-use. You’ll learn how to evaluate several popular cloud automation tools, including AWS SAM, Terraform, Chalice, Serverless Framework, Apex/Up, Claudia, kubeless, and Pulumi. Each of these tools offers something unique and is designed for particular problem spaces. There’s no one-size-fits-all answer and sometimes you’re better off with no tool at all.

## Past talks

### Jan 24 2018 - [ProductTank Bellevue Meetup](https://www.meetup.com/ProductTank-Bellevue), Bellevue, WA

#### [From Enterprise to Startup: How to be a successful Product Manager](https://www.meetup.com/ProductTank-Bellevue/events/246823880/)

In tech, the role of a Product and Program Manager is constantly evolving. Even within an organization, the role can be dramatically different, depending on the team and the product. Donna will talk about how the role evolved at Microsoft over the years, and what she's learned now from being at a startup. Then we'll lead an open discussion of how to adjust your role to suit your team and business needs.

[Talk slides](/slides/Malayeri-ProductTankBellevue-2018-01-24.pdf)
