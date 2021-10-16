# Great quotes for the concept of Bounded Context 

Mission of this overview is to bring great quotes for the concept of Bounded Context, in order to get a better understandig of this fundamental DDD concept. Bounded context and the ubiquitous language are the foundation of DDD.

> An operational definition of where a particular model is well-defined and applicable. Typically a sub-system, or the work owned by a particular team. [Evans 2003](https://pubs.opengroup.org/architecture/o-aa-standard/DDD-strategic-patterns.html#context-map)

*last update: 16.10.2021*


![Domain Driven Design](./img/sketch.png)

##### [Patterns, Principles and Practices of Domain-Driven Design by Scott Millet and Nick Tune 2015](https://github.com/bmihovski/software-development-ebooks-1/blob/master/%5BPatterns%2C%20Principles%2C%20and%20Practices%20of%20Domain-Driven%20Design%20Kindle%20Edition%20by%20Scott%20Millett%20-%202015%5D.pdf)


* p54: Bounded contexts are used to form a **protective boundary** around models that helps to prevent software from evolving into a BBoM.
* p119: A bounded context is defined based on **team’s language,** and physical artifacts. 
* p126: Treat bounded contexts like the **borders of a country**. Nothing should pass into the bounded context unless it goes through the border control and is valid. Just like countries where people speak a different language, so does the code within your bounded context. 
* p128: There are two aspects of a problem domain that you can use as a guide to **identifying bounded contexts** — terminology and business capabilities. 
* p129: A **single team** should be responsible for a bounded context, whether that crosses one or many applications or departments. So structure teams around bounded contexts; form product and services groups rather than trying to mirror the departmental structure of the business. Ensure that teams are **responsible for a bounded context from presentation through domain logic and to persistence.**
* p131: **Unlike a subdomain**, a bounded context is a concrete technical implementation that enforces boundaries between models within an application. Bounded contexts exist in the solution space and are represented as explicit domain models in a context.
* p136: There are **no rules for defining** the boundaries of a model and therefore bounded contexts. Instead you should base bounded contexts around linguistic boundaries, team organization, subdomains and physical deployments.
* p157:  Ideally a bounded context should have its **own database**.
* p157: **Applications** can be composed of **more than one** bounded context. 
* p157: However, some people believe that the boundary of a bounded context should extend to the presentation layer. Udi Dahan’s business component gives the bounded context the responsibility for owning specific regions of the **user interface**. 
* p175: However, if your business is not complex or isn’t changing frequently then don’t automatically reach for the DDD hammer: remember there are other better suited tools in your development tool kit. Only focus your modeling efforts and DDD on the most complex bounded contexts that **bring the most value** to your customer. 
* p221: Inside a bounded context you may have a number of responsibilities. In a Shipping bounded context, for example, there may be logic to deal with priority orders and standard orders. By isolating each major responsibility as a **component**, you’ll find yourself having clearer conversations with the business and all the other benefits of DDD that you’ve already seen arise from making the implicit explicit.
* p271: Business Components Need Their Own APIs. If you work to the principle that each business component has its own private database, the only sensible way to share data with a web application is for each **business component to have its own set of APIs** exposing that data. 
* p263: Storage Is Cheap—Keep a Local Copy - An option that many teams take in this situation to reduce unwanted coupling is **to store all the data each bounded context needs locally**. 
* p293: **Dogfooding** Your APIs - When all your communication is over HTTP, there may be no need to have dedicated channels for internal and external communication. In plain English, this means that you can build APIs that bounded contexts use to communicate, and third parties can use those same APIs.
* p315: By isolating bounded contexts each owned by a single team, **loose coupling** is within reach. Each team is free to develop its features in line with its business priorities, free of cross‐team distractions or dependencies.
* p320: This follows the convention of naming API projects based on the format **{bounded context}.{Resource}**. 
* p340: Accordingly, for an event‐driven REST system, you can use a similar naming convention that communicates domain concepts, such as **{BoundedContext}.{BusinessComponent}. {Component}**.
* p489:  The **domain model** for the Listing bounded context. (Domain - Bounded Context - Domain Model)

___

##### [Domain-Driven-Design Tackling Complexity in the Heart of Software by Eric Evans 2003](https://github.com/gg-daddy/ebooks/blob/master/Eric%20Evans%202003%20-%20Domain-Driven%20Design%20-%20Tackling%20Complexity%20in%20the%20Heart%20of%20Software.pdf)
* p239: By explicitly defining a BOUNDED CONTEXT within which a model applies and then, when necessary, defining its relationship with other contexts, the modeler can **avoid bastardizing** the model.
* p304: Code reuse between BOUNDED CONTEXTS is a **hazard to be avoided**. Integration of functionality and data must go through a translation.
* p339: Generally speaking, there is a correspondence of **one team per BOUNDED CONTEXT** . One team can maintain multiple BOUNDED CONTEXTS, but it is hard (though not impossible) for multiple teams to work on one together.
* p341: The **feasibility of a deployment plan** should feed back into the drawing of the CONTEXT boundaries. When two CONTEXTS are bridged by a translation layer, one CONTEXT can be updated just so a new translation layer provides the same interface to the other CONTEXT. A SHARED KERNEL imposes a much greater burden of coordination, not just in development but also in deployment. SEPARATE WAYS can make life much simpler.
* p419: Of course, because **each BOUNDED CONTEXT is its own name space**, one structure could be used to organize the model within one CONTEXT, while another was used in a neighboring CONTEXT, and still another organized the CONTEXT MAP.


___

##### [Implementing Domain-Driven Design by Vaughn Vernon 2013](https://ptgmedia.pearsoncmg.com/images/9780321834577/samplepages/0321834577.pdf)
* p23:  You get more than a team lingo. The Language of a team in an explicit Bounded Context expressed as a domain model adds true business value and gives us certainty that we are implementing the correct software.
* 
