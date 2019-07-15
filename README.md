# JS-Programming

####
``` 
let a = 12,
b = 3;
[a,b] = [b,a];
console.log([a,b]); 
```
O/p: [3,12] Swap the values inside a and b, without using extra variables.

### 2
``` 
var point = [1,2],
segment = [point, [5,5]];
traingle = [...segment,[1,8]];
console.log(traingle);
```
O/p: [[1,2],[5,5],[1,8]]


### Rest parameters:
Rest is a new way for functions to handle an arbitrary number of parameters.

``` 
function mystery(...params){
    return params;
}
let a = mystery(1,12,4);
console.log(a);
```
O/p : [1,12,4]

