# TrueSight Pulse Random Plugin 

Example plugin written using the meter plugin SDK for C.

Generates random data with a specified upper and lower limit.

### Prerequisites

|     OS    | Linux | Windows | SmartOS | OS X |
|:----------|:-----:|:-------:|:-------:|:----:|
| Supported |   v   |    v    |    v    |  v   |

- TrueSight Pulse Meter SDK for C

### Plugin Setup

For this plugin to run the [TrueSight Pulse Meter SDK for C](https://github.com/boundary/meter-plugin-sdk-c) must
be installed on the same host where the plugin is running.

### Plugin Configuration Fields

|Field Name|Description                                                                                              |
|:---------|:--------------------------------------------------|
|Minimum   |Lower limit on the random number generated.        |
|Maximum   |Upper limit on the random number generated.        |
|Source    |Label to display in the legend for the measurement.|
|Interval  |How often should the plugin poll for metrics.      |

### Metrics Collected

|Metric Name      |Description                       |
|:----------------|:---------------------------------|
| EXAMPLE\_RANDOM | Random value generated by plugin |

### Dashboards

- Example Random
