ChuneSpot - A music streaming app built with Next.js, Supabase, and Stripe

ChuneSpot is a music streaming web application inspired by Spotify and SoundCloud. It allows users to stream music and like songs. It also enables artists to upload and host their music to share with fans.

This project was built using:

Next.js - For server-side rendering and routing
Supabase - For user management and database
Stripe - For subscriptions and payments
React Hooks - For state management
Tailwind CSS - For styling
Some key features include:

User authentication with Supabase
Music playback with custom audio player
Music uploads and hosting via Supabase storage
Like songs
Search songs by title and filter by artist
Premium subscriptions with StripeCheckout
Responsive design with TailwindCSS
This app demonstrates fetching data from Supabase, integrating payments with Stripe, building reusable React components, managing state with React Hooks, and implementing responsive design with Tailwind.

The code is structured into intuitive folders and components for maintainability and extensibility. Custom hooks encapsulate complex logic. Typescript provides type safety.

Overall, this project showcases modern web development techniques with Next.js and Supabase to build a fast, dynamic music streaming application.

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
