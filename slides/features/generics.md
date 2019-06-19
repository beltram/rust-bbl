## Generics
<img src="lib/images/generics.svg" style="height:45vh"/> 

<!--
use std::fmt::{Display, Formatter, Error};
    
trait Eatable {}
struct Lemon {}
impl Eatable for Lemon {}
impl Display for Lemon {
    fn fmt(&self, f: &mut Formatter) -> Result<(), Error> { 
    	write!(f, "🍋") 
  	}
}
    
trait Human<T> where T: Eatable + Display {
    fn eat(food: T) { println!("Miam {}", food) }
}
    
struct Cyril {}
impl Human<Lemon> for Cyril {}-->
