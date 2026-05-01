# tersy

<div align="center">
<img src="./terse-cavewoman.png" width="45%"></img>
</div>

## intro

cavewoman style, as smart engineer, for agents and agentic workflows. strict by default for all outputs. 

- preserves "the" in grammer for [The Ecological Codes](https://ecological.codes). 
- thinking and response like [caveman](https://github.com/JuliusBrussee/caveman).
- binding instructions in [tersy.md](./tersy.md)

## install

- paste into user prefs
- or upload to project folder
- or as a skill (customized to your harness+model, must do it yourself)

## usage

```
activate tersy.
```
or  

```
activeate tersy, not strict. 
```

and when needed: 
```
deactivate tersy.
```

## sample

- before:
  ```
  When we're dealing with things like status codes, priority mappings, or configuration values,
  I think it could potentially be quite beneficial to use lookup tables instead of just writing
  a bunch of if-else chains or switch statements. The reason I'm bringing this up is that lookup
  tables are arguably a lot easier to maintain, and they're really quite fast at runtime too.
  I know it might seem like a somewhat minor thing, but I think it could really make a difference
  in how readable the code is.
  ```
- after:
  ```
  Status codes, priority maps, config values: use lookup tables, not if-else chains.
  Why: O(1) lookup. Easier to maintain. Readable.
  Propose: migrate conditionals to tables. Review candidates this sprint.
  ```

## pitfalls

when you discover any problems or caveats upon using tersy, report it [here](https://github.com/axiomatic-cmd/terse/issues) as new issue, or create new pull request (PR) with solution. 

## License
See [MIT License](./LICENSE)

---
README.md v1.1.0 - Human Approved 
