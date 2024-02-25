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
| `ChainID`       | Identity of the target chain where the transaction will be executed |
| `Action`        | The action to be performed in the transaction, for example sending money to an account or calling a contract function. |
| `Gas`           | The maximum amount of gas allocated for the transaction The amount of gas indicates the maximum transaction cost required to perform the transaction. |
| `Gas Price`     | Gas price payable per transaction. Gas represents the calculation amount required to execute the transaction.             |
| `Value`         | Specifies the amount of assets to be transferred in the transaction, for example the amount of currency or tokens.         |
| `Data`          | Additional data associated with the transaction.                     |

# Signed Transaction

| Field           | Description                                                         |
| :-------------- | :------------------------------------------------------------------ |
| `Raw Transaction` | RawTransaction structure containing the unsigned transaction.     |
| `Signature`     | Contains the digital signature used to sign the transaction.        |
| `Hash`          | A summary value representing the unique identifier of the transaction. |
| `Timestamp`     | The timestamp indicating when the transaction was executed.          |

{: .note } 
These components contain the basic features of a transaction. Documentation will continue to be developed throughout the process.

