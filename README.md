# Linnia Smart Contracts ![Build Status](https://circleci.com/gh/ConsenSys/Linnia-Smart-Contracts.png?circle-token=:circle-token&style=shield) ![Coverage Status](https://codecov.io/gh/ConsenSys/Linnia-Smart-Contracts/branch/master/graph/badge.svg)
---
> :warning: WIP

Smart Contracts for Linnia

# Overview
## Linnia Users
A contract that keeps a registry of registered users and their provenance.

## Linnia Records
A contract that keeps a registry of metadata of uploaded medical records, as well as the IRIS score of those records. The metadata makes records easily searchable.

## Linnia Permissions
A contract that keeps a registry of permissions. Permissions include who can view what data, and where the permissioned copy is stored on IPFS.

# Installing (only once)

Installs `babel` and `openzeppelin-solidity`.

```
npm install
```


# Deploying
```
npm run migrate
```

# Testing
To run tests with coverage
```
npm run coverage
```

To run tests without coverage
- First start testrpc with `npm start`
  - Alternatively you can run Ganache GUI at port 7545 with network id 5777
- Run `npm test`
