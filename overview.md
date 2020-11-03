# Overview

## algoDEA

"algoDEA"  provides end to end development lifecycle on Algorand blockchain using IntelliJ IDE. Using this plugin, developer can create and test both stateless and stateful smart contract directly from their IntelliJ IDE. It also provides support for ASA creation, management and transfer.

The account management module in the plugin provides a simple way for the developers to manage their test accounts in one place.

The plugin is currently available in JetBrains Official Plugin Repository [https://plugins.jetbrains.com/plugin/15300-algodea-algorand-integration](https://plugins.jetbrains.com/plugin/15300-algodea-algorand-integration)

The latest plugin binary can be also downloaded from [https://github.com/bloxbean/algodea/releases](https://github.com/bloxbean/algodea/releases)

**Git Repository :** [https://github.com/bloxbean/algodea](https://github.com/bloxbean/algodea)

The followings are the list of features currently supported by the plugin.

#### **Features**

* Algorand Smart Contract Project type
* Code Completion, Syntax Highlighter and other editor level support for TEAL file
* Create Stateless & Stateful Smart Contract
* Algorand Node support
  * Custom node
  * Purestake.io
* TEAL Compile using "goal" and algod REST api endpoint 
* Account Management
  * Create account
  * Create Multi-Sig account
  * List Account
  * Account Details
  * Dump Account
* Stateless Smart Contract
  * Generate Logic sig and multi-sig Logic Sig 
  * Send Logic Sig transactions
* Stateful Smart Contract 
  * Create Application
  * Call, OptIn, CloseOut, Clear, ReadState
  * Delete Application
  * Update Application
* Asset Management
  * Creat, Modify, OptIn, Freeze, UnFreeze, Revoke, Destroy
* Transfer
  * Algo, ASA

**TODO**

* TEAL debugger
* PyTEAL support
* Atomic Transfer

