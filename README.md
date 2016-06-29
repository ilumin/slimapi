# slimapi

```
slim-api ❯❯❯ docker run -it --rm --net=slimapi_default ilumin/wrk -t12 -c400 -d30s http://172.19.0.3/test-param/ilumin
	Running 30s test @ http://172.19.0.3/test-param/ilumin
	  12 threads and 400 connections
	  Thread Stats   Avg      Stdev     Max   +/- Stdev
	    Latency   811.01ms  402.76ms   1.99s    82.85%
	    Req/Sec    20.50     19.31   250.00     86.70%
	  3694 requests in 30.11s, 829.55KB read
	  Socket errors: connect 0, read 0, write 0, timeout 814
	  Non-2xx or 3xx responses: 35
	Requests/sec:    122.67
	Transfer/sec:     27.55KB
```
