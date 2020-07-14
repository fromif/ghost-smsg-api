
Ghost Node.js Public API's
===============

## Custom API Endpoints for dApps like Marketplace, Chat
`/smsgget` - will get specific smsg using id

`/smsglist` - will list all for specific address

`/smsgsend` - send smsg to ghost blockchain

`/smsgsendanon` - send a anon encrypted smsg to ghost blockchain


Also needs to develop a javascript Lib, like web3.js for storing smsg, getting smsg for a dApp which will allow devs to create marketplace, chat, email like dApps on top of ghost chain


## Public RPC API’s

### Address Actions
`getaddressbalance`

`getaddressdeltas`

`getaddressmempool`

`getaddresstxids`

`getaddressutxos`

### Blockchain Actions
`getbestblockhash`

`getblock`

`getblockcount`

`getblockdeltas`

`getblockhash`

`getblockhashes`

`getblockheader`

`getchaintips`

`getchaintxstats`

`getdifficulty`


### Rawtransactions
`decoderawtransaction`

`decodescript`

`getrawtransaction`

`sendrawtransaction`


### Util
`estimatefee`

`estimatesmartfee`

`validateaddress`

`verifymessage`
