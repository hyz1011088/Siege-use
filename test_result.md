# results of test:

### order1: 
```
siege -c 500 -t 1 https://www.baidu.com/s?rsv_idx=1&tn=62051058_3_bd_dg&wd=siege+%E4%B8%8B%E8%BD%BD&usm=1&ie=utf-8&rsv_rq=2&rsv_cq=siege

```
results:

```
Lifting the server siege...      done.
Transactions:		        2960 hits
Availability:		      100.00 %
Elapsed time:		       59.23 secs
Data transferred:	        0.49 MB
Response time:		        6.80 secs
Transaction rate:	       49.97 trans/sec
Throughput:		        0.01 MB/sec
Concurrency:		      340.00
Successful transactions:        2960
Failed transactions:	           0
Longest transaction:	       42.94
Shortest transaction:	        0.62
```

### order2:

```
siege -c 700 -t 1 https://www.baidu.com/s?rsv_idx=1&tn=62051058_3_bd_dg&wd=siege+%E4%B8%8B%E8%BD%BD&usm=1&ie=utf-8&rsv_rq=2&rsv_cq=siege

```
results:

```
Lifting the server siege...      done.
Transactions:		        1310 hits
Availability:		       89.18 %
Elapsed time:		       59.76 secs
Data transferred:	        0.22 MB
Response time:		       12.93 secs
Transaction rate:	       21.92 trans/sec
Throughput:		        0.00 MB/sec
Concurrency:		      283.55
Successful transactions:        1310
Failed transactions:	         159
Longest transaction:	       37.10
Shortest transaction:	        0.20
```

