# Wrapped WebDollar

Wrapped WebDollar is an ERC20 token on the Ethereum chain (currently on Ethereum Ropsten Test Network) pegged 1:1 to WEBD from WebDollar blockchain.

## Motivation:

  * Use ETH ecosystem to provide the much needed liquidity to WebDollar ecosystem
  * ETH users can easily burn WWEBD and receive that amount to their WEBD address.

## Ecosystem Deployment Requirements:

  * ETH contract for wrapped WEBD that creates and ERC20 token called WWEBD, pegging 1:1 WWEBD to WEBD.
  * WEBD address for the pegged (locked) WEBD
  * Automated system that polls the ETH blockchain for withdraw operations on WWEBD.
    It sends the WEBD amount to the withdraw WEBD address after 6 ETH block confirmations.
  * Web User Interface to ease the withdraw operation using Metamask integration.

## WWEBD Project links:

  * LOCKED WEBD address: TBD.
  * ETH contract address for WWEBD: TBD.
  * User interface (TESTNET): https://wwebd.shop

## How it works (TESTNET):

  * Download and install a compatible browser (desktop app)
    * Firefox, Chrome, Brave (for Desktop) and install Metamask plugin
    * Metamask application (for Android)
  * From Metamask, create a wallet and choose Ropsten Network (Ethereum Test Network)
  * Get some free Ropsten test ETH from: https://faucet.metamask.io/
  * Contact webmaster@lazyprogrammer.io to give you TESTNET WWEBD (Wrapped WebDollar)
  * Go to https://wwebd.shop, connect via Metamask and check your WWEBD balance
  * Go to http://webdollar.io/ and create a WEBD wallet where you can receive real (not testnet) WEBD
  * Withdraw the WWEBD to WEBD (from ETH Ropsten testnet chain to WebDollar chain) providing a WEBD address where you receive the WEBD amount. Two ETH transactions will be required: one to approve the spend and one to withdraw the WWEBD.
  * After 6 confirmation on the ETH Ropsten testnet chain, the WEBD address will be credited with the withdrawn WWEBD amount.
  * Currently, you are required to withdraw all the WWEBD amount in a withdraw transaction. The transaction will fail otherwise.
  * The WEBD transaction fees are supported by the system.

## Bug report

Please open any issues you find on this repo.
The WWEBD ecosystem code will be made public after the testing process is finished.
