# Loans collateralized by Real Estate NFTs

[<img align="center" alt="frontend" width="500px" src="https://raw.githubusercontent.com/EnriqueGS88/blog/main/img/nftLoans_frontend.png" />][frontend]


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


# Installation

Go to the project directory: _./nft-frontend-app_

Install the dependencies:

```sh
git clone <github url>
npm install
```

Then run the webapp on localhost
```sh
npm start
```

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.



### Deployment

Compile contracts (creates artifacts folder with ABIs)
```sh
npx hardhat compile
```

Start local test node:
```sh
npx hardhat node
```

Deploy SC:
```sh
npx hardhat run scripts/deploy.js --network localhost
```

Import accounts in Metamask:
Use network Localhost 8545 and import with the private key


## Auxiliar libraries
For UI components:
https://github.com/ConsenSysMesh/rimble-ui 

Connect with different wallets:
https://github.com/Web3Modal/web3modal


[frontend]: https://github.com/EnriqueGS88/nftLoans