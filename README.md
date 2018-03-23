# JWT::Multisig

[![Build Status](https://travis-ci.org/rubykube/jwt-multisig.svg?branch=master)](https://travis-ci.org/rubykube/peatio)
[![Maintainability](https://api.codeclimate.com/v1/badges/94315656e1c877212c32/maintainability)](https://codeclimate.com/github/rubykube/jwt-multisig/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/94315656e1c877212c32/test_coverage)](https://codeclimate.com/github/rubykube/jwt-multisig/test_coverage)

## Usage

`JWT::Multisig.generate_jwt(payload, private_keychain, algorithms)`

`JWT::Multisig.generate_jws(payload, key_id, key_value, algorithm)`

`JWT::Multisig.verify_jwt(jwt, public_keychain, options)`

`JWT::Multisig.verify_jws(jws, payload, public_keychain, options)`

The full documentation is available at [rubydoc.info](http://www.rubydoc.info/gems/jwt-multisig).
