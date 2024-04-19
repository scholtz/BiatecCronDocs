# Executors

Anyone can execute the tasks. Successful executor will receive reward set in the smart contract.

All scheduled tasks are stored in the box storage at the task pool contract.

List of deployed task pool contracts:

* Algorand Testnet: 643872805

Sample executor code is here: [https://github.com/scholtz/BiatecCron/blob/main/src/bin/executor.ts](https://github.com/scholtz/BiatecCron/blob/main/src/bin/executor.ts)&#x20;

This sample executor can be run as [docker image](https://hub.docker.com/r/scholtz2/biatec-cron-executor/tags) or as the [kubernetes deployment](https://github.com/scholtz/BiatecCron/blob/main/k8s/executor/testnet/deployment-main.yaml).

