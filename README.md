# es6-utils
You'll find some utils functions.

# How to use ?
Just copy it in your project. The function will be a new array's property

# Doc

* uniq : Returns a uniq flatten array
```javascript
['a','b','c','c'].uniq() => ['a','b','c']
```

* uniqBy : Returns a uniq array by the keys 
```javascript
[{
    a:1, b:2
  },
  {
    a:3, b:4
  },
  {
    a:1,b:2
}].uniqBy('a','b') => [{a:1,b2}, {a:3, b:4}]
```
