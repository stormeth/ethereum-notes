curl -L "http://localhost:8545" -X POST --data '{"jsonrpc":"2.0","method":"eth_blockNumber","params":[],"id":"159400"}'

curl -L "http://localhost:8545" -X POST --data '{"jsonrpc":"2.0","method":"eth_protocolVersion","params":"[]","id":"67"}'

For block **159400**

curl -L "http://localhost:8545" -X POST --data '{"jsonrpc":"2.0","method":"eth_getTransactionReceipt","params":["0xe8b78079acb603d2f2fba11f6a78903b7c2a4d14427e6f38082fa8177013fd2d"],"id":1}'

curl -L "http://localhost:8545" -X POST --data '{"jsonrpc":"2.0","method":"eth_syncing","params":[],"id":1}'

curl -L "http://localhost:8545" -X POST --data '{"jsonrpc":"2.0","method":"eth_getBlockTransactionCountByNumber","params":["0xe8"],"id":1}'

