## Borrowing 
#### Introducing move
<img src="lib/images/move.svg" style="height: 20vh"/>

```console
let s1: String = String::from("hello");
    -- move occurs because `s1` has type `std::string::String`, 
    which does not implement the `Copy` trait
let s2: String = s1;
                 -- value moved here
println!("{:?} world", s1);
                       ^^ value borrowed here after move
```


<!--
fn do_stuff() {
    let s1: String = String::from("hello");
    let s2: String = s1;
    println!("{:?} world", s1);
}-->
