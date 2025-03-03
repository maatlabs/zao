# Risc0 Adapter

This package adapts Risc0 version 0.19 to work as a zkVM for Zao.

## Limitations

While in-VM recursion is included in the Risc0 0.19 release, this adapter doesn't currently implement it. Individual "slots" may be proven, but those proofs cannot be recursively combined to facilitate bridging or ultra-fast sync ("user recursion" is not supported).

## Warning

This adapter has not been audited. Please do not deploy in production.
