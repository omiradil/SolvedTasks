# SolvedTasks on Codewars
#### Super Duper Easy

```javascript
function problem(x){
  if (typeof x === 'string') return "Error";
  if (typeof x === 'number') return 50 * x + 6;
}
```
#### Sum of angles
```javascript
function angle(n) { return a = ( n - 2 ) * 180 }
```

#### Sum The Strings
```javascript
function sumStr(a,b) {
  return String(Number(a)+Number(b));
}
```

#### Century From Year
--Introduction--
The first century spans from the year 1 up to and including the year 100, 
The second - from the year 101 up to and including the year 200, etc.

--Task :--
Given a year, return the century it is in.
```javascript
function century(year) {
  return Math.ceil ( year / 100);
}
```

#### Return Negative
```javascript
function makeNegative(num){
return -Math.abs(num);
}
```