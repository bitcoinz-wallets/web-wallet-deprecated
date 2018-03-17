# bitcoinz-wallets.github.io/web-wallet/
BitcoinZ is based on Bitcoin + zkSNARKs and is a decentralized CDD.

Community-driven development (CDD) is a development initiative that provides
control of the development process, resources and decision making authority
directly to groups in the community.

Initial commit is beta, working. The commit is necessary that the community can
review the source code and assure that it is free of error, to commit changes and
updates. Clean-up is needed.

Please post issues, concerns, comments, and pull requests.

BitcoinZ Web Wallet a client-side browser based wallet for BitcoinZ BTCZ based on
MyZENWallet which is the original client-side browser-based wallet for ZenCASH.

# Adapted
`node_modules/btczjs` for Zcash tx

# Running locally
Download one of the releases, goto the `dist` folder and double click `index.html`

# Install Dependencies
```
yarn install
```

or with npm
```
npm install
```

# Dev
```
yarn watch # watch and regenerate files
yarn start # start local host server
```

# Deploying to github

Use webpack to create a new release in the `dist` folder:
```
./scripts/webpack.sh
```

Next, save changes to git:
```
git commit -a
```

Finally, deploy the site:
```
./scripts/deploy.sh
```
