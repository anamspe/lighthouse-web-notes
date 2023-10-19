## Objects

Complex data structure that allows you to have one single name with multiple properties.

### Objects:

* Contain key-value pair; each key maps to a value
* Contain keys which are always **`strings`** (or symbols, but it's less common)
* Have unique keys; the same key cannot appear twice in an object
* Have their keys point to values which can be of any type

#### Revisiting important rules

1. Keys are always strings
2. Each key is unique (can only occur once in the object)
3. Each key is associated with exactly one value. _(Note that technically, an array or another object would count as "one value" here, even though they contain other values.)_  




``` text
In Javascript, all values which are not Objects are collectively referred to as primitives:

- undefined
- null
- boolean (true or false)
- string
- number
- symbol
```

#
Method: function defined in an object;
#
`this.` to refer to elements inside an object