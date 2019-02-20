# A basic Linux library to stamp files based on the blockchain

The library uses the [Stampery API](https://api.stampery.com/) which allows to prove the existence, integrity and ownership of arbitrary data by anchoring (embedding) unique identifiers (hashes) of files and datasets into the Ethereum and Bitcoin blockchains.

### Requirements

* an authentication token, obtained at https://api-dashboard.stampery.com/tokens
* a Linux system with the Bash shell
* the command line JSON processor [jq](https://stedolan.github.io/jq/)
* the [OpenTimestamps client](https://github.com/opentimestamps/opentimestamps-client)

### Usage

```
$ source stampery-lib
$ stamp <file>
```

A video clip demonstrating a typical usage pattern is available at https://youtu.be/8AtweGnW7Kk.
