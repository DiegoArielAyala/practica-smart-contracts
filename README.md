1. Los usuarios podran entrar en la loteria usando ETH cuyo precio estara basado en USD -> 50$
2. Un admin va a decidir cuando la loteria se termina
3. La loteria automatincamente va a seleccionar un ganador de manera aleatoria

Como voy a hacer test de esto?

1. Usar "mainnet-fork" porque usamos contratos que estan on chain (ejemplo el price feed, y podemos usar este contrato desplegado usando la fork mainnet)
2. "development" usando Mocks
3. "testnet" para hacer integration testing
