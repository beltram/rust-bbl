## Null safety
<img src="lib/images/null-safe.svg" style="height: 40vh"/>

<!--
fn life() {
    let mut promoted: Option<bool> = Some(true);
    let promoted = promoted
        .map(|is_promoted| "Say 💩")
        .filter(|&said| said == "🙏")
        .and_then(|said| if said == "🙏" { Some("💰") } else { None })
        .or_else(|| Some("🔍 another 🏢"));
    if let Some(i_am_promoted) = promoted {
        println!("Hourra")
    }
}-->
