---
layout: relation
title:  'root'
shortdef: 'root'
udver: '2'
---

The `root` grammatical relation points to the root of the sentence. A fake node "ROOT" is used as the governor. The ROOT node is indexed with "0", since the indexation of real words in the sentence starts at 1.

~~~ sdparse
ROOT I love French fries .
root(ROOT, love)
~~~

~~~ sdparse
ROOT Bill is an honest man
root(ROOT, man)
~~~
<!-- Interlanguage links updated So kvě 14 19:04:15 CEST 2022 -->
