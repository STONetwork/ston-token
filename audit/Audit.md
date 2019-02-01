
# Summary of the Audit Report

## Introduction of SlowMist

The SlowMist Security Team received the STON team's application for smart contract security
audit of the STON Token on January 25, 2019. The following are the details and results of this
smart contract security audit:

### Audit Focus Item 
Identification of potential security flaws/attacks including :
* Overflow Audit
* Race Conditions Audit
* Authority Control Audit
    * Permission vulnerability audit
    * Excessive auditing authority
* Safety Design Audit
    * Zeppelin module safe use
    * Compiler version security
    * Hard-coded address security
    * Fallback function safe use
    * Show coding security
    * Function return value security
    * Call function security
* Denial of Service Audit
* Gas Optimization Audit
* Design Logic Audit
* “False Deposit” vulnerability Audit
* Malicious Event Log Audit
* Uninitialized Storage Pointers Audit
* Arithmetic Accuracy Deviation Audit

### Audit Summary Report 
| Item Description | Result |
|     :---:       |     :---:       |
| Audit Result | Passed |
| Audit Number | 0X001901280001 |
| Audit Date | January 28, 2019 |
| Audit Team | SlowMist Security Team |

This is a token contract that does not contain the tokenVault section. 
The contract does not have the Overflow, the Race Conditions issue. 
**The comprehensive evaluation contract is no risk.**

