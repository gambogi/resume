
# Dependencies

* Requires `xelatex`
* build command should work with somethink like this:
```json
{
      "name": "xelatex",
      "command": "latexmk",
      "args": [
        "-cd",
        "-xelatex",
        "-pdf",
        "%DOC%"
      ]
    }
```