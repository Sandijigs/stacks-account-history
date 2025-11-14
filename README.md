# Stacks Account History

A Next.js application for viewing Stacks blockchain account history and transactions.

## Features

- **Account History**: View transaction history for any Stacks address
- **Wallet Integration**: Connect with Stacks Connect for browser extension wallets
- **WalletConnect Support**: Mobile wallet compatibility with WalletConnect SDK v2 (Project ID: 6b87a3c69cbd8b52055d7aef763148d6)
- **Address Search**: Look up any Stacks address without connecting a wallet
- **Transaction Details**: Comprehensive transaction information display

## WalletConnect Integration

This project includes **WalletConnect SDK v2** dependencies for future mobile wallet integration:

### Current Status
- WalletConnect dependencies installed
- Environment configured with WalletConnect Project ID
- Ready for WalletConnect implementation

### Planned Features
- Mobile wallet connection via QR code
- View account history from mobile wallets
- Secure session management
- Multi-wallet support (Xverse, Leather, etc.)

### WalletConnect Configuration
The `.env.local` file includes:
```bash
NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID=6b87a3c69cbd8b52055d7aef763148d6
```

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
