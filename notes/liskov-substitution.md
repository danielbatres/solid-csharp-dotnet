# Liskov substitution principle

It's cretited to Barbara Liskov and Robert Martin expounded on it in his book Clean Code.

Objects within a program must be able to be replaced by subtypes of the program without altering the logic or operation.

```
Let Φ(x) be a testable property about objects x of type T.

Then Φ(y) must be true for objects y of type S, where S is a subtype of T.
```
