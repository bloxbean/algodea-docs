# Overview

**Supported Since : 0.7.0-Beta1**

The plugin provides integration with "tealdbg" to provide debugging support for TEAL smart contracts. Currently, the debugger support is available for the followings:

* Stateless Smart Contract
* Stateful Smart Contract
* Atomic Transfer

When debugger option is chosen for a smart contract transaction, the following steps are done by the plugin :-

* If stateful smart contract, it creates the debugger context \(Dry run dump\) file
* Starts tealdbg with TEAL source file and dry run dump file
* Finds Google Chrome installation and automatically opens the browser for debugging \(If automatic detection is enabled\)

Alternatively, developer can directly use the dry run dump file and debug. The steps are as follows :-

* Create debugger context \(dry run dump\) file from the supported transaction UI
* Right click on the dry run dump file and select "Start TEAL debugger" to start the debugger.

**Note:** IDE automatically finds the Chrome executable and opens it. But this feature is only tested on Mac OS and Windows. For Linux, you may need to configure the Chrome executable path in the "Debugger Configuration" UI.



