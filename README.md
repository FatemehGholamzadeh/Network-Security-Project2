# Network-Security-Project-phase-2
implementation of a secure tunnel,
in this phase instead of using physical keys, session keys are generated using RSA algorithm and they're transferred in the tunnel. 
both server and client have a table for storing public and private keys. 
at fist session keys are transferred using asymmetric encryption and then communication continues based on symmetric encryption.
