## JavaScript // But how it's gonna be true?

```
0.1 + 0.2 === 0.3 // FALSE 
{a:1} === {a:1} // FALSE 
Math.max() > Math.min() // FALSE

!!("some string".indexOf("NuNu")) // TRUE
```

## Was macht folgende RegExp: 
```
/^.*?(\..{1,5})?$/i
```

## Was ist hier zu erwarten?

```
var a = null
var fn = (a) => typeof a === 'object' ? a || 'nothing' : 'match'
console.log(
	fn(), 
	fn(a)
)
```

```
var a = {x: 0, y: 0}
console.log(((a) => { a.x += 10; return a.y + a.x })(a), a)
```

```
var a = [1,2,3];
console.log(
	((a) => a.push(...a))(a), 
	a.reduce((a,c) => a + c, 0)
)
```

## JS // Frage
- Wie kann man feststellen, dass eine Variable einen Array erhält?

## JS Error // Bitte erklären
```
Uncaught TypeError: Cannot read property 'b' of null
```

