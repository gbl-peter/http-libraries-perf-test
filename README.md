# HTTP libraries performance test

## Introduction

I needed to find an HTTP client library for server-side work, with a balance between aesthetics and performance.

## Installation

After cloning this repo, run the following:
```
$ npm install
```

## Usage

To use, simply run the (only) npm script:
```
$ npm start
```

## Benchmarks

```bash
http.request POST request x 26,935 ops/sec ±5.28% (78 runs sampled)
http.request GET request x 25,685 ops/sec ±7.79% (73 runs sampled)
axios GET request x 7,116 ops/sec ±7.30% (73 runs sampled)
axios POST request x 7,208 ops/sec ±7.11% (75 runs sampled)
superagent GET request x 11,734 ops/sec ±10.05% (70 runs sampled)
superagent POST request x 11,354 ops/sec ±9.80% (69 runs sampled)
node-fetch GET request x 10,742 ops/sec ±9.52% (66 runs sampled)
node-fetch POST request x 10,955 ops/sec ±8.83% (69 runs sampled)
node-fetch GET request (Bluebird) x 9,046 ops/sec ±13.03% (69 runs sampled)
node-fetch POST request (Bluebird) x 9,025 ops/sec ±10.44% (68 runs sampled)
Request GET request x 7,896 ops/sec ±9.48% (62 runs sampled)
Request POST request x 6,619 ops/sec ±10.35% (68 runs sampled)
Fastest is http.request POST request,http.request GET request
```
