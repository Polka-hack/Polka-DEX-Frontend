# PolkaDEX UI

[![CircleCI](https://circleci.com/gh/subdarkdex/subdex-ui.svg?style=shield)](https://circleci.com/gh/subdarkdex/subdex-ui)

### Installation

The code can be installed using [git](https://git-scm.com/) and [yarn](https://yarnpkg.com/).

```bash
# Clone the repository
git clone https://github.com/Polka-hack/Polka-DEX-Frontend.git
cd Polka-DEX-Frontend
yarn
```

## Usage

Before you start the frontend locally, you need to start the SubDEX parachain node following the [README.md](https://github.com/subdarkdex/subdex-xc-network).

Then you can start the app in development mode to connect to a locally running node

```bash
yarn start
```

You can also build the app in production mode,

```bash
yarn build
```
and open `build/index.html` in your favorite browser.
