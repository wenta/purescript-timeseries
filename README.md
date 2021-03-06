# Time Series library

[![Build status](https://travis-ci.org/carldata/purescript-timeseries.svg?branch=master)](https://travis-ci.org/carldata/purescript-timeseries)
<a href="https://pursuit.purescript.org/packages/purescript-timeseries">
  <img src="https://pursuit.purescript.org/packages/purescript-timeseries/badge"
       alt="purescript-timeseries on Pursuit">
  </img>
</a>

Library for Time Series analysis. Online demo application is available at:
https://timeserieslab.github.io/


## Installation

```
bower install purescript-timeseries
```

## Features

  * Basic functionality
    * [x] Slicing series
    * [x] Filtering series
    * [x] Join 2 series
    * [x] Mapping over series
    * [x] Integration
    * [x] Differentiation
    * [x] Rolling window
    * [x] GroupBy
  * Input/Output
    * [x] Reading data from CSV string
  * Filtering
    * [x] Fill missing values (Reindex)
    * [x] Remove outliers
  * Advanced functionality
    * [x] Finding sessions (periods of activity)
    * [ ] FFT
  * Models
    * [x] Exponential smoothing


## Documentation

Module documentation is [published on Pursuit](http://pursuit.purescript.org/packages/purescript-timeseries).


## Build

```bash
bower update
pulp test
```


# Join in!

We are happy to receive bug reports, fixes, documentation enhancements,
and other improvements.

Please report bugs via the
[github issue tracker](http://github.com/carldata/purescript-timeseries/issues).



# Redistributing

purescript-timeseries source code is distributed under the Apache-2.0 license.

**Contributions**

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
licensed as above, without any additional terms or conditions.
