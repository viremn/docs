---
layout: relation
title:  'compound:prt'
shortdef : 'phrasal verb particle'
udver: '2'
---

The phrasal verb particle relation identifies an idiomatic phrasal verb, and
holds between the verb and its particle (tagged as [ADP]()). It is a subtype of the
[compound]() relation.

~~~ sdparse
They shut down the station
compound:prt(shut, down)
~~~

~~~ sdparse
They shut the station down
compound:prt(shut, down)
~~~

This relation excludes literal/directional uses of prepositions/particles, such as _up_, _down_, _in_, _out_, etc.
These would typically become an ADV with the relation [advmod]():

~~~ sdparse
The house was on fire and they ran out screaming.
advmod(ran, out)
~~~

<!-- Interlanguage links updated Ne 5. května 2024, 18:20:56 CEST -->
