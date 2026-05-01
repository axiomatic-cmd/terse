# tersy

<div align="center">
<img src="./terse-cavewoman.png" width="45%"></img>
</div>

## intro

"cavewoman style, as smart engineer" for agents and agentic workflows. strict by default for all outputs. 

- preserves "the" in grammar for names and labels like [The Ecological Codes](https://ecological.codes). 
- thinking and response like [caveman](https://github.com/JuliusBrussee/caveman).
- binding instructions in [tersy.md](./tersy.md) (not gendered as persona of any kind).

## install

- paste into user prefs
- or upload to project folder
- or as a skill customized to your harness+model (try doing it yourself with [safe-skill-creator](https://github.com/ecological-codes/safe-skill-creator))

## usage

```
activate tersy.
```
or  

```
activate tersy, not strict. 
```

and when needed: 
```
deactivate tersy.
```

**Hint:** use strict for agent pipelines, terminal, agentic reasoning chains; `not strict` when a human outside the workflow needs to read the output.

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

## known issues / compatibility

- **in most platforms:** aggressive sentence compression that works well in agent pipelines or terminal output can appear as curt or incomplete to non-technical stakeholders reading prose in a chat thread.
  - **practical solution:** use `activate tersy, not strict.`
  - the `not strict` parameter allows agent to apply judgment per context, instead of universally compressing token usage. 
  - **also relevant:** use the not strict mode, for document-generation workflows (docx, pdf, reports) where output artifacts need to be readable by someone unfamiliar with the tersy compression contract.

## contributing

when you discover any problems or caveats upon using tersy, report each [here](https://github.com/axiomatic-cmd/tersy/issues) as new issue, or create new pull request (PR) with viable solution and new feature. 

## License
See [MIT License](./LICENSE)

---
README.md v1.2.1 - Human Approved 
