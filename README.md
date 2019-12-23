![picture alt](https://www.liv-ex.com/wp-content/uploads/2019/02/FHL-Logo-Colour.png "FHL")

# About
Visual Studio Code FHL Snippets is a visual studio snippets file containing shorthand codes for quicker entry of frequently used code fragments.
All functions are available by starting to type 'function' in the editor.

#Installation
1. (If you already have a snippets file skip this step.) Create a new snippet file by navigating to File > Preferences > User Snippets > New Global Snippets File
2. Copy the contents of the FHL Snippets file into your global snippets file.

# Shorthand Codes
type !header to Generate the FHL Script header.

Each shorthand code is idenfitied with a '.' prior to the command.

**User Event**

| Function     | 1.0   | 2.0    |
|--------------|-------|--------|
| beforeLoad   | .uebl | .uebl2 |
| beforeSubmit | .uebs | .uebs2 |
| afterSubmit  | .ueas | .ueas2 |

**Client Script**

| Function       | 1.0   | 2.0    |
|----------------|-------|--------|
| pageInit       | .cspi | .cspi2 |
| saveRecord     | .cssr | .cssr2 |
| validateField  | .csfv | .csfv2 |
| fieldChanged   | .csfc | .csfc2 |
| postSourcing   | .csps | .csps2 |
| lineInit       | .csli | .csli2 |
| validateLine   | .csvl | .csvl2 |
| recalc         | .csr  | .csr2  |
| validateInsert | .csvi | .csvi2 |
| validateDelete | .csvd | .csvd2 |




**Scheduled Script**

| Function | 1.0  | 2.0   |
|----------|------|-------|
| execute  | .sse | .sse2 |

**Suitelet**

| Function  | 1.0  | 2.0   |
|-----------|------|-------|
| onRequest | .sor | .sor2 |

**Map/Reduce**

| Function     | 1.0 | 2.0    |
|--------------|-----|--------|
| getInputData | N/A | .mrgid |
| map          | N/A | .mrm   |
| reduce       | N/A | .mrr   |






