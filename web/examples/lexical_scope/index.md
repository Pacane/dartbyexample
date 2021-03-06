<!--
title: Lexical Scope
-->

Dart is a lexically scoped language.
Loops that declare their variable will have a new version of that variable for each iteration.

<pre>
<code class="hljs dart">{{> lexical_scope.dart}}
</code>
</pre>

```bash
$ dart lexical_scope.dart
0
1
2
```

Compared to javascript:

<pre>
<code class="hljs dart">{{> lexical_scope.js}}
</code>
</pre>

```bash
$ node lexical_scope.js
3
3
3
```
