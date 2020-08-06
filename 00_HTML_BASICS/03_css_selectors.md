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
<div style="width:50px;height:50px;background-color:#000;"></div>

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
<div class="myClass" style="width:150px;height:1em;background-color:#00FF00;"></div>

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
<div id="myId" style="width:2em;height:80px;background-color:#0000FF;"></div>
