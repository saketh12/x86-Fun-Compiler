# x86-Fun-Compiler
'Fun' is a simple functional programming language similar to Python. It has support for conditionals, types, functions, recursion, and arrays. This compiler will compile 'Fun' code to x86 assembly and run it to produce the desired output. Below are some examples:

## Conditionals
```
integer num = 5
if (n % 5 == 0){
  print("This number is divisible by 5")
} else{
  print("This number is not divisible by 5")
}
```

## Loops and Arrays
```
integer n = 5
for(integer i = 0; i<=n; i=i+1){
  print(i)
}

integer t = 0
while(t < n){
  print(t)
  t = t + 1
}

integer[10] array
for(integer k = 0; k<=n; k=k+1){
  array[k] = k
}
```

## Functions and Recursion
```
fun fibonacci(n){
  if(n <= 0){
    return 0
  }
  else{
    if(n <= 0){
      return 0
    }
    else{
      return fibonacci(n - 1) + fibonacci(n - 2)    
    }
  }
}

integer n = 10
print(fibonacci(n))
```
