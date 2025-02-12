The computer code stored within a [Smart Contract](#WhatIsASmartContract) can **not** change.

The ability to update a [Smart Contracts](#WhatIsASmartContract) code is designed into Ethereum, however,
there is currently no [instruction](https://ethereum.org/en/developers/docs/evm/opcodes/) to trigger this.

The information stored within the memory allocated to a [Smart Contract](#WhatIsASmartContract) can change.
For example, when an [NFT](#WhatIsAnNFT) is purchased the memory associated to the [NFT](#WhatIsAnNFT)'s [Smart Contract](#WhatIsASmartContract) must
be updated to store the new owner.

**References**
-   [Github - go-ethereum/core/state/state_object](https://github.com/ethereum/go-ethereum/blob/5fb463dddc928eec38de80f63ebdd9d7820d1a72/core/state/state_object.go#L499-L503)
-   [Ethereum - opcodes](https://ethereum.org/en/developers/docs/evm/opcodes/)
