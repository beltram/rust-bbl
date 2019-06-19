## Performance
*Plaintext Resp/s at x concurrent request (June 2019)*

|Fmk|256|1024|16,384|latency|
|:-------:|:-------:|:------:|:--------:|:--------:|
|actix-raw|7,000,221|7,021,312|6,913,990|0.3ms|
|vertx-web|1,702,797|1,714,636|1,606,119|5.6ms|
|spring-tomcat|87,786|22,513|158,808|397.7ms|
|nodejs|576,425|833,499|1,071,143|65.9ms|
[link](https://www.techempower.com/benchmarks/#section=data-r17&hw=ph&test=plaintext)