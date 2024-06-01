## Getting started

To get started with this template, first install the npm dependencies:

```bash
npm install
```

Next, create a `.env` file in the root of your project and set the `NEXT_PUBLIC_SITE_URL` variable to your site's public URL:

```
NEXT_PUBLIC_SITE_URL=https://example.com
```

Next, run the development server:

```bash
npm run dev
```

Finally, open [http://localhost:3000](http://localhost:3000) in your browser to view the website.

## Deployment (note to self)
This repo is already connected to vercel, so pushing to the main branch will deploy to production on vercel, so no need to do `vercel && vercel --prod`.
