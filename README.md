# Roslyn `log` Keyword

An experiment to see if I'll be able to bend Roslyn to introduce a new keyword `log` that works like this:

```cs
void Main() {
  log "The application has started";
  log $"The startup time is {DateTime.Now}";
}
```

- https://mattwarren.org/2017/05/19/Adding-a-new-Bytecode-Instruction-to-the-CLR/
- https://marcinjuraszek.com/2017/05/adding-matt-operator-to-roslyn-part-1.html
- https://marcinjuraszek.com/2017/05/adding-matt-operator-to-roslyn-part-2.html
- https://marcinjuraszek.com/2017/06/adding-matt-operator-to-roslyn-part-3.html
- https://github.com/dotnet/roslyn/issues/27841
