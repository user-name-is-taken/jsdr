# jsdr
graphing rtl-sdr data with JavaScript libraries.

# Components

1. SDR communication over webusb to pull samples from the SDR
    - Something like [rtl-sdr from npm](https://www.npmjs.com/package/rtl-sdr) or 
2. Data transformations on the samples pulled from the SDR
    - Something like [basic dsp](https://crates.io/crates/basic_dsp)
    - This has to be *fast*
3. Graphing and user interaction

# SDRs this will support

- RTL-SDR
- 
