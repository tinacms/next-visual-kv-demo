This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

Use the following link to directly deploy this demo to Vercel. You will need a Vercel account and a GitHub personal access token (PAT) with access to the repository (once it has been created).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Ftinacms%2Fnext-visual-kv-demo&env=GITHUB_PERSONAL_ACCESS_TOKEN,NEXTAUTH_SECRET,NEXTAUTH_CREDENTIALS_KEY&envDescription=Create%20a%20new%20GitHub%20PAT%20at%20https%3A%2F%2Fgithub.com%2Fsettings%2Fpersonal-access-tokens%2Fnew%20with%20content-access.%20For%20more%20information%20on%20env%20setup%2C%20see%20readme%3A%20https%3A%2F%2Fgithub.com%2Ftinacms%2Fnext-visual-kv-demo&envLink=https%3A%2F%2Fgithub.com%2Ftinacms%2Fnext-visual-kv-demo%2Fblob%2Fmain%2FREADME.md&project-name=next-visual-kv-demo&repository-name=next-visual-kv-demo&stores=%5B%7B%22type%22%3A%22kv%22%7D%5D&)

### Environment Variable Setup

After the repository is created, you will need to do the following steps to get the environment variables setup:

1. Create a new [GitHub personal access token (PAT)](https://github.com/settings/personal-access-tokens/new) with content access to the new repository and copy the token as the value for the `GITHUB_PERSONAL_ACCESS_TOKEN` environment variable.
2. Fill out the `NEXTAUTH_SECRET` environment variable with a random string.
3. Fill out the `NEXTAUTH_CREDENTIALS_KEY` environment variable with the key you want to use for storing user credentials in the KV database (i.e. `tinacms_users`).

### Local Development

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
