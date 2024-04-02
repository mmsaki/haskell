# Variables

In Haskell Variables:

- Can contain letters, numbers, underscores, and single quote characters.
- Can use Unicode letters but we stick to ASCII
- Start with lowercase letter by convention `greeting = "Hello"`
- CamelCased `myName = "George"`
- SnakeCased and have underscore `my_snake_case_var = True`
- Can have numbers but most not begin with number `number5 = 5`
- Can have single quote (prime) `two' = 2 + 1`

We join strings with `""<>""<>""` syntax

```hs
greeting = "Hello" <> " " <> "George"
```

## Run Progam

Run progam in `Main.hs`

```sh
# prints "Hello George"
runhaskell Main.hs
```
