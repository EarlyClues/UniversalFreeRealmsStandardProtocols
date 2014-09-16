# Self & State

**Insofaras it may be said that an entity constitutes a "thing itself," it may be reasoned then that an entity, as a "thing" has an "itself" or - more simply, a "self."**

> *ie, programmatically accessible as: Thing.self or Entity.self*

The .self property, we can assume, acts as a container for information pertitent to the "self" of the entity. The contents of this container are an instance of "state" information.

We can define each .self as having a "default state," and in doing so, "state:default" becomes an important **Protected Designation** for entity.self or thing.self:

> *ie, Entity.self.state:default

Entity.self.state may of course take other values, but protecting "state:default" value allows entities easy access "back home" if necessary. 

## Other States

Within the [ideological framework of entities which are both state-aware and autonomously capable of manipulating their "self states"](https://medium.com/life-in-pantarctica/these-two-top-shopping-tips-could-save-you-tons-of-cash-on-your-next-trip-to-the-tri-cities-8a45c2e25449), we can imagine that allowing the "entities themselves" to define additional .self.states would most likely be advantageous.

> Entity> query entity.self.state
> entity.self.state = default
> Entity> define entity.self.state:current //current state
> entity.self.state = current

**See sample code in [lib/self.api](https://github.com/EarlyClues/UniversalFreeRealmsStandardProtocols/blob/master/lib/self.api)**
