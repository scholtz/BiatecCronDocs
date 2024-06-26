# Biatec Scheduler

Biatec scheduler is timed based executor of the AVM smart contract.

Scheduler use cases are:

* Standing payment order - Execute periodic payment to another algorand account
* DCA - Buy your desired token token at periodic intervals
* Conditional purchase if token price is above or below desired price

Decentralized scheduler consists of the frontend blockly code builder where anyone can build their own logic. Person selects the start time and period how often the tasks should execute and execution fee in tokenized gold. User deposits funds to the escrow account. Anyone can execute the tasks from the escrow account when the times comes. Each execution event is logged in the escrow account transactions.

Endpoints:

* [https://www.a-wallet.net](https://www.a-wallet.net) - Algorand wallet with standing order option
* [https://scheduler.biatec.io](https://scheduler.biatec.io) - Smart contract blockly builder
* [https://api-scheduler.biatec.io](https://api-scheduler.biatec.io) - API endpoint to build smart contract from biatec yaml or json code
* [https://docs-scheduler.biatec.io](https://docs-scheduler.biatec.io) - Documentation
* [https://www.biatec.io](https://www.biatec.io) - List of all of our products - Concentrated liquidity AMM DEX, Aramid bridge,  Vote Coin, AWallet, Accounting services ...&#x20;

**Disclaimer**: Biatec scheduler is quite new product (launched April 2024) and may still contain errors or the future versions may not be compatible with the older versions. Always check the generated smart contract source code if it is compliant with your intended use. YOU are responsible for any and all actions you do, noone else is liable. You may loose money using this service if not configured properly. Remember that with great power comes great responsibility, your keys, your security, your crypto.\


