## Performance
*Resp/s at x queries/request (June 2019)*

|Fmk|1|10|20|latency|
|:-------:|:-------:|:------:|:--------:|:--------:|
|actix-raw|604,671|89,064|45,170|11.2ms|
|vertx-postgres|623,792|84,503|41,920|12.9ms|
|spring-tomcat|80,140|12,190|6,238|80.9ms|
|nodejs|129,368|16,446|8,522|88.6ms|
[link](https://www.techempower.com/benchmarks/#section=data-r17&hw=ph&test=query)