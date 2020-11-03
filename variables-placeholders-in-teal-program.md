# Variables/Placeholders in TEAL program

You can define variables or placeholders in your TEAL program. During compilation, the IDE will ask to input values for these variables.

The variable name should always start with a prefix **VAR\_TMPL\_ .** 

**Example:**

```text
#pragma version 2

int VAR_TMPL_AMOUNT
txn Amount
...
...
```

In the above example,  when you compile the TEAL program, you need to enter VAR\_TMPL\_AMOUNT variable value. The IDE automatically detects all variables start with VAR\_TMPL\_ and asks the user for the variable values if required. The IDE then creates the final source file in build/generated\_src folder and then compile the final source file using the configured compiler \(goal or Algorand node\).



