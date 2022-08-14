## Cloning for local use

First, install [degit](https://www.npmjs.com/package/degit) 

```bash
npm install -g degit
# or
yarn global add degit --prefix /usr/local
```

Then in the location where you want to place the project, run
```bash
degit https://github.com/Irene-24/NextJS-Storybook-Tailwind-and-TS-setup [PROJECT-NAME]
```

This will clone repo, without any git history attached.

Update the `"name"` field in the package.json file to match your [PROJECT-NAME] like so

```json
{
  "name": "project-name-goes-here",
  ...

```

Don't forget to install your dependencies with `yarn` or `npm`


Finally, initialize and commit you initial changes
```bash
git init 
```

```bash
git add . 
```

```bash
git commit -m "Initial commit" 
```



________________________________________________________

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
