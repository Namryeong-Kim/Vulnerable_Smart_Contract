# Vulnerable_Smart_Contract

## 사례 ListUp

### Access Control Exploit

### [Real World]

- Value DeFi (v)
  https://bscscan.com/address/0x7a8ac384d3a9086afcc13eb58e90916f17affc89#code
- DAO Maker (v)
  - 소스 공개 x
  - bytecode decompile
    https://etherscan.io/bytecode-decompiler?a=0xf17ca0e0f24a5fa27944275fa0cedec24fbf8ee2
- Safemoon (v)
  https://bscscan.com/address/0xeb11a0a0bef1ac028b8c2d4cd64138dd5938ca7a#code%23L1737
- LaunchZone
- Visor Finance
- Crema
- Poly Network
- DODO
- joyn
  https://github.com/code-423n4/2022-03-joyn/blob/main/core-contracts/contracts/CoreCollection.sol#L78-L97
- Rikkei Finance
  https://bscscan.com/address/0xd55f01b4b51b7f48912cd8ca3cdd8070a1a9dba5#code%23F1%23L29
- Ragnarok Online Invasion
  https://www.bscscan.com/address/0xe48b75dc1b131fd3a8364b0580f76efd04cf6e9c#code#L175
- UERII Token
  https://etherscan.io/address/0x418c24191ae947a78c99fdc0e45a1f96afb254be#code%23L493
- Parity Multisig
  https://etherscan.io/address/0x863df6bfa4469f3ead0be8f9f2aae51c91a907b4#code

### [Example]

- bank.sol
  https://gist.github.com/RealJohnnyTime/23066d3ac3c6f93738567432f5522e82#file-access-control-solidity-sol
- whitelist.sol
  https://goerli.etherscan.io/address/0x53bd8eafb67605c22a9e1a327aab6479583844f9#code

### Drained Contracts (Rug Pull)

- Turtle Dex
  - 소스 공개 x
  - 상장 폐지됨
- Meerkat Finance (v)
  - contract
    https://bscscan.com/address/0x49509a31898452529a69a64156ab66167e755dfb
  - proxy logic 변경 전
    https://bscscan.com/address/0x639f18c72b6a017bdd209c161d1617c9481a1e4d#code
  - proxy logic 변경 후
    https://bscscan.com/address/0x9d3a4c3acee56dce2392fb75dd274a249aee7d57
- Compounder Finance
- Arbix Finance
- Snowdog
- AnubisDAO
- SudoRare
- Blur Finance
- StableMagnet

### Price Oracle

- Rari Capital
- BonqDAO
- ElasticSwap
- Pando Rings
- Solend
- Moola Market
- GMX
- Inverse Finance
- Mango Market

### Re-entrancy

- Lendf.me (dForce)
  https://github.com/OpenZeppelin/exploit-uniswap/tree/master/contracts
- dForce
  https://etherscan.io/bytecode-decompiler?a=0x538359785a8d5ab1a741a0ba94f26a800759d91d
- dForce Network
- The DAO
- Orion
- DFX
- Skyward Finance
- Ola Finance
- Revest Finance
- Siren Protocol
