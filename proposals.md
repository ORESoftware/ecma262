Just looking for this simple method on Array.prototype


```
Array.prototype.add.= function(val){
   this.push(val); // or whatever is internal
   return val;
};
```

so that instead of this:

```js
  const col = [];
  ret.push(col);
```

we can do:

```js
  const col = ret.add([]);
```

would be nice
        



