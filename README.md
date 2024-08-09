# Decentralized News Service (Block Magic Hackathon 2024)
Building a decentralized news service with Chainlink Functions and Hacker News API

## Tutorial: "Blockchain Masterclass for JavaScript Developers"
https://functions.chain.link/playground/b44eba0d-4498-48c5-a675-81780fc6873e

## Contract Address
```
0xb835b0F63F411482B4EA0cfbD47Fe6BD6949AD70
```
## Chainlink Functions Subscription
https://functions.chain.link/sepolia/2489

## Steps
* Prerequisite: Have the smart contract deployed and run sendRequest a few times
* Clone the repository
* Run npm install within the frontend folder
* Create a .env file in the project root folder with the following content:
```
# RPC for sepolia (Change this if you want to use a different chain)
PROVIDER_URL="https://rpc.sepolia.org"

# CHANGE THIS TO YOUR CONTRACT ADDRESS!
CONTRACT_ADDRESS="0xb835b0F63F411482B4EA0cfbD47Fe6BD6949AD70"
```
* Run npm run dev in the terminal from the frontend folder
* Open page at http://localhost:4321 or with the given port if you changed it

# Astro Starter Kit: Minimal

```sh
npm create astro@latest -- --template minimal
```


##  Project Structure

Inside of your Astro project:

```text

├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

##  Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |


