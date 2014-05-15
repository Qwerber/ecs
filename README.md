ecs
===

ECS in CPP.

Structures:

-Entity:Component

-Component

-SubSystem

-Factory

-ObjectPool

-Component

--ID

--remove

--load()

--unload()

--cache(ID)

--getAllCaches()

-Entity

--ID

--hash()

--addComponent()

--removeComponent(ref)

--removeComponent(ID)

--getComponent(ref)

--getComponent(ID)

--load()

--unload()

--remove()

Subsystem

--ID

--priority

--get()

--update()

--addComponent(C)


ObjectPool

--get()

--pool()

(Insert Large Component Lib)

* virtual functions
* 
* object ID macros
