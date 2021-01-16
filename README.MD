### tag-template

Dirty HTML templating in template literals, occupies global namespace with the $_ prefix by building from a dictionary of tags and classes.

e.g.

```
<span class="code-block"> This is some code! </span>
```

becomes

```
${$_scb} This is some code! ${$_ss}
```