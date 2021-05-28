# HTML Notes

## Sources for learning
* https://ru.code-basics.com/languages/html/ (practical tasks)

## Examples

### How to use label and input checkbox
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

### How to use input checkbox
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

### How to use label and input radio
Version #1 (relation by id)
```
<form>
    <input id="radio_yes" type="radio" name="question">
    <label for="radio_yes">Yes</label>
    
    <input id="radio_no" type="radio" name="question">
    <label for="radio_no">No</label>
</form>
```
Version #2 (relation through nesting)
```
<form>
    <label>
        <input type="radio" name="question">
        Yes
    </label>
    <label>
        <input type="radio" name="question">
        No
    </label>
</form>
```

### How to use input radio
```
<form>
    <label>
        <input type="radio" name="question" value="yes">
        Yes
    </label>
    <label>
        <input type="radio" name="question" value="no">
        No
    </label>
</form>
```
Attribute "name" is used to make the browser understand the relationship between radios. Without "name" attribute it would be possible to choose all radios.
Attribute "value" is used to find out which particular radio was selected.
