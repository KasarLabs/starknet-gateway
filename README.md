<!-- markdownlint-disable -->
<div align="center">
<img src="https://kasar.io/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FkasarLogo.0513044c.png&w=640&q=75" height="100" style="border-radius: 15px;">
</div>
<div align="center">
<br />
<!-- markdownlint-restore -->

[![Project license](https://img.shields.io/github/license/kasarLabs/feeder-gateway-client.svg?style=flat-square)](LICENSE)
[![Pull Requests welcome](https://img.shields.io/badge/PRs-welcome-ff69b4.svg?style=flat-square)](https://github.com/kasarLabs/feeder-gateway-client/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
<a href="https://twitter.com/KasarLabs">
<img src="https://img.shields.io/twitter/follow/KasarLabs?style=social"/> </a>
<a href="https://github.com/kasarlabs/feeder-gateway-client">
<img src="https://img.shields.io/github/stars/kasarlabs/feeder-gateway-client?style=social"/>
</a>

</div>

# 🌌 **Starknet Feeder Gateway client (WIP)**

---

### 🚀 **Table of Contents**

- [get_oldest_transaction_age](#get_oldest_transaction_age)
- [get_number_of_transactions_in_backlog](#get_number_of_transactions_in_backlog)
- [get_block](#get_block)
- [get_block_hash_by_id](#get_block_hash_by_id)
- [get_block_id_by_hash](#get_block_id_by_hash)
- [get_contract_addresses](#get_contract_addresses)
- [get_class_by_hash](#get_class_by_hash)
- [get_compiled_class_by_class_hash](#get_compiled_class_by_class_hash)
- [get_state_update](#get_state_update)
- [get_transaction](#get_transaction)
- [get_transaction_status](#get_transaction_status)
- [get_signature](#get_signature)
- [get_public_key](#get_public_key)

---

#### 📜 **`get_oldest_transaction_age`**

- **Description**: Retrieves the age of the oldest transaction in the transaction pool.
- **Parameters**: None.
- **Response**: Age in seconds of the oldest transaction.

---

#### 📜 **`get_number_of_transactions_in_backlog`**

- **Description**: Determines the count of transactions in the backlog.
- **Parameters**: None.
- **Response**: Number of transactions in the backlog.

---

#### 📜 **`get_block`**

- **Description**: Fetches block details.
- **Parameters**:
    - `block_hash` (Optional): Desired block's hash.
    - `block_number` (Optional): Desired block's number.
- **Response**: Block details.

---

#### 📜 **`get_block_hash_by_id`**

- **Description**: Retrieves a block's hash using its ID.
- **Parameters**:
    - `block_id`: Block's ID.
- **Response**: Block's hash.

---

#### 📜 **`get_block_id_by_hash`**

- **Description**: Gets a block's ID using its hash.
- **Parameters**:
    - `block_hash`: Block's hash.
- **Response**: Block's ID.

---

#### 📜 **`get_contract_addresses`**

- **Description**: Provides all deployed contract addresses.
- **Parameters**: None.
- **Response**: List of contract addresses.

---

#### 📜 **`get_class_by_hash`**

- **Description**: Fetches the contract class via its hash.
- **Parameters**:
    - `class_hash`: Contract class hash.
- **Response**: Contract class details.

---

#### 📜 **`get_compiled_class_by_class_hash`**

- **Description**: Acquires the compiled contract class via its hash.
- **Parameters**:
    - `class_hash`: Contract class hash.
- **Response**: Compiled contract class details.

---

#### 📜 **`get_state_update`**

- **Description**: Retrieves state updates for a given block.
- **Parameters**:
    - `block_hash` (Optional): Desired block's hash.
    - `block_number` (Optional): Desired block's number.
- **Response**: State update details.

---

#### 📜 **`get_transaction`**

- **Description**: Provides detailed transaction information.
- **Parameters**:
    - `tx_hash`: Desired transaction's hash.
- **Response**: Transaction details.

---

#### 📜 **`get_transaction_status`**

- **Description**: Checks a transaction's current status.
- **Parameters**:
    - `tx_hash`: Desired transaction's hash.
- **Response**: Transaction status.

---

#### 📜 **`get_signature`**

- **Description**: Retrieves the signature of a given block.
- **Parameters**:
    - `block_hash` (Optional): Desired block's hash.
    - `block_number` (Optional): Desired block's number.
- **Response**: Block's signature.

---

#### 📜 **`get_public_key`**

- **Description**: Acquires the Starknet Feeder Gateway's public key.
- **Parameters**: None.
- **Response**: Public key string.