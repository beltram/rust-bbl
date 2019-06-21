## Standard traits
* Copy, Clone: I can be deep copied [Copy!=Clone](https://doc.rust-lang.org/std/marker/trait.Copy.html#whats-the-difference-between-copy-and-clone)
* Display: I can be printed in println!("{}", dis) without formatter like {:?}
* (De)Serializable: From serde (marshalling)
* Debug: Destructure structs fields while printed
* Send: Type can be sent to another thread (automatic derived, no impl)
* Sync: Type can be shared between threads (automatic derived, no impl)