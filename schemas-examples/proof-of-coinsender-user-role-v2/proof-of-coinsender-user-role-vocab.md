# CoinSender User Role Vocab

## Context

This is a vocab schema defined for the CoinSender User Role. It's used in a system of CoinSender and used for defining the role of a user in the system.

The context of this schema can be found at https://raw.githubusercontent.com/valeriiman/CoinSender0xpolygon/main/schemas-examples/proof-of-coinsender-user-role/proof-of-coinsender-user-role.json-ld

## Classes

### ProofOfCoinsenderUserRole

The `ProofOfCoinsenderUserRole` class is used to represent a proof of a user role in the CoinSender system.

## Properties

### role

The `role` property is used to denote the role of a user in the system. This is an integer where different integers represent different roles.

0 - Viewer: Has the right to view information only, cannot send tokens.

1 - Operator: Has the right to send tokens.

2 - Admin: Has all rights except for managing users.

3 - Super Admin: Has all rights, including managing users.