# C# `log` keyword

Me trying to see if there is a way to bend Roslyn to introduce a new keyword `log` that works like this:

```csharp
int ClamToPositive(int positiveOrNegative) {
  log $"Input ${positiveOrNegative}";
  return positiveOrNegative >= 0 ? positiveOrNegative : 0;
}
```
