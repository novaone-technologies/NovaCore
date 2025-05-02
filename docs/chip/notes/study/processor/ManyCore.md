# ManyCore

Manycore processors are special kinds of multi-core processors designed for a high degree of parallel processing, containing numerous simpler, independent processor cores (from a few tens of cores to thousands or more). Manycore processors are used extensively in embedded computers and high-performance computing.

Manycore processors are distinct from multi-core processors in being optimized from the outset for a higher degree of explicit parallelism, and for higher throughput (or lower power consumption) at the expense of latency and lower single-thread performance.

The broader category of multi-core processors, by contrast, are usually designed to efficiently run both parallel and serial code, and therefore place more emphasis on high single-thread performance (e.g. devoting more silicon to out-of-order execution, deeper pipelines, more superscalar execution units, and larger, more general caches), and shared memory. These techniques devote runtime resources toward figuring out implicit parallelism in a single thread. They are used in systems where they have evolved continuously (with backward compatibility) from single core processors. They usually have a 'few' cores (e.g. 2, 4, 8) and may be complemented by a manycore accelerator (such as a GPU) in a heterogeneous system.

Source - https://en.wikipedia.org/wiki/Manycore_processor