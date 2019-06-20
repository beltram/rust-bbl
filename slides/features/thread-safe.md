## Fearless concurrency 
<img src="lib/images/thread-safe.svg" style="height: 45vh"/>

<!--
use std::{sync::{Arc, Mutex}, thread};
use rayon::prelude::*;
fn send_chunks() {
    let movie = "👽☝️🚴";
    let movie_rc = Arc::new(movie).clone();
    thread::spawn(move || { println!("Send {}", movie_rc) });
    thread::spawn(move || { println!("Send {}", movie) });
    let mut comic = Arc::new(Mutex::new("🌕👦"));
    let comic_mutex = comic.clone();
    thread::spawn(move || {
        comic_mutex.lock()
            .map(|ref mut com| com.replace("👦", "🐵"))
            .map_err(|e| "Failed acquiring 🔒");
    });
    vec!["🚀👨", "👩☁️💎"].par_iter()
        .for_each(|song| println!("Listen {}", song));
}-->
