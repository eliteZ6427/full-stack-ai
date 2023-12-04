# Full stack AI

Build a full stack Next.js app with an AI prompt.

Example:

```bash
export OPENAI_API_KEY=...
npx @alephmatic/full-stack-ai gen "Build a clone of Twitter called WhaleCast where people cast instead of tweet. Allow users to follow one another and to like casts. Use GitHub for log in. Charge users a monthly fee for premium functionality."
```

Then `cd` into the newly created app folder, set the environment variables and in the `.env` file and run `npm run dev` to see your app live in the browser at [http://localhost:3000](http://localhost:3000).

You can install the package globally and run as follows:

```bash
pnpm i -g @alephmatic/full-stack-ai
export OPENAI_API_KEY=...
fsai gen "Build a clone of Twitter called TigerCast where people cast instead of tweet. Allow users to follow one another and to like casts. Use GitHub for log in. Charge users a monthly fee for premium functionality."
```

Under the hood this project uses [Kirimase](https://github.com/nicoalbanese/kirimase).

## Run locally

```bash
pnpm i
export OPENAI_API_KEY=...
npx tsx src/index.ts gen "Build a clone of Twitter called TigerCast where people cast instead of tweet. Allow users to follow one another and to like casts. Use GitHub for log in. Charge users a monthly fee for premium functionality."
```
