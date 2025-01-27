# nextjs-docker-template

This project is a template for Next.js that can build and run in a Docker container.

## Set up your package manager

By default, this project uses `bun` as the package manager. If you prefer a different package manager, follow these steps:

1. Delete the `bun.lockb` file

```bash
rm bun.lockb
```

2. Install dependencies using your preferred package manager

- For `npm`:

```bash
npm install
```

- For `yarn`:

```bash
yarn install
```

- For `pnpm`:

```bash
pnpm install
```

- For `bun`:

```bash
bun install
```

## Build your container

```bash
docker build -t nextjs-docker-template .
```

## Run your container

```bash
docker run -p 3000:3000 nextjs-docker-template
```
