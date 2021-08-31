# The philosophy of Domain Driven Design

Domain-driven design is a philosophy and approach to developing software, it's not an architecture. Strategic DDD helps us of getting out of the big ball of mud \(logical and not physical coupling\). It helps us in identifying our business capability boundaries \(**bounded context**\) using an **ubiquitous language** \(a language that is shared and understood in one part of the business\) as well identifying and naming the relationships \(**context mapping**\) that our bounded contexts \(also teams\) have between each other. By understanding the relationships between our contexts, it aids in making decisions about how are we going to model our software.

It’s a mindset: the application **Design** is **Driven** by the business **Domain**. There are no steps of how to do DDD and there isn’t a formula you can learn. What you can learn from Eric Evans or other DDD experts is how they approached a problem, but nobody can give you a sure recipe of how to do things.

![Domain Driven Design](./img/ddd.jpeg)

#### Theory books and pdfs

* The canonical Big Blue Book of Eric Evans \(2003\): [Domain-Driven-Design Tackling Complexity in the Heart of Software](https://github.com/gg-daddy/ebooks/blob/master/Eric%20Evans%202003%20-%20Domain-Driven%20Design%20-%20Tackling%20Complexity%20in%20the%20Heart%20of%20Software.pdf)
* Domain Driven Design Quickly is a short, quick-readable summary and introduction to the fundamentals of DDD \(2006\): [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly/)
* Domain Driven Design, Definitions and Pattern Summaries \(by Eric Evans 2015\): \[Domain-Driven Design Reference\]\([https://www.domainlanguage.com/wp-content/uploads/2016/05/DDD\_Reference\_2015-03.pdf](https://www.domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf)\)
* Vaughn Vernon presents the whole of Domain-Driven Design \(by Vaughn Vernon 2013\): [Implementing Domain-Driven Design](https://ptgmedia.pearsoncmg.com/images/9780321834577/samplepages/0321834577.pdf)
* Concise basics of DDD \(by Vaughn Vernon 2016\): [Domain-Driven Design Distilled](https://github.com/phulei/books-1/blob/master/software-development/domain-driven-design-distilled.pdf)
* Patterns, Principles and Practices of Domain-Driven Design \(by Scott Millet and Nick Tune 2015\): [Patterns, Principles and Practices of Domain-Driven Design](https://github.com/bmihovski/software-development-ebooks-1/blob/master/%5BPatterns%2C%20Principles%2C%20and%20Practices%20of%20Domain-Driven%20Design%20Kindle%20Edition%20by%20Scott%20Millett%20-%202015%5D.pdf)
* The Anatomy of Domain Driven Design \(by Scott Millett 2019\): [Primer DDDEurope.com](https://www.elbandit.co.uk/images/DDDEU-Booklet.pdf)

#### Theory links

* DDD easily explained \(by Anders Gill 2019\): [Part 1: Domain Driven Design like a pro](https://medium.com/raa-labs/part-1-domain-driven-design-like-a-pro-f9e78d081f10)
* A Decade of DDD, CQRS and Event Sourcing \(by Anes Hasičić 2019\): [A Decade of DDD, CQRS and Event Sourcing by Anes Hasičić](https://tacta.io/a-decade-of-ddd-cqrs-and-event-sourcing/)
* DDD introduction \(by Dan Haywood 2019\): [An Introduction to Domain Driven Design](https://www.methodsandtools.com/archive/archive.php?id=97)
* Various articles on Sapiens Works \(2012 - 2018\): [Sapiens Works: Domain Driven Design](https://blog.sapiensworks.com/tags.html#Domain%20driven%20design)
* Wikipedia \(2021\): [Domain-driven design](https://en.m.wikipedia.org/wiki/Domain-driven_design)

### DDD in practice

* This article shows a domain-driven approach to designing microservices \(by Microsoft 2019\): [Using domain analysis to model microservicess](https://docs.microsoft.com/en-us/azure/architecture/microservices/model/domain-analysis)

### Bounded Context

* What is Bounded Context? \(by Dave Taubler 2020\): [If You’re Building Microservices, You Need to Understand What a Bounded Context is](https://medium.datadriveninvestor.com/if-youre-building-microservices-you-need-to-understand-what-a-bounded-context-is-30cbe51d5085)
* BoundedContext \(by Martin Fowler 2014\): [Bounded Context is a central pattern in Domain-Driven Design](https://martinfowler.com/bliki/BoundedContext.html)

## Bounded Contexts and Microservices

* Bounded Contexts are the exact opposite of Microservices! \(by Vladik Khononov 2018\): [Bounded Contexts are NOT Microservices](https://vladikk.com/2018/01/21/bounded-contexts-vs-microservices/)
* Design of microservices using the principles of Domain-Driven Design \(by IBM 2018\): [Apply Domain-Driven Design to microservices architecture](https://www.ibm.com/garage/method/practices/code/domain-driven-design/)

## Bounded Contexts and Domain Models

* A domain model should omit the extraneous information irrelevant to its task. \(by Vladik Khononov 2020\): [Thread on models and bounded contexts](https://mobile.twitter.com/vladikk/status/1335947978482339841)

## Relationship Bounded Contexts and Subdomains

* The subtle relationship between bounded contexts and sub-domains \(by Lev Gorodinski 2013\): [Sub-domains and Bounded Contexts in Domain-Driven Design \(DDD\)](http://gorodinski.com/blog/2013/04/29/sub-domains-and-bounded-contexts-in-domain-driven-design-ddd/)
* Stackoverflow \(2018\): [Confused about Bounded Contexts and SubDomains](https://stackoverflow.com/questions/18625576/confused-about-bounded-contexts-and-subdomains)
* Stackoverflow \(2018\): [Can subdomain and bounded context be same in domain driven design?](https://stackoverflow.com/questions/32069892/can-subdomain-and-bounded-context-be-same-in-domain-driven-design)

## Context map: communication between Bounded Contexts

* Stackoverflow \(2013\): [Communicating between two Bounded Contexts in DDD](https://stackoverflow.com/questions/16713041/communicating-between-two-bounded-contexts-in-ddd)
* Stackoverflow \(2013\): [DDD - How to design associations between different bounded contexts](https://stackoverflow.com/questions/18761001/ddd-how-to-design-associations-between-different-bounded-contexts)

## Difference between Entities and Value Objects

* Entities versus Value Objects \(by Philip Brown 2014\): [What is the difference between Entities and Value Objects?](https://www.culttt.com/2014/04/30/difference-entities-value-objects/)
* Entity vs Value Object \(by Vladimir Khorikov 2016\): [Entity vs Value Object: the ultimate list of differences](https://enterprisecraftsmanship.com/posts/entity-vs-value-object-the-ultimate-list-of-differences/)

## DDD concepts and REST equivalents

* API design - Azure Architecture \(2019\): [Designing APIs for microservices](https://docs.microsoft.com/nl-nl/azure/architecture/microservices/design/api-design)

## Awesome Github.com sites

* kgoralski \(2019\): [Domain-driven design \(DDD\) learning resources](https://github.com/kgoralski/personal-wiki-and-learning-resources/blob/master/domain-driven-design.md)
* heynickc \(2021\): [Awesome Domain-Driven Design](https://github.com/heynickc/awesome-ddd)

## DDD slack community

* ddd-cqrs-es: [ddd-cqrs-es.slack.com](https://ddd-cqrs-es.slack.com/)

