# @dharma-eng/merkle-distributor (forked from @uniswap/merkle-distributor)

[![Tests](https://github.com/dharma-eng/merkle-distributor/workflows/Tests/badge.svg)](https://github.com/dharma-eng/merkle-distributor/actions?query=workflow%3ATests)
[![Lint](https://github.com/dharma-eng/merkle-distributor/workflows/Lint/badge.svg)](https://github.com/dharma-eng/merkle-distributor/actions?query=workflow%3ALint)

These contracts have been modified to include a mechanism for "funding" the distributor from a specific funder and with a specific amount of the target token, designated at the time of deployment. The funder must first approve the distributor to transfer the tokens to be funded on its behalf.

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`
