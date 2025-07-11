# Ultimate Quick Stack

This is a Next.js boilerplate project that integrates Next.js, Tailwind CSS, MongoDB (with Mongoose), Auth0, and Stripe. It is a great starting point for building full-stack applications with Next.js.

## Tech Stack

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Auth0](https://auth0.com/)
- [Stripe](https://stripe.com/)

## Getting Started

First, clone the repository and navigate to the project directory:

```bash
git clone https://github.com/MuhammadTanveerAbbas/nextjs-stack-boilerplate.git
cd nextjs-stack-boilerplate
```

Next, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

Next, create a `.env.local` file in the root of the project and add the following environment variables:

```bash
# Auth0
AUTH0_SECRET=
AUTH0_ISSUER_BASE_URL=
AUTH0_CLIENT_ID=
AUTH0_CLIENT_SECRET=
AUTH0_REDIRECT_URI=

# MongoDB
MONGODB_URI=

# Stripe

STRIPE_SECRET_KEY=
STRIPE_PRICE=

# Frontend Variables

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## License

This project is licensed under the MIT License.
