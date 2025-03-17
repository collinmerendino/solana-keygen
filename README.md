# Solana-Keygen CLI
A CLI tool to generate Solana keypairs (public and private keys) and save them to a JSON file.

Useful to create multiple wallets for trading bots or for mass wallet creation.

---

## Features
- Generate multiple Solana keypairs in one go.
- Save keypairs to a JSON file in a specified directory.
- Simple and intuitive command-line interface.


Requirements:
- Go 1.24.0 or higher.

---

## Usage
```
go run solana-keygen.go (number of keys)
```

Example:
```
go run solana-keygen.go 100 /home/directory/output
```

2. Example JSON file output
```
[
  {
    "public_key": "FWgRp9ksDwz2rfxmzV5oDTcss32vigGo2JKKazHRLgT",
    "private_key": "5BeQgPxdTE2gCENRX1tt6BqS44fpj3cApARqU1sNFLo4JJK2hBarYtSWLLLNdft7tX8v9rypyTQ7o6d87WTVM14o"
  },
  {
    "public_key": "GLnGE51L8RYDvkCWtJCoXVJH8AiBrpDqh6oAx4QaUSJ7",
    "private_key": "2Gqc5VQGWmHiGPHfHvMXsuTyBFtYxiG5mgWx9dfdZqocXz35fWm8gLmoVSiKr743dicntacLBgjEbtZY3JhwSKQ7"
  },
  {
    "public_key": "7wXVtGCjZ3cJaAAG8Th9w2gxhK18FqkBabriTNPMYDJm",
    "private_key": "58am3iGTQ3nG7UxPWnzw4a8oibZEwK9WuVH1Cn4oS8MknCYGVjEBKoMp7p3T6CVezE6ptkMa3F8VdhwM5LkUezy3"
  },
  {
    "public_key": "DRRsff6jaW9jgrzrb3TsoiHJv5JEo4dyspDhH2p2hbHH",
    "private_key": "5SHtNtGQYZnKEV3neLLyAAfr8RbG8ScdvsQKfanqWZM5M4JWTVVYbKghY3ceFMfmriJQx5Ni1frtkyQePqNHSNib"
  },
  {
    "public_key": "C2Z21tEM2sbWaunMo8kkpRZBWmk29G1o2D6AQHvXSESJ",
    "private_key": "4nfJNtz9hibJdhjKYdtoeexmTwUYqqE9BxjyLgtn8DfWDmPKUZUNKXLs9fU3wd5mM8x99CGuqbrwgiaJtdUEPPYz"
  }
]
```

---

## Contributing
Contributions are welcome! If you have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. 
