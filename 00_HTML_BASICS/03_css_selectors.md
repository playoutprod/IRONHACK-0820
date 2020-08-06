# CSS selectors

To apply css on html, we use css selectors to target html nodes.

## Main selectors

---

### node name

#### css
```
  div {
    width:50px;
    height:50px;
    background-color:#000;
  }
```

#### html
```
<div></div>
```

#### result
<div id="exemple1">
  <style>#exemple1 div {width:50px;height:50px;background-color:#000;}</style>
  <div></div>
</div>

---

### node class

#### css
```
  .myClass {
    background-color:#000;
  }
```

#### html
```
<div class="myClass"></div>
```


### node class

#### css
```
  .myClass {
    width:150px;
    height:1em;
    background-color:#00FF00;
  }
```

#### html
```
<div class="myClass"></div>
```

#### result
<div id="exemple2">
  <style>.myClass {
    width:150px;
    height:1em;
    background-color:#00FF00;
  }</style>
  <div class="myClass"></div>
</div>

---

### node id

#### css
```
  #myId {
    width:2em;
    height:80px;
    background-color:#0000FF;
  }
```

#### html
```
<div id="myId"></div>
```

#### result
<div id="exemple3">
  <style>#myId {
    width:2em;
    height:80px;
    background-color:#0000FF;
  }</style>
  <div id="myId"></div>
</div>
