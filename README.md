# payture-node
Payture API for NodeJS. To get started with Payture, you will need an account, please contact [Payture](http://payture.com/) directly. Please also note that this module was not developed by Payture.

## Getting Started

### What you need
[X] Payture Host
[X] Merchant Account(s)

### Install
**npm**
```console
npm install -save payture
```

### Initialize
```node
var PaytureAPI  = require('payture')
var api         = new Payture(PAYTURE_HOST)
```

## API Calls

### eWallet
#### Init
```node
api.wallet.init(MERCHANT, data, callback)           // Init
```
#### Pay
```node
api.wallet.pay(MERCHANT, data, callback)            // Pay
```
#### PaySubmit3DS
```node
api.wallet.paySubmit3ds(MERCHANT, data, callback)   // PaySubmit3DS
```
### User Management
```node
api.wallet.users.register(MERCHANT, data, callback) // Register
```
### Card Management
```node
api.wallet.cards.getList(MERCHANT, data, callback)  // GetList
```
