### Creating an ink! Project
We are going to use the ink! CLI to generate the files we need for a Substrate smart contract project.

Make sure you are in your working directory, and then run:

```
cargo contract new mycontract
```
This command will create a new project folder named mycontract which we will explore:

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
You will see at the bottom of the source code there is a simple test which verifies the functionality of the contract. We can quickly test that this code is functioning as expected using the off-chain test environment that ink! provides.

In your project folder run:

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
We Want to Hear From You

If you have any feedback regarding deploying Smartcontract on your project, feel free to reach out through our official community at Telegram group [here](https://t.me/selendra_sel).