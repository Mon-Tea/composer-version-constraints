# composer version constraints
How version constraints work with composer.


## Examples - Caret vs Tilde

```
^1.2.3 | >= 1.2.3 && < 2.0.0
~1.2.3 | >= 1.2.3 && < 1.3.0

^1.2 | >= 1.2.0 && < 2.0.0
~1.2 | >= 1.2.0 && < 2.0.0

^1 | >= 1.0.0 && < 2.0.0
~1 | >= 1.0.0 && < 2.0.0

^0.4 | >= 0.4.0 && < 0.5.0
~0.4 | >= 0.4.0 && < 1.0.0
```
