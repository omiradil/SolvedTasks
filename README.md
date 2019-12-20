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

#### What's the real floor?
```javascript
function getRealFloor(n) {
  return n > 13 ? n - 2 : n > 0 ? n - 1 : n;
}
```


#### Rock Paper Scissors!
```javascript
const rps = (p1, p2) => {
 if (p1 === p2){ return 'Draw!'}
 if (p1 === 'rock' &&  p2 === 'scissors'){ return 'Player 1 won!' }
 if (p1 === 'scissors' &&  p2 === 'paper'){ return 'Player 1 won!' }
 if (p1 === 'paper' &&  p2 === 'rock'){ return 'Player 1 won!' }
  
 if (p1 === 'scissors' &&  p2 === 'rock'){ return 'Player 2 won!' }   
 if (p1 === 'paper' &&  p2 === 'scissors'){ return 'Player 2 won!' } 
 if (p1 === 'rock' &&  p2 === 'paper'){ return 'Player 2 won!' } 
};
```

