# usage

> simple mvvm implements like vue

html
```
<div id="app">
    <input type="text" v-model="someStr">
</div>    

```

js
```
var vm = new MVVM({
    el: '#app',
    data: {
        someStr: 'hello '
    }
});
```