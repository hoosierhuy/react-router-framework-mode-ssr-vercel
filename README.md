# This is the Vercel version of the app on the Main branch

100 percent server-side rendered, including data fetching and mutations (POST request), with TypeScript and TailwindCSS 4.x.

Now, you will need to create a free tier Vercel account, and you have to set up Vercel CLI to deploy this app easily from the command line.

This app is deployed here: [https://react-router-framework-mode-ssr-ver.vercel.app/](https://react-router-framework-mode-ssr-ver.vercel.app/)

YouTube video: https://youtu.be/xIXBA9JzYMM

## Project folder structure

RRv7-Vercel/
├── package.json
├── README.md
├── vite.config.ts
├── react-router.config.ts
├── tsconfig.json
│
├── app/
│   ├── root.tsx
│   ├── app.css
│   ├── routes.ts
│   ├── components/
│   │   └── Navbar.tsx
│   ├── routes/
│   │   ├── index.tsx
│   │   ├── CatchAll.tsx
│   │   └── products/
│   │       ├── index.tsx
│   │       ├── [id].tsx
│   │       └── new.tsx
│   └── types/
│       └── product.ts
│
├── public/
│   └── favicon.ico
│
└── build/ (generated)
    ├── client/
    └── server/

If this repository helped you, please consider giving it a star ⭐️. And if you would like to contribute to my [coffee fund](https://www.paypal.com/donate/?business=XNPNP5FWN4B2A&no_recurring=0&item_name=I+provide+free+computer+science+training+to+everyone&currency_code=USD).  Thank you!
