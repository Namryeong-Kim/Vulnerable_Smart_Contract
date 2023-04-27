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
- LaunchZone (v)
  - 소스 공개 x
- Visor Finance (v)
  https://etherscan.io/address/0xc9f27a50f82571c1c8423a42970613b8dbda14ef#code
- Dexible (v)
  https://etherscan.io/address/0x33e690aEa97E4Ef25F0d140F1bf044d663091DAf#code
- joyn (v)
  https://github.com/code-423n4/2022-03-joyn/blob/main/core-contracts/contracts/CoreCollection.sol#L78-L97
- Rikkei Finance (v)
  https://bscscan.com/address/0xd55f01b4b51b7f48912cd8ca3cdd8070a1a9dba5#code%23F1%23L29
- Ragnarok Online Invasion (v)
  https://www.bscscan.com/address/0xe48b75dc1b131fd3a8364b0580f76efd04cf6e9c#code#L175
- UERII Token (v)
  https://etherscan.io/address/0x418c24191ae947a78c99fdc0e45a1f96afb254be#code%23L493
- Parity Multisig (v)
  https://etherscan.io/address/0x863df6bfa4469f3ead0be8f9f2aae51c91a907b4#code
- Crema
- Poly Network
- DODO

### [Example]

- bank.sol
  https://gist.github.com/RealJohnnyTime/23066d3ac3c6f93738567432f5522e82#file-access-control-solidity-sol
- whitelist.sol
  https://goerli.etherscan.io/address/0x53bd8eafb67605c22a9e1a327aab6479583844f9#code

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

[dforce audit report]
github: https://github.com/dforce-network/documents/tree/master/audit_report
docs: https://docs.dforce.network/
medium: https://medium.com/dforcenet

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
- Omni Protocol -> double reentrancy
  https://etherscan.io/address/0x50c7a557d408a5f5a7fdbe1091831728ae7eba45#code
  PoC: https://github.com/immunefi-team/hack-analysis-pocs/blob/main/src/omni-july-2022/Attacker.sol
