# Why You should build your own components

## Simple is not the same as easy

I know, I know. I keep going on about this is not that. But words have meanings and those meanings matter. They structure our brains and create boundaries on how we think.

It is _easy_ to use Redux. But it isn't very simple in the long run. Because you are offloading the cognitive process of how your application state is managed, you lose the ability to control it. Everything becomes a global variable, stored in a giant hashtable.

It is _easy_ to use Carbon Components, until your boss wants you to implement scroll detection on that modal component, and the property you need to access is not available to you and the documentation is awful and the code is written in TypeScript and is extremely abstract and hard to follow.

It is _easy_ to just use MongoDB because all the tutorials for NodeJS seem to be using it, but it is not simple to have data whos schema is constantly changing over time while your code is also changing over time, until you find that your code no longer works with the data. It is no longer simple to return a large amount of relational data for that shiny new report your boss wants you to generate.
