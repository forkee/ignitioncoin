Ignition development tree

Ignition is a POW/PoS-based cryptocurrency.

IC is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1

Ignition is a PoW (Scrypt) / PoS / Master Node hybrid cryptocurrency, with a 5 million coin maximum supply, which is generated slower and slower over 50 years. Master Node cost 3000IC, block size is 20MB, and block time is ~2Minutes.

Block Spacing: 120 Seconds
Diff Retarget: every Blocks
Maturity: 30 Blocks
Stake Minimum Age: 1/2 Hours

Port: 44144
RPC Port: 44155

For compiling on different architectures, see the docs/build-*os* documents. Otherwise, view releases page for windows qt-wallets.

IC includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the IC codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.
