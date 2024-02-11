---
layout: default
title: Block
parent: Components
nav_order: 2
---

# Block
A block is the basic building block of a blockchain. This section describes the general structure and components of a block.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Block Header
The title of a block contains the general characteristics of the block.

| Field            | Description                                           |
| :--------------- | :---------------------------------------------------- |
| `Version`        | Version of the block                                  |
| `Parent Hash`    | The hash value of the previous block.                 |
| `Block Number`   | Represents the number or height of the block.         |
| `Height`         | The height of the location of the block.              |
| `Timestamp`      | Time of creation of the block.                        |
| `Difficulty`     | The difficulty of creating the block.                 |
| `Nonce`          | The nonce value used in the creation of the block.    |
| `Gas Price`      | Specifies the gas price per transaction.              |
| `Gas Limit`      | The value that sets the maximum limit of transactions that can be executed in a block.  |
| `Total Difficulty` | Represents the total difficulty level in the chain. |
| `Transaction Root` | Represents the transaction root of the block.       |

## Finalize Block
Once the creation of a block is complete, the finalization phase of the block begins. At this stage, the title of the block and the Transaction ID are determined.

| Field            | Description                                           |
| :--------------- | :---------------------------------------------------- |
| `*Block Header`  | Title of the completed block.                         |
| `Transaction`    | Represents transactions added to the block            |
| `Validator`      | Represents the block validator                        |

This basic information will help to understand the overall structure of the block. Documentation will continue to be developed in the process.
