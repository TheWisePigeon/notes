# 29, Aug 2023
Started learing Rust seriously. And wrote a guessing game.
## Things I want to remember
```rs
//Reading from user input
//You want to use io::stdin().read_line()
//Generating random numbers using the rand crate
use std::io;
use rand::prelute::*;

func main(){
    let mut input;
    io::stdin().read_line(&mut input).unwrap();
    let mut rng = rand::thread_rng();
    let random_num = rand::gen_range(0..100);
}
```
