### Setup Environment

#### Introduction
Selendra is based on Substrate. we support ink!, an [eDSL](https://wiki.haskell.org/Embedded_domain_specific_language) to write WebAssembly based smart contracts using the Rust programming language. 

Learn more from Parity Technologies refer to this page: https://substrate.dev/substrate-contracts-workshop/#/

#### Prerequisites

#### Arch Linux
```
pacman -Syu --needed --noconfirm cmake gcc openssl-1.0 pkgconf git clang
export OPENSSL_LIB_DIR="/usr/lib/openssl-1.0"
export OPENSSL_INCLUDE_DIR="/usr/include/openssl-1.0"
```

#### Ubuntu/Debian
Use a terminal shell to execute the following commands:
```
sudo apt update
# May prompt for location information
sudo apt install -y cmake pkg-config libssl-dev git build-essential clang libclang-dev curl libz-dev
```

#### macOS
Open the Terminal application and execute the following commands:

```
# Install Homebrew if necessary https://brew.sh/
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# Make sure Homebrew is up-to-date, install openssl and cmake
brew update
brew install openssl cmake
```

#### Latest Nightly
Use a terminal shell to execute the following commands:
```
rustup update
rustup update nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
```
#### ink! CLI
The final tool we will be installing is the ink! command line utility which will make setting up Substrate smart contract projects easier.

You can install the utility using Cargo with:

```
cargo install cargo-contract --force
```
Use the --force to ensure you are updated to the most recent cargo-contract version.

You can then use cargo contract --help to start exploring the commands made available to you.

### Setting Up a Indracore Node
Make sure you have running node read for your contract to be deployed. If you had not installed the node yet following the [Setting Up Local Node](https://docs.selendra.org/Maintain/guides-how-to-setup-indracore-local-node)

#### We Want to Hear From You

If you have any feedback regarding deploying Smartcontract on your project, feel free to reach out through our official community at Telegram group [here](https://t.me/selendra_sel).