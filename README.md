# RasBench

This repository hosts rasdaman benchmarks and benchmark results. It is complimentary to the "Array Databases: Concepts, Standards, Implementations" report (https://www.rd-alliance.org/system/files/Array-Databases_final-report.pdf) and relates directly to the 


Benchmark tests included in this repository measure various functionalities, data sizings, and also the effect of parallelization.




The benchmarks
are executed with benchy (https://github.com/misev/benchy). For example, to
execute the `polygon_clipping` benchmark suite and save the results in the
`polygon_clipping_results` directory:

```bash
benchy.sh -d polygon_clipping/ -r polygon_clipping_results/
```

To setup another benchmark the `benchmark.conf` and `datamanager.sh` from
`polygon_clipping` can be reused.

Refer to the documentation of benchy for further information.
