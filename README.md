Attached Evidence for create crypto with Solana CLI & Create Crypto with JS

#For Create Crypto with JS
Attached Screenshot for token transaction in public folder

#For Create Crypto with Solana CLI (Terminal Dump)

$ spl-token create-token --url https://api.devnet.solana.com
Creating token 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a

Signature: 2g8Utt9Jp3p4461QP87ux3Q7Cx6UNjrnqt1rJBT5ymjNJ9Yeha9hDQi8WusYXmAnrWameS3cBc3jw6xzsetFH3FL

$ spl-token create-account 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a --url https://api.devnet.solana.com
Creating account 6BCG1GMAUpdKSDtH6mKqv2z5syxwkuRrDV4ABo4CHC3A

Signature: 2ZiH5VyP6fYsYXiVJ6nYKpcYPSRYoc5WCDfoB5e8kCEj2u8aKmBNm2Ttk66Hpw5LeFjsfJEcvJ6yNQMWDpNUm36k

$ spl-token balance 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a
0

$ spl-token mint 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a 1000 --url https://api.devnet.solana.com
Minting 1000 tokens
  Token: 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a
  Recipient: 6BCG1GMAUpdKSDtH6mKqv2z5syxwkuRrDV4ABo4CHC3A

Signature: QtYQa1AeEfQPgMGqMNM1AaqYwAWJugBQhLWNDkNnTjt5d4u7XLSrLpfNDniD9g1Xff3DVAYVK6qHrTDCzE3iZEi

$ spl-token supply 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a
1000

$ spl-token authorize 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a mint --disable
Updating 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a
  Current mint authority: 4Nakc7ghNbXAgLEK3tx85pKo9ypUCBGNnWFWwR1eLQRF
  New mint authority: disabled

Signature: qhuUsEsYyga8E481WVTyNyxxjiK9x2koearGpEwCSGBBaSNRvJpECRoL5dHi9mu2ZrpNxeMbtrsgESp1WmC259D

$ spl-token burn 6BCG1GMAUpdKSDtH6mKqv2z5syxwkuRrDV4ABo4CHC3A 900
Burn 900 tokens
  Source: 6BCG1GMAUpdKSDtH6mKqv2z5syxwkuRrDV4ABo4CHC3A

Signature: 4r1eQ6irusa6mhnS84wpdvdTaBhJTtJa3fLLkw4AxBrEzZoM2LJAHgqfCkG2WKLfmPmdJQBf3DNMkzt3jurwRe1D

$ spl-token supply 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a
100

$ spl-token transfer 83WHSH9AX4UGp1hUQqbUuGB4qJcbbCvdKPcuqMK9fb8a 69 GHWpV7hG9Y8iYSroNZTUZTazv8EGHwc8gZk2ogT6DGdt
Transfer 69 tokens
  Sender: 6BCG1GMAUpdKSDtH6mKqv2z5syxwkuRrDV4ABo4CHC3A
  Recipient: GHWpV7hG9Y8iYSroNZTUZTazv8EGHwc8gZk2ogT6DGdt
  Recipient associated token account: GWavpBfSTP653SgaLkcsRvSac77dCMh3tujFvWnRGjix

Signature: 5QQ7KPzsScSL3yDPm1EkBkG83krrpSUzFsqTiwCbigauAiFbUunjgFHphicLkfwS7wAB7kUhAFev9CpFWcB4woVU
