# OP4 web using svelteKit + Prisma + sqlite3
repo (private): https://github.com/me7/my-app/

## step
- install and test svelteKit
```
npm init svelte my-app
cd my-app
pnpm i
pnpm dev
```
- install and test prisma
```
pnpm i -D prisma
pnpx prisma init
// edit .env and schema.prisma
pnpx prisma db pull
// install prisma extension for syntax highlight
```
- gen prima client
```
pnpm i @prisma/client
pnpx prisma generate

```

# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte

# create a new project in my-app
npm init svelte my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
