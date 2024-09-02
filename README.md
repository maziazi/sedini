# Create T3 App

This is a [T3 Stack](https://create.t3.gg/) project bootstrapped with `create-t3-app`.

## What's next? How do I make an app with this?

We try to keep this project as simple as possible, so you can start with just the scaffolding we set up for you, and add additional things later when they become necessary.

If you are not familiar with the different technologies used in this project, please refer to the respective docs. If you still are in the wind, please join our [Discord](https://t3.gg/discord) and ask for help.

- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [Drizzle](https://orm.drizzle.team)
- [Tailwind CSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

Firstly you need this tech, that are required to run on local:

1. Docker/Podman - Used for the database.
2. node js (^20 is recomended).
3. npm/yarn/pnpm/others (I will use pnpm for this guide).

Step to run on local (first time only):

1. Clone this repostiory git clone git@github.com:maziazi/sedini.git
2. Move into the directory cd sedini
3. Install all the dependancy pnpm install
4. Move into the prisma directory cd prisma
5. Run the docker compose file docker compose up
6. populate the env variable cp .env.example .env
7. Run the Pisma migration pnpm prisma db push
8. Finaly the seeder pnpm prisma db seed

After this step, you only need to start the server using:

pnpm dev

## Learn More

To learn more about the [T3 Stack](https://create.t3.gg/), take a look at the following resources:

- [Documentation](https://create.t3.gg/)
- [Learn the T3 Stack](https://create.t3.gg/en/faq#what-learning-resources-are-currently-available) — Check out these awesome tutorials

You can check out the [create-t3-app GitHub repository](https://github.com/t3-oss/create-t3-app) — your feedback and contributions are welcome!

## How do I deploy this?

Follow our deployment guides for [Vercel](https://create.t3.gg/en/deployment/vercel), [Netlify](https://create.t3.gg/en/deployment/netlify) and [Docker](https://create.t3.gg/en/deployment/docker) for more information.
