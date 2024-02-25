---
layout: default
title: Transaction
parent: Components
nav_order: 2
---

# Transaction
Transactions represent events that are performed on the blockchain. This section describes the general structure and components of a transaction.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Raw Transaction

| Field           | Description                                                         |
| :-------------- | :------------------------------------------------------------------ |
| `Nonce`         | The number of transactions sent from the sender's address.          |
| `ChainID`       | Specifies the ID of the target chain to execute the operation.      |
| `Action`        | Specifies the action to be performed in the transaction, for example sending money to an account or calling a contract function.          |
| `Gas`           | Specifies the maximum amount of gas allocated for the process. The gas quantity specifies the maximum process cost required to perform the process. |
| `Gas Price`     | Specifies the gas price to be paid per transaction. Gas represents the calculation amount needed to process the transaction.             |
| `Value`         | Specifies the amount of assets to be transferred in the transaction, for example the amount of currency or tokens.         |
| `Timestamp`     | The timestamp indicating when the transaction was executed.          |
| `Data`          | Additional data associated with the transaction.                     |

{: .note } 
These components contain the basic features of a transaction. Documentation will continue to be developed throughout the process.

