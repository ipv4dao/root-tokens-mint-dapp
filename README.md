## Installation 🛠️

If you are cloning the project then run this first, otherwise you can download the source code on the release page and skip this step.

```sh
git clone https://github.com/ipv4dao/root_tokens_mint
```

Make sure you have node.js installed so you can use npm, then run:

```sh
npm install
```

Please note that this repository is not tested with node.js versions higher than 16.20.
If you're using the later versions, please do the following:

Install NVM from the link below:
https://github.com/nvm-sh/nvm#installing-and-updating

Install a compatible Node.js version:

```sh
nvm install 16
```

Set the newly installed version as the active one:

```sh
nvm use 16
```

After changing the version of Node.js, remove your node_modules folder and package-lock.json file:

```sh
rm -rf node_modules
rm package-lock.json
```

Reinstall your project dependencies:
npm install

## Usage ℹ️

Most of the configurable parameters are located in `public/config/config.json`

Don't forget to copy the contract ABI from remix and paste it in the `public/config/abi.json` file.

To run on local environment execute:

```sh
npm run start
```

To deploy - create a build:

```sh
npm run build
```

After that you can move the content of the build folder to your external web server.
