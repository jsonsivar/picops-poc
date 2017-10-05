# uPort <> PICOPS Comparison

<i>empty cells means information is still yet to be found</i>

## Functionality Fit


| Functionality | PICOPS | uPort |
|---|---|---|
| Digital identity | | |
|--- Identity proxy | N | Y |
|--- Generic attestations (to be used for t&c acceptances) | N | Y |
|--- Recovery/transfer |  | Y |
|KYC| |  |
|--- ID capture| Y | N (to be added in a few weeks) |
|--- US citizenship check| Y| N (to be added in a few weeks) |
|--- China citizenship check| | N (to be added in a few weeks) |
|--- Citizenship check for other sanctioned countries| Y| N (to be added in a few weeks) |
|--- Not named on a sanction list | Y| N (to be added in a few weeks) |
|--- Ethereum address not already registered | Y(?) | Y |
|--- Not registered under a different Ethereum address  |Y |  |
|--- Expiry Date  | N | Y |
|Wallet| Y | N (to be added in a few months) |

## Integrations


| Integration | PICOPS | uPort |
|---|---|---|
| Hosted Middleware/APIs | Y |  N |
| Contract-level integration | Y |   |
| Managed integration of smart contracts to OnFido | Y |   |
| SDK | N |  Y (JavaScript) |
| API boilerplate | Y (JavaScript) |  N |
| Front-end boilerplate| Y (JavaScript) |  N |

## Readiness/Commercial


| Consideration | PICOPS | uPort |
|---|---|---|
| Release phase | Production | Development |
| User controlled mobile app | N | Y |
| License | MIT | Apache v2 |
| Per user certification request | 0.024ETH | |

## Misc

* Both option seem to have very similar implementation complexity on the token launch team side, but uPort is more feature rich and library/SDK rich
* "Key stakeholders are identified and notified in the case of a grave security issue that has been found 'in the wild'"
    * Not sure if this is regarding users of the system like us or registrants, but should try to get on this list if we plan to use it
* "Any major user of PICOPS, determined as a user that has demonstrably referred more than 1000 certification requests, is entitled to commision, at their own expense, an independent security audit"
    * This is cool!
