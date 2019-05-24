# Update Shortcuts

Use this shortcut to fetch the latest versions of other shortcuts.  By default, this shortcut will read the information in this repo's [meta.json](../meta.json) file to determine what shortcuts to update (this can be changed during import).

It is also possible to share another json file to this shortcut and it will be read as input.  The json file must have the following format:

```json
{
    "name of shortcut": {
        "url": "link to shortcut"
    }
}
```
