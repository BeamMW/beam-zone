# BeamZone DApp Store Submission Guidelines

Follow these guidelines to submit your project to the BeamZone DApp store. Before submitting, make sure your project meets the criteria outlined below.

## Prerequisites

1. Your project must be related to the Beam Privacy cryptocurrency.
2. Your project should have a working product (mainnet) or be close to completion (dappnet).
3. You should have a clear and concise project description.

## Submission Process

1. Fork the BeamZone repository on GitHub.
2. Create a new branch with a descriptive name (e.g., `add-my-dapp`).
3. Create a new folder with your project's name in lowercase and hyphen-separated (e.g., `my-awesome-dapp`).
4. Inside your project's folder, add the following files:
   - `metadata.json` (details on publisher keys, developer contact info, category, see below for structure)
   - `README.md` (project description with self-contained images, text, and markdown styling)
   - `assets/` folder:
      - `preview-{1,6}.png` App presentation banners, up to 6. (Strict size: 1200x628 pixels)
      - `logo.{svg,png}` App logo (if PNG, strict size: 256x256 pixels)
      - any other material you want to use in your `README.md`
5. Commit your changes and push the new branch to your forked repository.
6. Create a pull request from your new branch to the main branch of the BeamZone repository.
7. In the pull request description, provide a summary of your project and any additional information that may be helpful for the review process.

### `metadata.json` Structure

```ts
interface AppInfo {
  app: {
    name: string; // Name of your app
    description: string; // Short description of your app
    category: string; // Category of your app: DEX, Charting, NFTs, Stablecoin, Naming Service, Lending and Borrowing...
    x?: string; // Optional: X profile link
    github?: string; // Optional: Link to the app's GitHub
    website?: string; // Optional: Website of your app or relevant information (forum post, whitepaper...)
  };
  developer: {
    name: string; // Name of the developer
    key: string; // Your publisher key
    email?: string; // Optional: Email to contact the developer
    privacyPolicy?: string; // Optional: A link to your privacy policy. Privacy policy is required if your DApp call external servers
  };
}
```

Example can be seen in the [Nephrite folder](./nephrite)

## Review Process

The Beam team will review your submission and provide feedback or request changes if necessary. If your project meets the guidelines and criteria, it will be approved and merged into the BeamZone DApp store.

Thank you for your interest in joining the Beam ecosystem!
