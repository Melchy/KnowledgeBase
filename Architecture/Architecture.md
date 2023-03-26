# Software architecture knowlage base

## Overview

[Patterns of Enterprise Application Architecture](https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420) - contains basic patterns every proggramer should know. For example layered architecture, ORM, DTO. This book also describes 3 basic domain patterns -> transactions script,active record and domain model.

Basic domain model patterns (with anemic model) are also described in [Patterns, Principles, and Practices of Domain-Driven Design](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - chapter Domain Model Implementation Patterns

[The Software Architecture Chronicles](https://herbertograca.com/2017/07/03/the-software-architecture-chronicles/) - Short overview of many architectures.

## Layered architecture

[Patterns of Enterprise Application Architecture](https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420) - chapter layered architecture

[Software Architecture Patterns by Mark Richards](https://www.oreilly.com/library/view/software-architecture-patterns/9781491971437/]) - first chapter

### Skipping layers in Layered architecture. (Also called Open/Closed or relaxed system)

Patterns of Enterprise Application Architecture - page 20

Domain-Driven Design: Tackling Complexity in the Heart of Software - Figure 4.1 in chapter Isolating the Domain.

Software Architecture Patterns by Mark Richards - first chapter

## Hexagonal architecture

[Hexagonal architecture](https://beyondxscratch.com/2017/08/19/decoupling-your-technical-code-from-your-business-logic-with-the-hexagonal-architecture-hexarch/)

[Cockburn talk heaxagonal](https://www.youtube.com/watch?v=th4AgBcrEHA&list=PLGl1Jc8ErU1w27y8-7Gdcloy1tHO7NriL)

## DDD

[Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215) - very hard book. Contains some usefull information but over all isn't probably worth reading.

[Patterns, Principles, and Practices of Domain-Driven Design](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - personaly i think this book is much better than original [Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)

[Delete operation in DDD](http://udidahan.com/2009/09/01/dont-delete-just-dont/)

[JImmi bogard general DDD tips](https://lostechies.com/gabrielschenker/2015/04/16/ddd-revisited/)

[Jimmy boggard refactoring anemic model to DDD](https://vimeo.com/43598193)

[Aggregate example by Jimmi boggard](https://lostechies.com/gabrielschenker/2015/05/25/ddd-the-aggregate/)

[Example of aggregate design by Vernon](https://dddcommunity.org/library/vernon_2011/)

[Example of DDD](https://www.mirkosertic.de/blog/2013/04/domain-driven-design-example/)

[Some DDD patterns](https://lostechies.com/jimmybogard/2010/02/04/strengthening-your-domain-a-primer/)

[Specification pattern - sharing logic in query and domain](https://enterprisecraftsmanship.com/posts/specification-pattern-c-implementation/)

[Entity and value object differences](https://enterprisecraftsmanship.com/posts/entity-vs-value-object-the-ultimate-list-of-differences/)

[Example of modeling (ubiqutous language)](https://www.youtube.com/watch?v=T29WzvaPNc8)

## Domain events

General description in [Patterns, Principles, and Practices of Domain-Driven Design](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709)

[Some more information](https://docs.microsoft.com/cs-cz/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/domain-events-design-implementation)

[Dispatching events](https://enterprisecraftsmanship.com/posts/domain-events-simple-reliable-solution/)

[Merging events](https://enterprisecraftsmanship.com/posts/merging-domain-events-dispatching/)

## Anemic domain model

[Famous article](https://martinfowler.com/bliki/AnemicDomainModel.html)

[More information](https://lostechies.com/jimmybogard/2009/12/03/persistence-model-and-domain-anemia/)

[Diffrent opinion](http://codebetter.com/gregyoung/2009/07/15/the-anemic-domain-model-pattern/)

## CQRS

[CQRS basics](https://martinfowler.com/bliki/CQRS.html)

[Basic informations with C# examples](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)

Patterns, Principles, and Practices of Domain-Driven Design - chapter Domain model reporting contains some interesting information
about reporting in DDD. It's not CQRS entierly but it can be viewed as simple CQRS.

[CQRS with one data store without event store. Similar to Reporting in DDD.](https://vladikk.com/2017/03/20/tackling-complexity-in-cqrs/)

[CQRS vs specification](https://enterprisecraftsmanship.com/posts/cqrs-vs-specification-pattern/)

## Design methodologies

[Event storming 1](https://www.eventstorming.com/)
[Event storming 2](https://github.com/mariuszgil/awesome-eventstorming)
[Event storming 3](https://www.youtube.com/watch?v=xIB_VQVVWKk)

[Domain story telling 1](https://www.youtube.com/watch?v=MPQfb7fsw3I)
[Domain story telling 2](https://domainstorytelling.org/)

[Gibrish game](http://codebetter.com/gregyoung/2012/02/29/the-context-game-2/)

[How to split bounded contexts](https://www.amazon.com/Team-Topologies-Organizing-Business-Technology/dp/1942788819)
page 107 (fracture planes) -  ubiquitous language, Regulatory Compliance, Change Cadence, Team Location, Risk,  Performance Isolation, Technology, User Persona


## General

[Good architecture pays of in matter of weeks (and other tips from) according to Martin Fowler](https://youtu.be/p5Qj75nJPEs?t=2742)
