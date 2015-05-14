# mbed TLS

mbed TLS (formerly known as PolarSSL) makes it trivially easy for developers to include cryptographic and SSL/TLS capabilities in their (embedded) products, facilitating this functionality with a minimal coding footprint. It offers an SSL library with an intuitive API and readable source code.

The Alpha 3 release of mbed TLS is an integration of TLS, mbed SDK and yotta. It is a testing preview only and **not suitable for deployment**: there is currently no source of random numbers, meaning no security at all for (D)TLS communication and other protocols that rely on random numbers.

## Sample programs

This release includes the [following samples](https://github.com/ARMmbed/mbedtls-examples):

1. [**TLS client:**](https://github.com/ARMmbed/mbedtls-examples/tree/master/tls-client) downloads a file from an HTTPS server (mbed.org) and looks for a specific string in that file.

2. [**Self test:**](https://github.com/ARMmbed/mbedtls-examples/tree/master/selftest) tests different TLS base functionalities.

3. [**Benchmark:**](https://github.com/ARMmbed/mbedtls-examples/tree/master/be nchmark): tests the time and memory required to perform TLS base functions.

## Running TLS

Please follow the instructions in the [TLS client sample](https://github.com/ARMmbed/mbedtls-examples/tree/master/tls-client). These include a list of prerequisites and an explanation of building TLS with yotta.

## Contributing

We graciously accept bugs and contributions from the community. There are some requirements we need to fulfil in order to be able to integrate contributions in the main code:

* Simple bug fixes to existing code do not contain copyright themselves and we can integrate those without any issue. The same goes for trivial contributions.

* For larger contributions, e.g. a new feature, the code possibly falls under copyright law. We then need your consent to share in the ownership of the copyright. We have a form for that, which we will mail to you in case you submit a contribution or pull request that we deem this necessary for.

To contribute, please:

* [Check for open issues](https://github.com/ARMmbed/mbedtls/issues) or [start a discussion](https://tls.mbed.org/discussions) around a feature idea or a bug.

* Fork the [mbed TLS repository on Github](https://github.com/ARMmbed/mbedtls>) to start making your changes.

* Write a test that shows that the bug was fixed or that the feature works as expected.

* Send a pull request and bug us until it gets merged and published. We will include your name in the ChangeLog :)