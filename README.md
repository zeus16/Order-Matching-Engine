# Order-Matching-Engine

### Single orderbook on one thread:
On average, an order takes 2.5μs to process an order. This means that the engine can ingest and process 400k orders per second (on 3 GHz Intel Core i7, 16 GB 1600 MHz DDR3) using the pypy compiler. More benchmarks to come.

### Multiple orderbooks, one thread per orderbook:
On average, an order takes 1.18μs to process an order. This means that the engine can ingest and process 850k orders per second (on 3 GHz Intel Core i7, 16 GB 1600 MHz DDR3) using the pypy compiler. More benchmarks to come.

