# Algorand Project Structure

The Algorand project's standard directory layout :

![](.gitbook/assets/package-structure%20%281%29.png)

| Directory / File | Description |
| :--- | :--- |
| **src** | TEAL program files |
| **algo-package.json** | Algorand package json files. Every algorand project should have this file at top level. |
| **generated-src** | Any generated source files from original TEAL programs are stored here. Example: If a TEAL program uses variables \(VAR\_TMPL\_\*\) inside the source code, the plugin generates the final source files with variable values under this folder. Also, the TEAL file generated during PyTeal compilation is  created in this folder. |
| **build** | Build folder. The compiled binaries and other files generated from source are stored here. |
| **build/toks** | Compiled TEAL file |
| **build/lsigs** | Logic Sig files generated from TEAL program |
| **build/txns** | Exported transaction files |
| **build/dryrun** | Dry Run output files |

