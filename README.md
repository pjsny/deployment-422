# mobile-backend

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.2.4. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.

Deploys a docker image to a digital ocean droplet. Digital Ocean droplet must have docker installed.

The [github action](.github/workflows/deploy.yml) builds a new image on push then pushes the file to digital ocean via SSH
