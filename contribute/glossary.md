# 📖 Glossary

**BOLT-11**: A standard format for Lightning Network payment requests (invoices). BOLT-11 invoices are the long strings that start with "lnbc" and contain all the information needed to make a Lightning payment.

**Channel**: A payment channel on the Lightning Network. Channels connect two nodes and allow them to transact with each other off-chain.

**Invoice**: A payment request in the Lightning Network, typically in BOLT-11 format. Unlike Bitcoin addresses, invoices are meant for one-time use and can include specific payment amounts.

**Keysend**: A spontaneous payment method that allows sending satoshis to a node without requiring an invoice first. Only requires the destination public key and amount.

**Lightning Address**: A human-readable identifier (similar to an email address, e.g., username@domain.com) that allows receiving Lightning payments without generating invoices each time.

**Lightning Network**: The Lightning Network extends Bitcoin with payment channels to increase transaction speed and lower costs. It is becoming widely adopted and accepted as the preferred way to scale Bitcoin.

**LNURL**: A protocol for advanced Lightning Network interactions. LNURL enables features like withdrawals, channel requests, and authentication through QR codes or links.

**Node**: A computer running Lightning Network software that can send and receive payments, open channels, and route payments for others.

**Payment**: A payment is a transaction that occurs over the Lightning network. Payments are routed through Lightning payment channels and are not recorded in the Bitcoin blockchain.

**Preimage**: A secret value in Lightning payments that proves a payment was completed. The hash of the preimage is included in the invoice, and revealing the preimage claims the payment.

**Satoshi (sats)**: The smallest unit of Bitcoin. One Bitcoin equals 100,000,000 satoshis. Most Lightning payments are denominated in satoshis.

**Transaction**: A transaction is a transfer of value over the Bitcoin network. While transactions can be complicated, one of the simplest forms of a transaction would be sending bitcoin from one address to another. A transaction is not considered final until it has been included in a valid block by a miner.

**Web3.js**: [web3.js](https://www.npmjs.com/package/web3) is a collection of libraries that allow you to interact with a local or remote ethereum node using HTTP, IPC or WebSocket.

**WebLN**: A JavaScript standard and interface that allows web applications to interact with Lightning wallets in the user's browser. WebLN provides a programmable, permissioned way for websites to request payments and other Lightning operations.

**WebLN provider**: Providers are classes or browser extensions that implement the WebLN interface. Examples include Alby, Joule, and other Lightning-enabled browser extensions. See [WebLN Reference](../building-lightning-apps/webln-reference/) for the full specification.&#x20;
