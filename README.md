# A basic Linux library to stamp files based on the blockchain

It uses the [Stampery API](https://api.stampery.com/) which allows to prove the existence, integrity and ownership of all your data by anchoring (embedding) unique identifiers (hashes) of your files and datasets into the Ethereum and Bitcoin blockchains.

Requirements:
* an authentication token, obtained at https://api-dashboard.stampery.com/tokens
* a Linux system with the Bash shell
* the command line JSON processor [jq](https://stedolan.github.io/jq/)
* the [OpenTimestamps client](https://github.com/opentimestamps/opentimestamps-client)
