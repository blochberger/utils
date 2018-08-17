# Utilities

This repository is a collection of several more or less useful utilities.

Center a list of texts:

```
$ echo -en "foo\n|\nv\nbar" | center
foo
 |
 v
bar
```

Get a median from a list of numbers:

```
$ echo {1..10} | tr ' ' '\n' | median
5
```

