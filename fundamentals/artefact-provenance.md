---
description: Ensuring Cross-Chain Provenance with Keccak-256 and SolidMetadata
---

# 🔎 Artefact Provenance

Similar to how Blockchains prove transactions with hash functions, BIMP's artwork has been hashed using the Keccak256 checksum and each hash has been included as part of the artefact metadata on **Bitcoin** and **Solana**.&#x20;

Keccak256 is a cryptographic hashing function, which takes in a message of any size and produces a fixed-size output (256 bits) that represents a unique "fingerprint" of the input data.

This output is (usually) represented as a long string of numbers and letters. Even a small change to the input data will result in a vastly different output, making it almost impossible to reverse-engineer the original input from the output.

> _Anyone, Anywhere can prove that the digital artefact in question, is actually an official BIMP by comparing the Keccak256 file checksum for the binary image data against the one stored on the Blockchain._

_**Provenance on Solana via 'Artefact'**_&#x20;

As of 17/02/2023 the TokenMetadata standard for Solana is not immutable / ossified and still accessible via development keys. The foundation highlighted this as an issue to the authentic artefact collecting experience and thus created a **fork of an alternative standard "NFToken" known as 'Artefact.**&#x20;

Read more about the NFToken fork "**Artefact**" [here.](../infrastructure/artefact-standard/)
