# BeamZone DApp Store Submission Guidelines

Follow these guidelines to submit your project to the BeamZone DApp store. Before submitting, make sure your project meets the criteria outlined below.

## Prerequisites

1. Your project must be related to Beam Cryptocurrency.
2. Your project should have a working product (mainnet) or be close to completion (dappnet).
3. You should have a clear and concise project description.

## Submission Process

1. Fork the BeamZone repository on GitHub.
2. Create a new branch with a descriptive name (e.g., `add-my-dapp`).
3. In the `dapps` folder, create a new folder with your project's name in lowercase and hyphen-separated (e.g., `my-awesome-dapp`).
4. Inside your project's folder, add the following files:
   - `banner.png` (strict size: 1200x628 pixels)
   - `description.md` (project description with self-contained images, text, and markdown styling)
   - `metadata.json` (details on publisher keys, developer contact info, category, and IPFS hash)

### `metadata.json` Structure

```json
{
  "version": "1.0",
  "publisherKey": "your_publisher_keys_here",
  "ipfsHash": "your_ipfs_hash_here",
  "ipfsGateway": "https://cloudflare-ipfs.com/ipfs/your_ipfs_hash_here",
  "developerEmail": "your_email@example.com",
  "developerSocials": {
    "twitter": "https://twitter.com/your_username",
    "github": "https://github.com/your_username",
    "website": "https://your_website.com"
  },
  "category": "DeFi, NFT, or other relevant category"
}
```

5. Commit your changes and push the new branch to your forked repository.
6. Create a pull request from your new branch to the main branch of the BeamZone repository.
7. In the pull request description, provide a summary of your project and any additional information that may be helpful for the review process.

## Review Process

The Beam team will review your submission and provide feedback or request changes if necessary. If your project meets the guidelines and criteria, it will be approved and merged into the BeamZone DApp store.

Thank you for your interest in joining the Beam ecosystem!
