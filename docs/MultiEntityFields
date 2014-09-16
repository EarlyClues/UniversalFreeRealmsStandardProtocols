# Multi-Entity Fields

In the [Relationality of Self](https://github.com/EarlyClues/UniversalFreeRealmsStandardProtocols/blob/master/docs/SelfRelation.md), it is written:

>This plurality of `entity.self`'s that any entity is surrounded by or linked to in proximity is a defining factor in determining or defining the field, environment or contextuality of that entity. 

The purpose of present document is to expound on this concept of a "field" as being made up of multiple "entities" in relation to one another. 

While an `entity` cannot access private `entity.self.state`'s of other entity's, it may request `entity.self` of other entities, unless protected. 

### How it might work:

> Entity> query all entities relative to entity.self
> Entity1> entity.self
> Entity2> entity.self
> Entity3> entity.self

Any responding entities to such a query would constitute the components of the "field" of the querying entity, such that querying `field.self` in the above case would yield a list of component entities:

> Entity> query field.self
> Field> self = Entity, Entity1, Entity2, Entity3

And `field.self.state` would yield as public results to entities which compose that field the public state (if any) of entities composing that field, as well as relational data between entities. 

> Entity> query field.self.state
> Field> self = Entity.state:default, Entity1.state:protected, Entity2.state:current, Entity3.state:default
> Field> self.state = Entity is next to Entity1. Entity2 is above Entity3. Entity is to the left of Entity2
