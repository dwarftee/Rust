# rust
this is a rust tutorial


variables
```rust
#variables in rust are really cool
fn main() {
  let x = 6;
  #x is uneditable
  #if we tried to do → x = 8; it would give an error
  
  let mut y = 5;
  #adding mut means we can now edit the variable
  y = 89; #this would work
}
```

printing in rust

without printing you wouldn't be able to print the variables!

```rust
fn main() {
    println!("hello world!");
    #println! is the function name and it prints to the terminal
    #output: hello
    let x = 9;
    println!("x = {}",x)
    #adding "{}",x tells the machine to print x
}
```

