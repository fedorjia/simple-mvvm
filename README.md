# usage

> simple mvvm implements like vue

html
```
<div id="app">
    <input type="text" v-model="str">
    <br/>
    <div>{{str}}</div>
</div>    

```

js
```
var vm = new MVVM({
    el: '#app',
    data: {
        str: 'hello '
    }
});
```