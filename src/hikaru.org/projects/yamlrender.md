---
description: Turn a YAML file and Jinja2 template into HTML or PDF.
---

# yamlrender

yamlrender takes a YAML file and a Jinja2 template and renders a HTML or PDF
file, populating the variables in the Jinja2 template with data from your YAML
file.

The source code is available on [GitHub](https://github.com/mizuki-hikaru/yamlrender).

## Installation

    pip install yamlrender

## Usage

    yamlrender input.yaml template.html output.html
    yamlrender input.yaml template.html output.pdf

Or in Python, you can use it like this:

    from yamlrender import yamlrender

    yamlrender("input.yaml", "template.html", "output.html")
    yamlrender("input.yaml", "template.html", "output.pdf")

## Markdown support

You can use markdown in your YAML file and render it like this in the template:

    {{ some_markdown_variable | markdown }}
