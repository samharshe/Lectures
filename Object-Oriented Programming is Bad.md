https://www.youtube.com/watch?v=QM1iUe6IofM
Object-Oriented Programming is Bad

OOP is never good. there is no time that we should use it.

classes, performance, aesthetics, and abstraction are NOT the problem with OOP.

procedural programming is not functional programming.

procedural = no explicit association between data types and functions.

imperative = we mutate state whenver we feel like it.

procedural & imperative = default.

procedural & functional = no explicit association between data types and functions, but we don't rely on state.

object-oriented & imperative = segregate state. change different parts of the state from different places.

object-oriented & functional = minimize the amount of state we rely on, but segregate whatever state is left.

encapsulation does not work.

method autocompletion makes OOP feel easy to use.

Java would have been better if it were procedural instead of object-oriented.

OOP helps us think in terms of paragraphs, not sentences, which we like.

object-oriented program can be conceived of as a graph of objects communicating to each other by messages.

we don't interact with the state of an object directly—we interact with it by messages.

messages send copies of state, not references.

to send messages to an object, though, we need a private reference to that object.

thus, if B sends a message to A, A must be a part of B's private state. messages indirectly read and modify state, so B is responsible for A.

if two objects send messages to the same object, then we have shared state, and the whole project of encapsulation has failed.

the coordination between these objects that share state is in practice minimal.

to get rid of shared state our graph of dependencies must be a tree which makes everything extremely annoying and which we don't really do anyway.

OOP = building with walls built before we know its function, so we end up busting holes in walls.

with OOP, we end up making up data types just as containers for behaviors that we want.

OOP tends to force us into useless and confusing abstractions and partitioning of what should all be self-contained.

procedural programming: mostly use plain functions.

1. when in doubt, parameterize instead of using global variables.
2. bundle globals into structs/records/classes.
3. favor pure functions. (not sure what this means.)
4. encapsulate at the level of namespaces/packages/modules. (nor this.)
5. don't be afraid of long functions.

reflections:
I haven't done enough work as a software developer to evaluate this talk critically, but I am aesthetically quite partial to it. Wittgenstein told us about how hard it is to carve reality into discrete, exhaustive chunks. let's give up on that idea, stop worrying so much abotu coming up with perfect abstractions, and write code that does what we want it to do.
I don't know. I need to do some more projects and come back to this when I have experience I can base my opinions on.