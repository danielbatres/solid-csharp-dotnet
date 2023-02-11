# Open/closed principle

This principle is credited to Bertrand Meyer but Robert Martin exposed it in his book Clean Code.

A component must be open to extensions and closed to changes.
Astract types and multiple implementations must be used to achieve this.

## The C# case

Does not support multi-inheritance

```cs
public class SubClass: MainClass
```

Supports multiple interface implementations

```cs
public DataAccess : IDataBase, IQuery, IDelete
```