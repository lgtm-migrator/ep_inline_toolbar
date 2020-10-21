# Inline toolbar for Etherpad

A simple way to add the toolbar buttons inline on the editor.  These buttons only appear when you highlight text

# Usage
Buttons must be added to settings.json in teh toolbar section as a section called ``inline``

For example..

```
  "toolbar": {
    "left": [
      ["bold", "italic", "underline", "strikethrough"],
      ["orderedlist", "unorderedlist", "indent", "outdent"],
      ["undo", "redo"],
      ["clearauthorship"]
    ],
    "right": [
      ["importexport", "timeslider", "savedrevision"],
      ["settings", "embed"],
      ["showusers"]
    ],
    "timeslider": [
      ["timeslider_export", "timeslider_returnToPad"]
    ],
    "inline":[["bold"]]
  },
```

The above example will make bold show up inline
