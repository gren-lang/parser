# Run the Examples

To try these examples out locally, you can run the following terminal commands:

```bash
git clone https://github.com/gren-lang/parser.git
cd parser/examples
gren make ./Expression.gren
```

After that, open the newly generated index.html file in your favourite browser to see that example.


## Exercises

- Have a user input feed into the `Expression` parser. Show people the results live.
- Expand the `Expression` parser to cover `-` and `/` as well.
- Handle more escape characters in `DoubleQuotedString`. Maybe hexidecimal
escapes like `\x41` and `\x0A` that are possible in JavaScript.