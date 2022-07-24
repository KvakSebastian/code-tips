# code-tips
## Angular
- ### Instead of calculating value in component like this
```html
<p>calculate(value)</p>
```
USE PURE PIPE
```html
<p>value | calculate</p>
```
- ### In thisway you will get invoking of valculation only if getting new value or value changes(in ingular memoization)
