### Building Your Contract
Run the following command to compile your smart contract::

```
cargo +nightly contract build
```
This special command will turn your ink! project into a Wasm binary, a metadata file (which contains the contract's ABI) and a .contract file which bundles both. This .contract file can be used for deploying your contract to your chain. If all goes well, To which you should see a successful test completion:

```
Original wasm size: 19.1K, Optimized: 2.5K

Your contract artifacts are ready. You can find them in:
/home/ayoung/project/mycontract/target/ink

  - mycontract.contract (code + metadata)
  - mycontract.wasm (the contract's code)
  - metadata.json (the contract's metadata)
```

you should see a target folder which contains these files:

```
└── metadata.json
└── mycontract.contract
└── mycontract.wasm
```
We Want to Hear From You

If you have any feedback regarding deploying Smartcontract on your project, feel free to reach out through our official community at Telegram group [here](https://t.me/selendra_sel).