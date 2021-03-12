### Building Your Contract
Run the following command to compile your smart contract:

```
cargo +nightly contract build
```
This special command will turn your ink! project into a Wasm Binary, a metadata file that contains both the contract's ABI and a .contract file. 

This .contract file can be used for deploying your contract to your chain. If all goes well, you will see a successful test completion.

```
Original wasm size: 19.1K, Optimized: 2.5K

Your contract artifacts are ready. You can find them in:
/home/ayoung/project/mycontract/target/ink

  - mycontract.contract (code + metadata)
  - mycontract.wasm (the contract's code)
  - metadata.json (the contract's metadata)
```

You should see a target folder that contains these files:

```
└── metadata.json
└── mycontract.contract
└── mycontract.wasm
```
### We Want to Hear From You

If you have any feedback regarding deploying Smart contract on your project, feel free to contact us via our Telegram group [here](https://t.me/selendraorg).