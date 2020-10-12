# Why You should build your own components

## Summary

For a long time now, it has been easy to import code that will allow
you to _begin_ to build your software faster. You just run npm
install, and suddenly you are moving forward at light speed, creating
functions, components, features, and eventually, a _horrible ball of
mud_.

That package you installed with _such apparent ease_ is the culprit.
It is _easy_ to install it and use it _initially_. However, _easy is
not the same as simple_, and _simple is the enemy of complexity_. Easy
is the ally of complexity.

That package was _not designed for you_; it wasn't built with your
project or code in mind. There is no way the authors _could have
guessed_ how you will end up using it. And without spending a lot of
time reading the documentation (if it exists at all), you don't
_really understand_ how it works or how to extend it to do what you
ultimately want.

Over time, npm install will make your software _brittle_ and _hard to
modify_. It will make your software _less secure_, with more attack
vectors available for exploitation, and it will cause your build,
testing, and deployment processes to _take longer and longer_.

In this talk, I will explain why this happens, how to avoid it, and
quite possibly the best part of all, how _you can become a much better
programmer_ by _tackling complexity_ through a _consistent practice_
of _eschewing the easy for the simple_.
