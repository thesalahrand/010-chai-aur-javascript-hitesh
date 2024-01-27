**01. Will this piece of code cause any error?**

```javascript
b = 1

{
  var b = 10
}

console.log(b)
```

**Ans:** Explicitly not declaring let/const is a bad practice but it will not cause any error. The variable **b** will be getting a global scope. Hence, the output is **10**.

**02. What will be the output?**

```javascript
console.log(typeof null)
console.log(typeof undefined)
```

**Ans:**

```javascript
object
undefined
```

**03. What will be the output?**

```javascript
console.log(Number('1a'))
console.log(typeof NaN)
```

**Ans:**

```javascript
NaN
number
```

**04. What will be the output?**

```javascript
console.log('1' + 2 + 2)
console.log(1 + 2 + '2')
```

**Ans:**

```javascript
122
32
```

**05. What will be the output?**

```javascript
console.log(null > 0)
console.log(null == 0)
console.log(null >= 0)
```

**Ans:** An equality check and comparisons work differently. Comparisons convert **null** to **number**.

```javascript
false
false
true
```

**06. What will be the output?**

```javascript
console.log(undefined > 0)
console.log(undefined == 0)
console.log(undefined < 0)
```

**Ans:** An equality check and comparisons work differently. Comparisons convert **undefined** to **NaN**.

```javascript
false
false
false
```

**07. Basic difference between primitive and non-primitive?**

**Ans:** Primitive types store the actual data value in the allocated memory space. Non-primitive types store references (memory addresses) to the location where the data is stored.
