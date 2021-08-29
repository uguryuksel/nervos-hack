## Use A Tron Wallet To Execute A Smart Contract Call


### 1- A screenshot of the accounts you created (account list)

<img src="https://github.com/uguryuksel/nervos-hack/blob/master/task11-Tron/accounts.png" />

### 2- A link to the Layer 1 address you funded on the Testnet Explorer

- <a href="https://explorer.nervos.org/aggron/address/ckt1qyqg2dxcnq6g3kdjy7c5nf84vqq4phvae6jsr8khjy"> Explorer Link </a>

### 3- A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/uguryuksel/nervos-hack/blob/master/task11-Tron/deposit.png" />

### 4- A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/uguryuksel/nervos-hack/blob/master/task11-Tron/contract.png" />

### 5- The transaction hash of the "Contract call" from the console output

```bash
0xaf1f6884c2df6e58fe95e1e2208e911fdf514f1efb0f1d890e9d0d6662608e8c
```

### 6- The contract address that you called

```bash
0xece0BF9447c1467Bc689Fb6eaE4d2495bCB5DdfB
```


### 7- The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "name": "numberOfQuotes",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "quotes",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "quoteId",
          "type": "uint256"
        },
        {
          "internalType": "address",
          "name": "owner",
          "type": "address"
        },
        {
          "internalType": "string",
          "name": "author",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "content",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_author",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "_content",
          "type": "string"
        }
      ],
      "name": "createQuote",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getAllQuotes",
      "outputs": [
        {
          "components": [
            {
              "internalType": "uint256",
              "name": "quoteId",
              "type": "uint256"
            },
            {
              "internalType": "address",
              "name": "owner",
              "type": "address"
            },
            {
              "internalType": "string",
              "name": "author",
              "type": "string"
            },
            {
              "internalType": "string",
              "name": "content",
              "type": "string"
            }
          ],
          "internalType": "struct Quotes.Quote[]",
          "name": "",
          "type": "tuple[]"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```


### 8- Your Tron address

```bash
TERKZsw71tsRRZpZTB5ZSLNNpDp1ZV5wRB
```


