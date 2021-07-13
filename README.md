# Fox Token Airdrop Merkle Proofs

This repo contains merkle proofs used to claim from the fox token airdrop.

Usage:

1. Determine if your address is eligible to claim the airdrop by locating it in one of the proof json files.
2. Make note of the `index`, `amount` and `proof` fields for your address. The filename is the airdrop contract address you will be claiming from.
3. Use a service such as myetherwallet or mycrypto to interact with the contract address for your claim.
    - Use the ABI from TokenDistributor.json
    - Call the `claim` function using `your address`, `index`, `amount` and `proof`.  
        - Note: `amount` is a hex number and may need to be converted to decimal depending which service you use to interact with the contract