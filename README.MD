## Replacements in exported Twine file

At end of head, insert:
```
<link rel="stylesheet" type="text/css" href="./css/fonts.css"/>
<link rel="stylesheet" type="text/css" href="./css/cyoa48.css">
```

In Twine engine code JS

replace:
```
<tw-icon tabindex=0 class="undo" title="Undo">&#8630;</tw-icon>
```
and
```
<tw-icon tabindex=0 class="redo" title="Redo">&#8631;</tw-icon>
```

with:
```
<tw-icon tabindex=0 class="undo" title="Undo"><img src="./img/b-undo.png"></tw-icon>
```
and
```
<tw-icon tabindex=0 class="redo" title="Redo"><img src="./img/b-redo.png"></tw-icon>
```