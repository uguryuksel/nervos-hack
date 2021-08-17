# Inspiring Quotes Dapp(by Nervos)

### What is it?

You can add quotes to Nervos chain and get random 3 quotes from smart contract storage. Randomness generated on client side. It picks an id according to quote size on the smart contract. Enjoy it!

### 1- Screenshoots and Video

Go to <a href="https://youtu.be/G2a-xGpjdh8"> YOUTUBE VIDEO </a> to see project explanation(No sound but everything explained clearly)

<img src="https://github.com/uguryuksel/nervos-hack/blob/master/task7-Porting%20Dapp/ss1.png"/>
<hr/>
<img src="https://github.com/uguryuksel/nervos-hack/blob/master/task7-Porting%20Dapp/ss2.png"/>
<hr/>
<img src="https://github.com/uguryuksel/nervos-hack/blob/master/task7-Porting%20Dapp/ss3.png"/>

### 2- Project Github Link

Go to <a href="https://github.com/uguryuksel/task7"> GITHUB REPO </a> to see project source code

### 3- Contract Details

Transaction Hash: ```0xdf493fbf6ea0dce1202f775c113b24c4a69197fe04a4c0d6033c8b5e35cb15a8```

Deployed Quotes Contract Address: ```0xece0BF9447c1467Bc689Fb6eaE4d2495bCB5DdfB```

Contract ABI:

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

