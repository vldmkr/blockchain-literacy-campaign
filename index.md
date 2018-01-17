_blockchain_ literacy campaign

---

[Blockchain Demo](https://anders.com/blockchain/hash.html)

---

_Hash_ - репрезентация входных данных в виде уникальной строки фиксированной длины

---

_Nonce_ - одноразовый код, выбранный случайным образом

---

_Difficulty_ - это мера того, как трудно найти _хэш_ ниже заданной цели

---

_Token_ - расчетная единица в децентрализованных системах

---

_Coinbase_ - значение генерирующей транзакции

---

_Smart contract_ (тех.) - алгоритм выполняемый на _VM_ конкретной децентрализованной системы

---

_VM_ - программная система позволяющая выполнять целевой код в изолированных процессах абстрагируясь от аппаратной реализации

---

_SCRIPT_ - используемый в _Bitcoin_ скриптовый язык. Основан на стеке, не является Тьюринг-полным

---

_pay-to-pubkey-hash_
```
<sig>
<pubKey>

OP_DUP
OP_HASH160
<pubKeyHash>
OP_EQUALVERIFY
OP_CHECKSIG
```

---

язык, используемый в _EVM_ имеет конечный автомат и функцию рекурсивной отправки сообщений

---

```
PUSH1            JUMPDEST 
0                PUSH1
CALLDATALOAD     32
SLOAD            CALLDATALOAD
NOT              PUSH1
PUSH1            0
9                CALLDATALOAD
JUMPI            SSTORE
STOP
```
---

_Solidity_ - высокоуровневый язык ориентированный на разработку контрактов, исполняющихся на _EVM_, транслируются в байткод _EVM_

---

```
contract SimpleStorage {
  uint256 public value;
  
  function setValue(uint256 _value) public {
    value = _value;
  }
}
```

---

_THX_


Buy Bitcoins

---
