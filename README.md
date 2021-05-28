# HTML Notes

## Sources for learning
* https://ru.code-basics.com/languages/html/ (practical tasks)

## Examples

### Label and checkbox
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