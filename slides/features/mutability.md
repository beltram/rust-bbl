## Immutable by default 
<img src="lib/images/mutability.svg" style="height: 40vh"/>

<!--
struct Politician { pub party: String }
fn prepare_elections() -> Politician {
    let mut politician = Politician {
        party: "some".to_string()
    };
    politician.party = "other".to_string();
    politician
}-->
