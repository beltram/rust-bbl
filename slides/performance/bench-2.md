## Performance
*Json Resp/s at x concurrent request (June 2019)*

|Fmk|32|128|512|latency|
|:-------:|:-------:|:------:|:--------:|:--------:|
|actix-raw|360,378|866,188|1,120,402|0.3ms|
|vertx-web|388,130|792,959|994,797|0.6ms|
|spring-tomcat|74,759|102,252|104,566|4.8ms|
|nodejs|258,478|532,514|561,593|0.9ms|
[link](https://www.techempower.com/benchmarks/#section=data-r17&hw=ph&test=json)