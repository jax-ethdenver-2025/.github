# Jax

## Incentivized Decentralized File Storage on Ethereum

Jax is a decentralized file storage protocol that enables users to store files across a network of peers while incentivizing others to maintain their availability. The platform functions as a self-sustaining ecosystem where anyone can participate either by sharing files, providing storage resources, or creating incentives around storing specific files.

## Concept

Jax creates a direct connection between users who need storage and those who can provide it:

- File owners define treasuries in order to incentivize storage of their content.
- Storage providers work to discover and host content they are interested in providing.
- A distributed peer trust oracle (powered by EigenLayer) comes to consensus on which providers are faithfully storing which files through many rounds of ZK-proofs.
- The oracle network allows providers to withdraw rewards from file owners' treasuries in proportion to their behavior as peers.
- Providers can then claim rewards due to their storage contribution. They are free to enter and leave the set of providers hosting a file at will, allowing them to chase down opportunities they consider worthwhile.

## Benefits

- **Open Participation**: Anyone can join as a user or storage provider
- **Economic Sustainability**: Storage providers earn rewards for their services
- **Reliability**: Files are distributed across multiple nodes with verification
- **No Central Authority**: The system operates through smart contracts and peer verification
