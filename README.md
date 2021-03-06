# wrapped-twitter-bootstrap
Apply bootstrap styles inside a wrapper/container only without affecting other/parent containers of the website

```
<div class="non-bs-parent">
<aside></aside>
<div class="bootstrap-inside">
... 
</div>
</div>
```

Let's say you want to apply bootstrap only inside the div.bootstrap-inside container. But default bootstrap sylesheet will impact the entire document.
Having a wrapped boostrap stylesheet will limit the bootstrap styles inside the container.

Requirements
- SCSS compiler
- CSSNano (if you want to minify the CSS)

The How
- Create an .scss file and import your bootstrap scss file by wrapping the import into the class you want to wrap bootstrap into
- Compile SCSS 
- Minify using CSSNano if you want to minify
