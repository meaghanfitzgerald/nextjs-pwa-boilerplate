I created this boilerplate for a Progressive Web Application that uses Next.js framework because many of the tutorials I found online left out important information about options in the `_document.tsx`, `mainfest.json`, and the `next.config.js` files. [This youtube tutorial](https://www.youtube.com/watch?v=ARNN_zmrwcw) had the most up-to-date information at the time, and the comments below were my best resources for creating a PWA with [`next-pwa`](https://www.npmjs.com/package/next-pwa) library and nextjs. Hope this is helpful!

## To Set Up Your Own Progressive Web App with Next.js

Fork this repo, clone to your machine, and when in the root folder, run `npm install`.

If you want to immediately compile and view the boilerplate app on your machine, run:
- `npx next build`
followed by
- `npx next start`
- navigate to `localhost:3000` in your chrome browser (or any browser run with chromium), and view the app. 

To import as a desktop app, click the icon seen here: 

<img width="510" alt="image" src="https://user-images.githubusercontent.com/99047250/213308384-370d7664-2f28-48de-a64a-dd896c8ad528.png">

To customize, edit the provided `manifest.json` file in the `public` folder, and run through the workflow above. Be sure to have the `display` option set to "standalone" or "fullscreen". 

Please feel free to leave feedback, comments, or links to issues so that this boilerplate can be kept up-to-date.



This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
