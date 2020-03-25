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

#### Calculate Two People's Individual Ages
```javascript
function getAges(sum,difference){
   if (difference<0||sum<0) return null;
   sum=sum/2
   difference/=2
   if (sum+difference<0||sum-difference<0) return null;
   return [sum+difference,sum-difference]
};
```


#### Be Concise I - The Ternary Operator
```javascript
function describeAge(age) {
  return "You're a(n) " + (age < 13 ? "kid" : age < 18 ? "teenager" : age < 65 ? "adult" : "elderly")
}
```


#### Calculate Two People's Individual Ages
```javascript
function getAges(sum,difference){
   if (difference<0||sum<0) return null;
   sum=sum/2
   difference/=2
   if (sum+difference<0||sum-difference<0) return null;
   return [sum+difference,sum-difference]
};
```

#### Training JS #7: if..else and ternary operator
```javascript
function saleHotdogs(n){
  return n<5 ? n=n*100 : n>=5 && n<10 ? n=n*95 : n=n*90;
}
```

#### Basic Mathematical Operations with Switch
```javascript
function basicOp(operation, value1, value2)
{
  switch(operation){
    case '+': return value1 + value2;
    case '*': return value1 * value2;
    case '-': return value1 - value2;
    case '/': return value1 / value2;
  }
}
```

#### simple calculator Switch case
```javascript
function calculator(a,b,sign){
  if ((typeof a === "number") && (typeof b === "number")) {
    switch (sign) {
    case "+":
      return a + b;
    case "-":
      return a - b;
    case "*":
      return a * b;
    case "/":
      return a / b;
    }
  }
  return "unknown value";
}
```

#### Sum of the first nth term of Series
```javascript
function SeriesSum(n)
{
  let sum = 0;
  for( let i = 0; i < n; i++ ) {
    sum += (1 / (1 + i * 3))
  }
  return sum.toFixed(2)
}
```

#### SBeginner Series #3 Sum of Numbers
```javascript
function getSum(...range) {
  const rangeSort = range.sort((a, b) => a - b)
  if (rangeSort[0] === rangeSort[1]) return rangeSort[0]

  let result = 0
  for (let i = rangeSort[0]; i <= rangeSort[1]; i++) result += i

  return result
}
```

#### Power
   ```javascript
   function numberToPower(number, power){
     let r = 1;
     for (let i=1;i<=power;i++){ r*=number}
   return r
   }
   ```
   
#### Draw stairs
```javascript
function drawStairs(n) {
  let s = '';
  for (let i = 1; i <= n; i++) {
    s += i === n ? 'I' : 'I\n' + ' '.repeat(i)
  }
  return s;
}
```

#### Get Planet Name By ID
```javascript
function getPlanetName(id){
  var name;
  switch(id){
    case 1:
      name = 'Mercury'
    break;
    case 2:
      name = 'Venus'
     break;
    case 3:
      name = 'Earth'
      break;
    case 4:
      name = 'Mars'
       break;
    case 5:
      name = 'Jupiter'
       break;
    case 6:
      name = 'Saturn'
      break;
    case 7:
      name = 'Uranus'
      break;
   default:
      name = 'Neptune'
     }
    return name;
}
```      

#### Filter the number
```javascript
let FilterString = function(value) {
  let string = '';
  for(let i = 0; i < value.length; i++){
  if(!isNaN(value[i])) {string+= value[i];}
    }
return +string;
}
```

#### isReallyNaN
```javascript
const isReallyNaN = (val) => {
    return Number.isNaN(val)
};

//2nd way to solve

function isReallyNaN(val) {
  return val != val;
};
```

#### Invert values
```javascript
function invert(array) {
for ( let i = 0; i < array.length; i++){
 if (array[i] === 0){
 continue;
 } else {
  array[i] = array[i] * -1;
  }
}
   return array ;
}

//2nd way to solve

function invert(array) {
   return array.map(i => 0 - i);
}

```

#### Squares sequence
```javascript
function squares(x, n) {
  var result = [];

  for (var i = 0; i < n; i++) {
    if (i == 0) {
      result.push(x);
    }
    else {
      result.push(Math.pow(result[i - 1], 2));
    }
  }
  return result;
}
```

#### Square Every Digit
```javascript
function squareDigits(num) {
  const result = String(num)
    .split('')
    .map(digit => Math.pow(digit, 2))
    .join('')
  return Number(result)
}
```

#### To square(root) or not to square(root)
```javascript
function squareOrSquareRoot(array) {
  return array.map(el => {
 if( Number.isInteger(Math.sqrt(el))){
  return Math.sqrt(el);
  } else {
  return Math.pow(el, 2); 
  }
  });  
}
```

#### Closest elevator
```javascript
function elevator(left, right, call){
   return  Math.abs(call-left) < Math.abs(call-right) ? 'left' : 'right'
}
```

We would like you to fill out a survey to determine if you are eligible for a test cycle with unique requirements. It looks like you’re a potential match for a paid project at uTest. The project requires some unique details that we haven’t profiled for in the past so we need som


