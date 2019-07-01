## Structopt
<img src="lib/images/structopt.svg" style="height:45vh"/>   

<!--
#[derive(StructOpt, Debug)]
#[structopt(name = "guilt")]
struct Guilt {
    // This is the -h message
    //
    // and this is the --help message
    #[structopt(short = "d", long = "debug")]
    debug: bool,
    #[structopt(subcommand)]
    cmd: Commands,
}
        
#[derive(Debug, StructOpt)]
#[structopt(rename_all = "kebab-case")]
pub enum Commands {
    Blame {
        who: String,
    },
}
        
println!("{:?}", Guilt::from_args());-->
