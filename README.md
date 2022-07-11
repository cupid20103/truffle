# Truffle common usage

truffle init
truffle create contract `Contract Name`
truffle create test `Test Name`

truffle compile [Contract Name]
truffle test [Test Name]

truffle migrate [--network `Network`] [--reset]
truffle deploy [--network `Network`] [--reset]
truffle migrate -f X --to X [--network `Network`] [--reset]

truffle run verify `Contract Name` [--network rinkeby]

npx sol-merger "contracts/`ContractName.`"