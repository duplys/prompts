## Introduction
Collection of (mostly) useful prompts.

## Executing prompts manually

Start with the system prompt, then copy-paste the context and finally the user question.

## Tips and tricks

### Use Markdown
Use Markdown to format the input, especially for headings, subheadings, lists, tables, etc.

### Use personas

Use personas to improve the quality of LLM's output. Examples for personas:

* Software developer
* Quality manager
* Code reviewer
* Project manager
* Customer support engineer

You can also combine personas with specific roles or tasks, for example:

```
# Persona
Experienced Python developer

# Role
Test engineer in an agile software project
```

### Be precise

* Use clear, precise prompts
  * Bad example: `Analyse following code for issues.`
  * Good example: `Analyse the following code for potential cybersecurity vulnerabilities and output a list sorted by risk, in descending order.`
* Suppy context:
  * Bad example: `Review the code.`
  * Good example: `You will be given the code for an HTTP REST service. Pay attention to security aspects. Review the code.`
* Use technical terms:
  * Bad example: `Generate Python code for connecting to a database.`
  * Good example: `Generate Python code for connecting to an SQL database.`