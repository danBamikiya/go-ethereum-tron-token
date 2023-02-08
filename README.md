This is a small Go program to interact with a deployed Smart Contract on the Ethereum Chain - the Tron token.

The Tron token smart contract is compiled from Solidity, using Abigen, to a Go binding (`token.go`) that can be used by our Go program (`main.go`) to interact with our Tron token deployed on the Ethereum mainnet.

### How To Use

- Make sure Go is installed. Here are the installation [instructions](https://go.dev/doc/install)
- Install the Solidity compiler. Here are the [instructions](https://docs.soliditylang.org/en/v0.8.18/installing-solidity.html#)
- Install the go-ethereum client. Here are the [instructions](https://geth.ethereum.org/docs/getting-started/installing-geth)
- Run the Go packages: `go run main.go token.go`
