# HTML Notes

## Sources for learning
* https://ru.code-basics.com/languages/html/ (practical tasks)

## Examples

### How to use label and checkbox
Version #1 (relation by id)
```
<form>
    <input id="html" type="checkbox">
    <label for="html">I want to know HTML well</label>
</form>
```
Version #2 (relation through nesting)
```
<form>
    <label>
        <input type="checkbox">
        I want to know HTML well
    </label>
</form>
```

### How to use checkbox
```
<form>
    <label>
        <input type="checkbox" name="languages" value="HTML">
        I want to learn HTML
    </label>
    <label>
        <input type="checkbox" name="languages" value="CSS">
        I want to learn CSS
    </label>
    <label>
        <input type="checkbox" name="languages" value="JS">
        I want to learn JS
    </label>
</form>
```
Attribute "name" is used to separate our checkboxes group among others and attribute "value" is used to find out which checkboxes were selected.
