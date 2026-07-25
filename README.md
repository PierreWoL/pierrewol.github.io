# Zhenyu Wu

Personal research website for **Zhenyu Wu**, a final-year Computer Science PhD
candidate working on large language models, structured data, schema and taxonomy
inference, knowledge graphs, and agentic data systems.

The site is built with [al-folio](https://github.com/alshedivat/al-folio) and
published at [pierrewol.github.io](https://pierrewol.github.io).

## Local validation

```bash
npm ci
npm run lint:prettier
bundle exec al-folio upgrade audit --no-fail
bundle exec jekyll build
```
