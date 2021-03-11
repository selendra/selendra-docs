### Calling Your Contract

### Smart contract messages

To communicate with Smart contracts. We use "messages".
![Calling Contract](../assets/calling-contract-01.png "Calling Contract")

It's possible to pass two kinds of messages:
 - messages that change a smart contract's state should be sent as transactions;
 - messages that don't change a state could be called by using RPC calls.

Let's try to read our smart contract value by ```get()``` message call.

![Calling Contract get() value](../assets/calling-contract-02.png "Calling Contract get() value")

Second, let's change a smart contract state by sending a "message", send flip() message that flips smart contract boolean flag.

![Flip call is a transaction.](../assets/calling-contract-03.png "Flip call is a transaction.")

Verify the result:
![Call last Flip value.](../assets/calling-contract-04.png "Call last Flip value.")

Using these two kinds of messages, your DApp can easily write and read the smart contract data. Have fun!

We Want to Hear From You

If you have any feedback regarding deploying Smartcontract on your project, feel free to reach out through our official community at Telegram group [here](https://t.me/selendra_sel).