# Truffle common usage

## Normal command

truffle init

truffle create contract `Contract Name`

truffle create test `Test Name`

truffle compile [Contract Name]

truffle test [Test Name]

## Migrate & Deploy command

truffle migrate [--network `Network`] [--reset]

truffle deploy [--network `Network`] [--reset]

truffle migrate -f X --to X [--network `Network`] [--reset]

## Verify command

truffle run verify `Contract Name` [--network rinkeby]

## Other command

npx sol-merger "contracts/`ContractName.`"