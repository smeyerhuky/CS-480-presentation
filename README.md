# CS-480-presentation
A presentation given to CS-480 at JMU

## AI for Engineers: From Statistics to Workflow

A presentation on understanding and effectively using LLMs for software engineering tasks.

## Overview

This presentation covers:

- **How LLMs Work** — The "next token" prediction model and why context matters
- **Prompt Engineering** — Structured prompts, XML tags, chain-of-thought, and output formatting
- **Context & RAG** — How retrieval-augmented generation grounds responses in your data
- **Practical Patterns** — Code review workflows and multi-agent coordination

## Meta: Built With Its Own Principles

`index.md` was written and coded using a **human-in-the-loop process** together with the AI workflow tools discussed in the presentation itself. The structured prompting techniques, iterative refinement, and context engineering patterns covered in the slides were applied to generate this Marp presentation — demonstrating that these principles work across domains, not just code review.

LLMs are great at generating text output, so this presentation was written with AI outputting 'text' as marp syntax markdown. Iterate, validate, rinse, repeat... PUBLISH!

## Building the Presentation

This is a [Marp](https://marp.app/) presentation. Convert to HTML with:

```bash
npx @marp-team/marp-cli index.md -o index.html
```

Other formats:
```bash
npx @marp-team/marp-cli index.md --pdf      # PDF export
npx @marp-team/marp-cli index.md --pptx     # PowerPoint
npx @marp-team/marp-cli index.md --preview  # Live preview in browser
```

## Author

**Shuky Meyer**
Staff Software Engineer @ AuditBoard
