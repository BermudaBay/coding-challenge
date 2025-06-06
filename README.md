# Coding Challenge

## Task 1

Develop a Noir function that computes a Merkle tree root just like the [Circom](./merkleproof.circom) reference implementation does - utilizing Poseidon as hash.

Make sure that correctness of 

- your Noir function 

can be verified easily by running it against 

- the Circom reference implementation 

as well as

- a JS-WASM computed Merkle tree root 

in a bash script.

> We have a robust fork of Circom/snarkjs libs at https://github.com/chiefbiiko/slimejs

> The `.env` file contains elements that were used for the `merkleproof.json` fixture; use these test values when computing the Merkle tree root(s).

## Task 2

Find 

- a Poseidon2 Solidity hasher contract 
- the matching Noir hash function
- and a corresponding JS function

and write a bash script that demonstrates that their hashing is equal. 

> Please use foundry tools for any EVM related steps.