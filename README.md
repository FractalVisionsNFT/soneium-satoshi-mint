## Steps for deploying a NFT minting template

- First, check if you have the correct client Id or secret key in ``` .env.local``` 

- If the clientId or secret key is to be edited, change it in the ``` .env.local``` file

- Then, edit this [Constants.ts](./src/lib/constants.ts) file to the NFT contract address and NFT chain. The comments in this file will guide you.

- Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
