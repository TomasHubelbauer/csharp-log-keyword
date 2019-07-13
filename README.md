# C# `log` keyword

Me trying to see if there is a way to bend Roslyn to introduce a new keyword `log` that works like this:

```cs
void Main() {
  log "The application has started";
  log $"The startup time is {DateTime.Now}";
}
```

## Links

- https://marcinjuraszek.com/2017/05/adding-matt-operator-to-roslyn-part-1.html
- https://marcinjuraszek.com/2017/05/adding-matt-operator-to-roslyn-part-2.html
- https://marcinjuraszek.com/2017/06/adding-matt-operator-to-roslyn-part-3.html
