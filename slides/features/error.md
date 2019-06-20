## Error handling
<img src="lib/images/error.svg" style="height:45vh"/> 

<!--use std::io::{Error, ErrorKind, Result};
use std::path::PathBuf;
    
fn kube_config() -> Result<String> {
    let gradle_config = read_file(PathBuf::from("~/.gradle/gradle.properties"));
    gradle_config
        .map(|config| println!("My kubectl config {}", config));
    let bash_profile = read_file(PathBuf::from("~/.bash_profile"));
    if let Ok(profile) = bash_profile {
        println!("My bash profile {}", profile)
    }
    // ? let me return Ok if read_file succeeds, Err otherwise
    // Only works if my method returns a Result<>
    let kube_config = read_file(PathBuf::from("~/.kube/config"))?;
    Ok(kube_config)
}
    
fn read_file(path: PathBuf) -> Result<String> {
    if path.is_absolute() { Ok("apiVersion: v1".to_string()) } else {
        Err(Error::new(ErrorKind::NotFound, "I only read absolute files"))
    }
}-->
