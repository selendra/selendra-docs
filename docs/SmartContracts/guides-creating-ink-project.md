### Creating an ink! Project
We are going to use ink! CLI to generate the files that we need for a Substrate Smart Contract project.

Make sure you are in your working directory and then run:

```
cargo contract new mycontract
```
This command will create a new project folder named ***mycontract*** which we will explore:

```
cd mycontract
```
ink! Contract Project

```
.
├── Cargo.toml              <----- Rust Dependencies and ink! Configuration
└── lib.rs                  <-- Contract Source Code

0 directories, 2 files

```
### Testing Your Contract
At the bottom of the source code, you can see a simple test uses for verifying the functionality of the contract. You can also quickly test this code using ink! **off-chain test environment** if it is functioning as expected.

In your project folder, run:
```
cargo +nightly test
```

To which you should see a successful test completion:


```
running 2 tests
test mycontract::tests::default_works ... ok
test mycontract::tests::it_works ... ok

test result: ok. 2 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.00s

```
### We Want to Hear From You

If you have any feedback regarding deploying Smart contract on your project, feel free to contact us via our Telegram group [here](https://t.me/selendraorg).