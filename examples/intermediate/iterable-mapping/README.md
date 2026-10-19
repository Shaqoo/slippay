# Iterable Mapping Example

This is the canonical iterable-map example used by the Soroban Cookbook.

It demonstrates how to iterate over a Soroban map (Dict) using the Soroban SDK.

## Overview

This example shows the pattern for reading all keys/values from a Soroban `Map` type, which is essential for many on-chain operations such as:
- Enumerating all allowances for an operator
- Collecting all balances in a token contract
- Processing all entries in a data storage map

## Key Concepts

- **Soroban `Map` (Dict)**: A key-value storage persistent across contract invocations
- **Iteration pattern**: Using `Map::all()` to iterate over all entries
- **Cursor-based pagination**: For large maps, using cursors to paginate through results

## Usage

```bash
# Build the contract
cd contract
carl build --release

# Deploy and interact
# (see the full tutorial in the Soroban Cookbook)
```