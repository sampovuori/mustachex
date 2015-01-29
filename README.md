# Mustache for Elixir

## Usage

```elixir
Mustachex.render("Hello, {{planet}}", [planet: "World!"])
#=> "Hello, World!"
Mustachex.render("Hello, {{planet}}", %{planet: "World!"})
```

## Links

* [mustache(5) -- Logic-less templates.](http://mustache.github.io/mustache.5.html)
