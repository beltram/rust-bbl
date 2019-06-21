## Profiling 
<img src="lib/images/profiling.svg" style="height: 45vh"/>

<!--
//Cargo.toml
[features]
ci = []
[target.'cfg(target_os = "macos")'.dependencies]
openssl = { version = "0.10.23", features = ["vendored"] }

// mod.rs
#[cfg(feature = "ci")]
fn install_additional_stuff() {}

#[cfg(target_os = "macos")]
pub fn install() { brew::install("java") }
    
#[cfg(target_os = "windows")]
pub fn install() { chocolatey::install("java") }
    
#[cfg(target_os = "linux")]
pub fn install() { apt_get::install("java") }
    
#[cfg(unix)]
pub fn symlink() {
    std::os::unix::fs::symlink(from, to).unwrap();
}
    
#[cfg(not(unix))]
pub fn symlink() {
    std::os::windows::fs::symlink_file(from, to).unwrap();
}-->
