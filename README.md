# SkImageResizer

## 硬體規格

```txt
OS: macOS Catalina 10.15.6（19G2021）
CPU: Intel Core i9-9980HK CPU 2.40GHz, 1 CPU, 16 logical and 8 physical cores
RAM:64 GB 2667 MHz DDR4
```

## 效能測試

```js
// AfterActualRun
WorkloadResult   1: 1 op, 9383115740.00 ns, 9.3831 s/op
WorkloadResult   2: 1 op, 9131962825.00 ns, 9.1320 s/op
WorkloadResult   3: 1 op, 9031332224.00 ns, 9.0313 s/op
WorkloadResult   4: 1 op, 8680617983.00 ns, 8.6806 s/op
WorkloadResult   5: 1 op, 8684606783.00 ns, 8.6846 s/op
WorkloadResult   6: 1 op, 8975169240.00 ns, 8.9752 s/op
WorkloadResult   7: 1 op, 8791425765.00 ns, 8.7914 s/op
WorkloadResult   8: 1 op, 9149966093.00 ns, 9.1500 s/op
WorkloadResult   9: 1 op, 9274175321.00 ns, 9.2742 s/op
WorkloadResult  10: 1 op, 8847284872.00 ns, 8.8473 s/op
WorkloadResult  11: 1 op, 8904593658.00 ns, 8.9046 s/op
WorkloadResult  12: 1 op, 9273440828.00 ns, 9.2734 s/op
WorkloadResult  13: 1 op, 9634368670.00 ns, 9.6344 s/op
WorkloadResult  14: 1 op, 9031182049.00 ns, 9.0312 s/op
WorkloadResult  15: 1 op, 9646307712.00 ns, 9.6463 s/op
WorkloadResult  16: 1 op, 9038425269.00 ns, 9.0384 s/op
WorkloadResult  17: 1 op, 9595095745.00 ns, 9.5951 s/op
WorkloadResult  18: 1 op, 8938965327.00 ns, 8.9390 s/op
WorkloadResult  19: 1 op, 9215435096.00 ns, 9.2154 s/op
WorkloadResult  20: 1 op, 9466959492.00 ns, 9.4670 s/op
WorkloadResult  21: 1 op, 9500735836.00 ns, 9.5007 s/op
WorkloadResult  22: 1 op, 9278609727.00 ns, 9.2786 s/op
WorkloadResult  23: 1 op, 9575687506.00 ns, 9.5757 s/op
WorkloadResult  24: 1 op, 9179427096.00 ns, 9.1794 s/op
WorkloadResult  25: 1 op, 8927371583.00 ns, 8.9274 s/op
WorkloadResult  26: 1 op, 9283304951.00 ns, 9.2833 s/op
WorkloadResult  27: 1 op, 9378069138.00 ns, 9.3781 s/op
WorkloadResult  28: 1 op, 8896974326.00 ns, 8.8970 s/op
WorkloadResult  29: 1 op, 9162452766.00 ns, 9.1625 s/op
WorkloadResult  30: 1 op, 8967395502.00 ns, 8.9674 s/op
WorkloadResult  31: 1 op, 8984686865.00 ns, 8.9847 s/op

// AfterAll
// Benchmark Process 3993 has exited with code 0

Mean = 9.156 s, StdErr = 0.049 s (0.54%), N = 31, StdDev = 0.275 s
Min = 8.681 s, Q1 = 8.953 s, Median = 9.150 s, Q3 = 9.331 s, Max = 9.646 s
IQR = 0.378 s, LowerFence = 8.387 s, UpperFence = 9.897 s
ConfidenceInterval = [8.976 s; 9.336 s] (CI 99.9%), Margin = 0.180 s (1.97% of Mean)
Skewness = 0.19, Kurtosis = 1.99, MValue = 2

// ***** BenchmarkRunner: Finish  *****

// * Export *
  BenchmarkDotNet.Artifacts/results/SkImageResizer.Benchmark.SkImageResizerBenchmark-report.csv
  BenchmarkDotNet.Artifacts/results/SkImageResizer.Benchmark.SkImageResizerBenchmark-report-github.md
  BenchmarkDotNet.Artifacts/results/SkImageResizer.Benchmark.SkImageResizerBenchmark-report.html

// * Detailed results *
SkImageResizerBenchmark.ResizeImages: Job-OIYMPL(InvocationCount=1, UnrollFactor=1) [N=5]
Runtime = .NET Core 3.1.4 (CoreCLR 4.700.20.20201, CoreFX 4.700.20.22101), X64 RyuJIT; GC = Concurrent Workstation
Mean = 9.068 s, StdErr = 0.044 s (0.48%), N = 15, StdDev = 0.169 s
Min = 8.843 s, Q1 = 8.948 s, Median = 9.012 s, Q3 = 9.169 s, Max = 9.455 s
IQR = 0.221 s, LowerFence = 8.617 s, UpperFence = 9.499 s
ConfidenceInterval = [8.887 s; 9.249 s] (CI 99.9%), Margin = 0.181 s (1.99% of Mean)
Skewness = 0.66, Kurtosis = 2.47, MValue = 2
-------------------- Histogram --------------------
[8.753 s ; 9.108 s) | @@@@@@@@@@
[9.108 s ; 9.299 s) | @@@@
[9.299 s ; 9.545 s) | @
---------------------------------------------------

SkImageResizerBenchmark.ResizeImagesAsync: Job-OIYMPL(InvocationCount=1, UnrollFactor=1) [N=5]
Runtime = .NET Core 3.1.4 (CoreCLR 4.700.20.20201, CoreFX 4.700.20.22101), X64 RyuJIT; GC = Concurrent Workstation
Mean = 9.156 s, StdErr = 0.049 s (0.54%), N = 31, StdDev = 0.275 s
Min = 8.681 s, Q1 = 8.953 s, Median = 9.150 s, Q3 = 9.331 s, Max = 9.646 s
IQR = 0.378 s, LowerFence = 8.387 s, UpperFence = 9.897 s
ConfidenceInterval = [8.976 s; 9.336 s] (CI 99.9%), Margin = 0.180 s (1.97% of Mean)
Skewness = 0.19, Kurtosis = 1.99, MValue = 2
-------------------- Histogram --------------------
[8.566 s ; 8.828 s) | @@@
[8.828 s ; 9.058 s) | @@@@@@@@@@@
[9.058 s ; 9.322 s) | @@@@@@@@@
[9.322 s ; 9.671 s) | @@@@@@@@
---------------------------------------------------

// * Summary *

BenchmarkDotNet=v0.12.1, OS=macOS Catalina 10.15.6 (19G2021) [Darwin 19.6.0]
Intel Core i9-9980HK CPU 2.40GHz, 1 CPU, 16 logical and 8 physical cores
.NET Core SDK=3.1.300
  [Host]     : .NET Core 3.1.4 (CoreCLR 4.700.20.20201, CoreFX 4.700.20.22101), X64 RyuJIT
  Job-OIYMPL : .NET Core 3.1.4 (CoreCLR 4.700.20.20201, CoreFX 4.700.20.22101), X64 RyuJIT

InvocationCount=1  UnrollFactor=1  

|            Method | N |    Mean |    Error |   StdDev |
|------------------ |-- |--------:|---------:|---------:|
|      ResizeImages | 5 | 9.068 s | 0.1809 s | 0.1692 s |
| ResizeImagesAsync | 5 | 9.156 s | 0.1800 s | 0.2749 s |

// * Legends *
  N      : Value of the 'N' parameter
  Mean   : Arithmetic mean of all measurements
  Error  : Half of 99.9% confidence interval
  StdDev : Standard deviation of all measurements
  1 s    : 1 Second (1 sec)

// ***** BenchmarkRunner: End *****
// ** Remained 0 benchmark(s) to run **
Run time: 00:09:52 (592.55 sec), executed benchmarks: 2

Global total time: 00:09:57 (597.33 sec), executed benchmarks: 2
// * Artifacts cleanup *
```