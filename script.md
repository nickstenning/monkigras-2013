Imagine that you are a violin maker. You make the most beautiful, resonant
instruments -- the best sounding violins in the world.

Now imagine that all the tradesmen you know suddenly disappear. The timber
merchant you buy your wood from: gone. The wire maker you buy wire from to
make your strings. The man down the road who sells your varnish. All of them
are no more. What's more, you can't find anyone else who makes these things.
The entire supply chain for your violin making business is gone.

Consider for a moment all the skills you'd need to acquire before you could
continue making violins. For the metal, you'd need to know how to make wire
from metal, metal from ore, how to get ore from a mine. You'd need the skills
of a woodcarver, a haulier, a lumberjack. But if the lumberjack uses an axe,
you'd also need to know how to make and sharpen an axe head, and how to hang
the head properly on the axe haft.

The regress isn't endless, but it goes a long way back, and it would take
several lifetimes to acquire all the necessary skills. And even if you managed
it, how much time would you have left to spend obsessing over what really
mattered to you: the timbre and tone of your handmade instruments?

---------------------------------------------------------------------------

So, you're thinking, what on earth has this got to do with Monkigras, or with
Scaling Craft? When does this session end? "I came here to learn about cool
new programming languages and Web Scale NoSQL databases!" Well, don't fall
asleep just yet, as I'm here to tell you about the as-yet unexplored link
between JavaScript and Quantum Mechanics.

If you write JavaScript, you probably know something about the DOM, which is
part of a browser, which runs on an Operating System, which has its heart a
kernel, which is almost certainly written in a programming language called C,
and compiled with a C compiler: GCC, or the IBM C compiler. That C compiler
needs a detailed understanding of the machine code understood by the
particular class of processor in your computer. The machine code itself
triggers the action of thousands of electronic components inside the
processor. Each of these components may include hundreds of thousands of
transistors. To understand a transistor you need a decent understanding of
semiconductor physics, which in turn requires a not inconsiderable knowledge
of Quantum Mechanics.

By now, of course, you see the parallel with our violin maker.

---------------------------------------------------------------------------

Consider for a minute that in both cases -- the violin and the programming
language -- thousands of lifetimes have been expended developing the stack of
technologies on which their existence rests.

How do we ever get anything done?

The answer is Black Box Abstraction. You've probably heard Black Box
Abstraction called all kinds of names: encapsulation, the separation of
interface from implementation, complexity hiding. It is the process of
wrapping up complex systems in a shiny box that hides most of the details of
their construction, and hopefully idealises their behaviour.

Consider your car. Some of you might know all about cams and cranks and
ignition timers, but most of you probably don't. You know that you get in the
car, turn the key, and can make it go forward and backward, left and right.

The aim of a Black Box Abstraction is to make it possible for a user to reason
about a system of unreasonable complexity, and I argue that it is *the*
central paradigm for technological advance. As soon as a technology or process
can be packaged in a black box through which it exposes a small but useful
fraction of its inner complexity, its users can concentrate on *using* it,
rather than trying to understand it.

---------------------------------------------------------------------------

So, if you are, like me, trying to work out how to build application
deployment and configuration tools -- a platform on which other peoples'
applications run, the most important thing is to expose some useful behaviour
while hiding underlying complexity. Kenneth Reitz, a Python developer, says:

> The user API is all that matters.
> Everything else is secondary.

Or, as we might say at GDS:

> Start with needs.
