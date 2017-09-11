# How to conduct effective code reviews without making people want to stab you

The aim of this document is to define a set of guidelines to use when conducting
_effective_ code reviews. A code review is effective when it:

* is completed in a reasonable amount of time
* doesn't require numerous feedback round-trips
* produces good-quality code
* doesn't hurt the author, the reviewer, nor anyone else
* leaves the author, the reviewer, or both, knowing more than when they started

This document will not focus on the technical requirements of good quality code,
which have been discussed at length in general and for specific languages
(see [Suggested Reading](#suggested-reading)). It will instead describe some
common biases and anti-patterns which create a cognitive dissonance between
the author and the reviewer, leading to reviews which are long, hostile,
and _ineffective_.

## DON'T

### Reiterate requests ad nauseam

Suppose you don't like a specific pattern / convention / choice repeated
multiple times in a Pull Request. There is no need to leave the same comment
multiple times, particularly if you're just going to copy+paste the comment
all over the diff. The perceived intention is to highlight just how many times
the author made an alleged mistake. This is disrespectful and patronizing.
Instead, leave the comment once and add "applies to all other instances in this
PR" or "you get the gist". The author will appreciate that you trust them
with finding and correcting other instances of the mistake themselves.

# Suggested Reading

* Clean Code: A Handbook of Agile Software Craftsmanship (Robert C. Martin, 2008)
