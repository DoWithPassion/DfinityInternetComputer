# DfinityInternetComputer

## Overview of Internet Computer
  - If we want to build any website/app/enterprise system/any internet service we need to use proprietary legacy stack.(Databases, Webservers,Kuberneets, cloud services,DNS, IP,WIFI, Firewall and many) but they are some way insecure.
  - This causes enormous stack to build for entrepreneur.
  - Internet computer is the extension of the public internet and upgrades the public internet so that it provides not just global connectivity but also revolutionary shared computer.
  - This transformation of the internet is achieved through a new open protocol called ICP(Internet Computer Protocol).
  - **Internet computer** is the replacement for proprietary legacy stack, which is created by independent datacenters running ICP.
  - This forms a new kind of blockchain computer which has unbounded capacity and delivers performance that rivals the traditional cloud.
  ### Canisters
    - The internet computer reimagined s/w as interoperable compute units called **Canisters**.
    - Smart contracts are simply programs stored on a blockchain that run when predetermined conditions are met.
    - These are the evolution of smart contracts, they consists of a bundle of web assembly bytecode and the memory in which the bytecode runs.(Both code and state)
    - Just like smart contracts, canisters are tamper proof and unstoppable, but canisters are also scalable and parallelizable.
    - Canisters also run on web speed and highly efficient.
  - Internet Computers provides a way to build anything(Websites,Open Internet services, Enterprise systems, Pan Industry Platforms...), No AWS, No Servers, No CDNs, No DBs and No Firewall are required.
  - We can create new systems and services on the internet computer in two simple steps.
    1. Write code in any programming language and it will be compiles down to a web assembly canister such as rust and motoko.
    2. Simply Upload the canisters that you have created to the internet computer via ICP.
## Internet Computer
  - Basically, An extension of the internet that allows us to build, deploy and host s/w directly on the internet without things like DBs or third party cloud providers.
  - It simplifies the techstack in the developer experience itself.
  - Open Internet Services is lot like the apps and s/w that we all use today, but behind the scenes there is a network of canisters that are speaking to each other on the internet computer.
  - The Internet Computer extends the functionality of the public Internet so that it can host backend software, transforming it into a global compute platform.
  - The Internet Computer is formed by an advanced decentralized protocol called ICP (Internet Computer Protocol) that independent data centers around the world run to combine the power of individual computers into an unstoppable seamless universe where internet native software is hosted and run with the same security guarantees as smart contracts.
  - It is integrated with Internet standards such as DNS, and can server user experiences directly to Web browsers and smartphones.
## Canisters
  - Software canister is a bundle of code and data that runs on the internet computer.
  - It can be partially like processes in a operating systems.
  - A canister is like a smart contract because its execution is governed by secure protocol called Internet Computer Protocol (ICP).
  - Therefore it is a tamperproof, which means its state can only be modified only through the messages included in the blockchain and also governed by ICP.
  - As the execution of canister code is fully deterministic, a canister's state can be audited in a cryptographically secure way by inspecting the messages in the blockchain.
  - Canister has all the capabilities of the traditional smart contract.
  - In contrast to smart contracts, the canisters have performance characterstics that makes it possible to use them to build internet scale software services.
  - A canister is like a smart contract that scales.
  - It consists of a private state that can only be modified by the canister itself and had a single thread of execution, so it doesnot need lock-based synchronization.
  - It communicates with other canisters through asynchronous messages and also able to create other new canisters.
  - Canisters on the internet computer can have a bi-directional message passing.
  - A single canister has only one thread of execution of updates. But the internet computer executes a potentially massive number of canisters in parallel. 
  - A canister can serve hundreds of queries concurrently acheiving a throughput in the order of thousands of queries per second and latency measured in milliseconds.
  - Internet computer schedules the execution of canisters, similarily to os scheduler which wakes up the process.
  - Internet computer maintains the state behalf of the canister by keeping track of balances of tokens and cycles its outstanding calls and much more.
  - Canisters cant directly modify the balances of tokens for obvious reasons.
  - Internet computer provides APIs to make payments call out to other canisters, create or manage canisters, manage permissions and get the system time and for other actions.
  - When a canisters malfunction, it will not crashed instead its state is rolled back to what it was before the current message has started execution.
  - A canister is like a process that running on the internet computer's operating system.

## Development
- DFX, a command line tool to interact with internet computer.
- SDK, Software Development Kit to create projects, build the code part of your canister, send the canister up to the internet computer and interact with it.
  - To install sdk, [Dfinity SDK](https://sdk.dfinity.org/docs/index.html)
  - To setup linux command line for windows, [Click here, to Follow this official doc](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
  - Copy command and paste it in the linux terminal `sh -ci "$(curl -fsSL https://sdk.dfinity.org/install.sh)"`
  - To check the version by `dfx --version` and for help `dfx help`
  - To create a new project run `dfx new project`
  - To check with canister run `dfx canister --help`
  - 
