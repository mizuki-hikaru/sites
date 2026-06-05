# Styledown

Styledown is an extension to Markdown that adds clean syntax for styled
container blocks and includes a lightweight web server for serving rendered
content.

For example:

```markdown
.center: # A *markdown* heading

.center.card:
    ## A *markdown* subheading

    .buttons.blue:
        [A link that looks like a button](/example)
        [Another link](/example)
```

.buttons:
    [Style Showcase](/projects/styledown/showcase)

## Usage

```bash
pip install styledown
styledown -h # Usage instructions
```

### --domains mode

If the `--domains` flag is passed to the script, you can put your code in:

 - `./src/first.example.com/`
 - `./src/second.example.com/`

to serve different sites.
