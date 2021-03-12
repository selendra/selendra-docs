## Setup Environment

### Introduction
Selendra is based on Substrate. We support ink!, an [eDSL](https://wiki.haskell.org/Embedded_domain_specific_language) that uses Rust programming language to write WebAssembly-based Smart contract. 

Learn more from Parity Technologies: https://substrate.dev/substrate-contracts-workshop/#/

### Prerequisites

#### Arch Linux
```
pacman -Syu --needed --noconfirm cmake gcc openssl-1.0 pkgconf git clang
export OPENSSL_LIB_DIR="/usr/lib/openssl-1.0"
export OPENSSL_INCLUDE_DIR="/usr/include/openssl-1.0"
```

#### Ubuntu/Debian
To execute the following commands, use the terminal shell:
```
sudo apt update
# May prompt for location information
sudo apt install -y cmake pkg-config libssl-dev git build-essential clang libclang-dev curl libz-dev
```

#### macOS
Open the terminal and execute the following commands:

```
# Install Homebrew if necessary https://brew.sh/
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# Make sure Homebrew is up-to-date, install openssl and cmake
brew update
brew install openssl cmake
```

#### Latest Nightly
Use the terminal shell to perform the following commands:
```
rustup update
rustup update nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
```
#### ink! CLI
The final tool we will be installing is the ink! command line utility which will make setting up Substrate Smart contract projects easier.

With Cargo, you can install the utility:

```
cargo install cargo-contract --force
```
Use the *--force* to ensure you are up to date cargo-contract version.

To explore available commands, you can use Cargo contract *--help*.


### Setting Up a Indracore Node
Make sure you have run Node read for your contract to be deployed. If you have not installed the Node yet, following the [Setting Up Local Node](https://docs.selendra.org/Maintain/guides-how-to-setup-indracore-local-node)

### We Want to Hear From You

If you have any feedback regarding deploying Smart contract on your project, feel free to contact us via our Telegram group [here](https://t.me/selendraorg).