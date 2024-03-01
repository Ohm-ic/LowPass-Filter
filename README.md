# LowPass-Filter

This repository contains a C++ implementation of a lowpass filter with Tustin pre-warping for digital signal processing applications.

## Overview

The `LowpassFilter` class implements a lowpass filter with configurable order and cutoff frequency. It uses Tustin pre-warping to transform the cutoff frequency from the continuous-time domain to the
discrete-time domain. The implemented orders are limited to first and second orders.

## Constructor Parameters

- `order`: The order of the filter. It is limited to 1 (first order) or 2 (second order). If a value outside this range is provided, it will default to the nearest valid value.
- `fc`: The cutoff frequency of the filter in Hz.
- `fs`: The sampling frequency of the system in Hz.

## Dependencies

No external dependencies are required for this implementation.

## Credits

This implementation was created by Hariom Agrahari and is based on standard digital signal processing techniques.

## Contributions

Contributions are welcome. Feel free to open an issue or submit a pull request.

## References

- [Tustin's Approximation](https://en.wikipedia.org/wiki/Bilinear_transform#Tustin's_approximation)
- [Digital Signal Processing](https://en.wikipedia.org/wiki/Digital_signal_processing)

