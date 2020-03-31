# HTTP libraries performance test

My results:
```bash
$ npm start

http.request POST request x 26,818 ops/sec ±12.45% (76 runs sampled)
http.request GET request x 29,370 ops/sec ±3.70% (81 runs sampled)
axios GET request x 7,947 ops/sec ±8.36% (76 runs sampled)
axios POST request x 7,045 ops/sec ±8.49% (67 runs sampled)
superagent GET request x 11,979 ops/sec ±9.31% (70 runs sampled)
superagent POST request x 11,672 ops/sec ±12.87% (67 runs sampled)
node-fetch GET request x 9,355 ops/sec ±15.60% (60 runs sampled)
node-fetch POST request x 11,677 ops/sec ±8.20% (70 runs sampled)
node-fetch GET request (Bluebird) x 10,207 ops/sec ±8.71% (70 runs sampled)
node-fetch POST request (Bluebird) x 9,987 ops/sec ±10.52% (72 runs sampled)
Request GET request x 8,736 ops/sec ±10.25% (69 runs sampled)
Request POST request x 6,150 ops/sec ±10.70% (66 runs sampled)
Fastest is http.request GET request
```
