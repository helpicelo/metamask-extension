# Changelog

## Current Develop Branch

## 9.2.1 Thu Mar 25 2021
- [#10692](https://github.com/MetaMask/metamask-extension/pull/10692): Prevent UI crash when a 'wallet_requestPermissions" confirmation is queued behind a "wallet_addEthereumChain" confirmation
- [#10712](https://github.com/MetaMask/metamask-extension/pull/10712): Fix infinite spinner when request for token symbol fails while attempting an approve transaction

## 9.2.0 Tue Mar 09 2021
- [#10546](https://github.com/MetaMask/metamask-extension/pull/10546): Add a warning when sending a token to its own contract address
- [#10563](https://github.com/MetaMask/metamask-extension/pull/10563): Update references to MetaMask support
- [#10126](https://github.com/MetaMask/metamask-extension/pull/10126): Update Italian translation
- [#10591](https://github.com/MetaMask/metamask-extension/pull/10591): Fix mobile sync of ERC20 tokens
- [#10582](https://github.com/MetaMask/metamask-extension/pull/10582): Adding warnings for excessive custom gas input
- [#10601](https://github.com/MetaMask/metamask-extension/pull/10601): Fix activity title text truncation
- [#10598](https://github.com/MetaMask/metamask-extension/pull/10598): Remove 'Ethereum' from custom RPC endpoint warning
- [#10606](https://github.com/MetaMask/metamask-extension/pull/10606): Show loading screen while fetching token data for approve screen
- [#10486](https://github.com/MetaMask/metamask-extension/pull/10486): Add setting to hide zero balance tokens
- [#10505](https://github.com/MetaMask/metamask-extension/pull/10505): Add support for multiple Ledger & Trezor hardware accounts
- [#10587](https://github.com/MetaMask/metamask-extension/pull/10587): Show correct block explorer for custom RPC endpoints for built-in networks

## 9.1.1 Wed Mar 03 2021
- [#10560](https://github.com/MetaMask/metamask-extension/pull/10560): Fix ENS resolution related crashes when switching networks on send screen
- [#10561](https://github.com/MetaMask/metamask-extension/pull/10561): Fix crash when speeding up an attempt to cancel a transaction on custom networks

## 9.1.0 Mon Mar 01 2021
- [#10265](https://github.com/MetaMask/metamask-extension/pull/10265): Update Japanese translations.
- [#9388](https://github.com/MetaMask/metamask-extension/pull/9388): Update Chinese(Simplified) translations.
- [#10270](https://github.com/MetaMask/metamask-extension/pull/10270): Update Vietnamese translations.
- [#10258](https://github.com/MetaMask/metamask-extension/pull/10258): Update Spanish and Spanish(Latin American and Carribean) translations.
- [#10268](https://github.com/MetaMask/metamask-extension/pull/10268): Update Russian translations.
- [#10269](https://github.com/MetaMask/metamask-extension/pull/10269): Update Tagalog localized messages.
- [#10448](https://github.com/MetaMask/metamask-extension/pull/10448): Fix 'imported' translation use case for Dutch.
- [#10391](https://github.com/MetaMask/metamask-extension/pull/10391): Use translated transaction category for confirmations.
- [#10357](https://github.com/MetaMask/metamask-extension/pull/10357): Cancel unapproved confirmations on network change
- [#10413](https://github.com/MetaMask/metamask-extension/pull/10413): Use native currency in asset row.
- [#10421](https://github.com/MetaMask/metamask-extension/pull/10421): Fix color indicator size on connected site indicator.
- [#10423](https://github.com/MetaMask/metamask-extension/pull/10423): Fix multiple notification window prompts.
- [#10424](https://github.com/MetaMask/metamask-extension/pull/10424): Fix icons on token options menu.
- [#10414](https://github.com/MetaMask/metamask-extension/pull/10414): Fix token fiat conversion rates when switching from certain custom networks.
- [#10453](https://github.com/MetaMask/metamask-extension/pull/10453): Disable BUY button from home screen when not on Ethereum Mainnet.
- [#10465](https://github.com/MetaMask/metamask-extension/pull/10465): Fixes gas selection check mark on the notification view.
- [#10467](https://github.com/MetaMask/metamask-extension/pull/10467): Fix confirm page header with from/to addresses in fullscreen for tx confirmations.
- [#10455](https://github.com/MetaMask/metamask-extension/pull/10455): Hide links to etherscan when no block explorer is specified for a custom network for notifications.
- [#10456](https://github.com/MetaMask/metamask-extension/pull/10456): Fix swap insufficient balance error message.
- [#10350](https://github.com/MetaMask/metamask-extension/pull/10350): Fix encypt/decrypt tx queueing.
- [#10473](https://github.com/MetaMask/metamask-extension/pull/10473): Improve autofocus in the add network form.
- [#10444](https://github.com/MetaMask/metamask-extension/pull/10444): Use eth_gasprice for tx gas price estimation on non-Mainnet networks.
- [#10477](https://github.com/MetaMask/metamask-extension/pull/10477): Fix accountsChanged event not triggering when manually connecting.
- [#10471](https://github.com/MetaMask/metamask-extension/pull/10471): Fix navigation from jumping vertically when clicking into token.
- [#9724](https://github.com/MetaMask/metamask-extension/pull/9724): Add custom network RPC method.
- [#10496](https://github.com/MetaMask/metamask-extension/pull/10496): Eliminate artificial delay in swaps loading screen after request loading is complete.
- [#10501](https://github.com/MetaMask/metamask-extension/pull/10501): Ensure that swap approve tx and swap tx always have the same gas price.
- [#10485](https://github.com/MetaMask/metamask-extension/pull/10485): Fixes signTypedData message overflow.
- [#10525](https://github.com/MetaMask/metamask-extension/pull/10525): Update swaps failure message to include a support link.
- [#10521](https://github.com/MetaMask/metamask-extension/pull/10521): Accommodate for 0 sources verifying swap token
- [#10530](https://github.com/MetaMask/metamask-extension/pull/10530): Show warnings on Add Recipient page of Send flow
- [#9187](https://github.com/MetaMask/metamask-extension/pull/9187): Warn users when an ENS name contains 'confusable' characters
- [#10507](https://github.com/MetaMask/metamask-extension/pull/10507): Fixes ENS IPFS resolution on custom networks with the chainID of 1.

## 9.0.5 Mon Feb 08 2021
- [#10278](https://github.com/MetaMask/metamask-extension/pull/10278): Allow editing transaction amount after clicking max
- [#10214](https://github.com/MetaMask/metamask-extension/pull/10214): Standardize size, shape and color of network color indicators
- [#10298](https://github.com/MetaMask/metamask-extension/pull/10298): Use network primary currency instead of always defaulting to ETH in the confirm approve screen
- [#10300](https://github.com/MetaMask/metamask-extension/pull/10300): Add origin to signature request confirmation page
- [#10296](https://github.com/MetaMask/metamask-extension/pull/10296): Add origin to transaction confirmation
- [#10266](https://github.com/MetaMask/metamask-extension/pull/10266): Update `ko` localized messages
- [#10263](https://github.com/MetaMask/metamask-extension/pull/10263): Update `id` localized messages
- [#10347](https://github.com/MetaMask/metamask-extension/pull/10347): Require click of "Continue" button to interact with swap screen if there is a price impact warning for present swap
- [#10373](https://github.com/MetaMask/metamask-extension/pull/10373): Change copy of submit button on swaps screen
- [#10346](https://github.com/MetaMask/metamask-extension/pull/10346): Swaps token sources/verification messaging update
- [#10378](https://github.com/MetaMask/metamask-extension/pull/10378): Stop showing the window.web3 in-app popup if the dapp is just using web3.currentProvider
- [#10326](https://github.com/MetaMask/metamask-extension/pull/10326): Throw error when attempting to get an encryption key via eth_getEncryptionPublicKey when connected to Ledger HW
- [#10386](https://github.com/MetaMask/metamask-extension/pull/10386): Make action buttons on message components in swaps flow accessible

## 9.0.4 Fri Jan 22 2021
- [#10285](https://github.com/MetaMask/metamask-extension/pull/10285): Update @metamask/contract-metadata from v1.21.0 to 1.22.0
- [#10264](https://github.com/MetaMask/metamask-extension/pull/10264): Update `hi` localized messages
- [#10174](https://github.com/MetaMask/metamask-extension/pull/10174): Move fox to bottom of 'About' page
- [#10198](https://github.com/MetaMask/metamask-extension/pull/10198): Fix hardware account selection
- [#10101](https://github.com/MetaMask/metamask-extension/pull/10101): Add a timeout to all network requests
- [#10212](https://github.com/MetaMask/metamask-extension/pull/10212): Fix displayed balance of tokens with 0 decimals in swaps flow
- [#10162](https://github.com/MetaMask/metamask-extension/pull/10162): Prevent accidentally submitting a swap twice
- [#10224](https://github.com/MetaMask/metamask-extension/pull/10224): Improve chain ID validation
- [#10195](https://github.com/MetaMask/metamask-extension/pull/10195): Increase minimum Firefox version to v68
- [#10192](https://github.com/MetaMask/metamask-extension/pull/10192): Update TrezorConnect to v8
- [#10166](https://github.com/MetaMask/metamask-extension/pull/10166): Fix back button on swaps loading page
- [#9947](https://github.com/MetaMask/metamask-extension/pull/9947): Do not publish swaps transaction if the estimateGas call made when adding the transaction fails.

## 9.0.3 Fri Jan 22 2021
- [#10243](https://github.com/MetaMask/metamask-extension/pull/10243): Fix site metadata handling
- [#10252](https://github.com/MetaMask/metamask-extension/pull/10252): Fix decrypt message confirmation UI crash

## 9.0.2 Wed Jan 20 2021

- [#10191](https://github.com/MetaMask/metamask-extension/pull/10191): zh_TW: 乙太 -> 以太 (#10191)
- [#10207](https://github.com/MetaMask/metamask-extension/pull/10207): zh_TW: Translate buy, assets, activity (#10207)
- [#10219](https://github.com/MetaMask/metamask-extension/pull/10219): Restore provider 'data' event (#10219)

## 9.0.1 Wed Jan 13 2021

- [#10169](https://github.com/MetaMask/metamask-extension/pull/10169): Improved detection of contract methods with array parameters
- [#10178](https://github.com/MetaMask/metamask-extension/pull/10178): Only warn of injected web3 usage once per page
- [#10179](https://github.com/MetaMask/metamask-extension/pull/10179): Restore support for @metamask/inpage provider@"< 8.0.0"
- [#10180](https://github.com/MetaMask/metamask-extension/pull/10180): Fix UI crash when domain metadata is missing on public encryption key confirmation page

## 9.0.0 Fri Jan 8 2021

- [#9156](https://github.com/MetaMask/metamask-extension/pull/9156): Remove window.web3 injection
- [#10039](https://github.com/MetaMask/metamask-extension/pull/10039): Add web3 shim usage notification
- [#8640](https://github.com/MetaMask/metamask-extension/pull/8640): Implement breaking window.ethereum API changes
- [#8629](https://github.com/MetaMask/metamask-extension/pull/8629): Fix `eth_chainId` return values for Infura networks
- [#10019](https://github.com/MetaMask/metamask-extension/pull/10019): Increase Chrome minimum version to v63
- [#10135](https://github.com/MetaMask/metamask-extension/pull/10135): Fix error where a swap only completed the token approval transaction
- [#10100](https://github.com/MetaMask/metamask-extension/pull/10100): Remove unnecessary swaps footer space when in dropdown mode
- [#9905](https://github.com/MetaMask/metamask-extension/pull/9905): Redesign view quote screens
- [#9320](https://github.com/MetaMask/metamask-extension/pull/9320): Prevent hidden tokens from reappearing
- [#10000](https://github.com/MetaMask/metamask-extension/pull/10000): Use consistent font size for modal top right Close links
- [#10046](https://github.com/MetaMask/metamask-extension/pull/10046): Improve home screen notification appearance
- [#10093](https://github.com/MetaMask/metamask-extension/pull/10093): Always roll back to the previously selected network when unable to connect to a newly selected network
- [#10117](https://github.com/MetaMask/metamask-extension/pull/10117): Fix network settings Kovan block explorer link
- [#10143](https://github.com/MetaMask/metamask-extension/pull/10143): Prevent malformed next nonce warning
- [#10142](https://github.com/MetaMask/metamask-extension/pull/10142): Update @metamask/contract-metadata from v1.20.0 to 1.21.0
- [#10160](https://github.com/MetaMask/metamask-extension/pull/10160): Fix French "Block Explorer URL" translations
- [#10157](https://github.com/MetaMask/metamask-extension/pull/10157): Automatically detect tokens on custom Mainnet RPC endpoints
- [#9772](https://github.com/MetaMask/metamask-extension/pull/9772): Improve zh_CN translation
- [#10170](https://github.com/MetaMask/metamask-extension/pull/10170): Fix bug where swaps button was disabled on Mainnet if the user hadn't switched networks in a long time

## 8.1.11 Thu Jan 07 2021

- [#10155](https://github.com/MetaMask/metamask-extension/pull/10155): Disable swaps when the current network's chainId does not match the mainnet chain ID, instead of disabling based on network ID

## 8.1.10 Fri Dec 18 2020

- [#10084](https://github.com/MetaMask/metamask-extension/pull/10084): Set last provider when switching to a customRPC
- [#10096](https://github.com/MetaMask/metamask-extension/pull/10096): Update `@metamask/controllers` to v5.1.0
- [#10103](https://github.com/MetaMask/metamask-extension/pull/10103): Prevent stuck loading screen in some situations
- [#10104](https://github.com/MetaMask/metamask-extension/pull/10104): Bump @metamask/contract-metadata from 1.19.0 to 1.20.0
- [#10110](https://github.com/MetaMask/metamask-extension/pull/10110): Fix frozen loading screen on Firefox when strict Enhanced Tracking Protection is enabled

## 8.1.9 Tue Dec 15 2020

- [#10034](https://github.com/MetaMask/metamask-extension/pull/10034): Fix contentscript injection failure on Firefox 56
- [#10045](https://github.com/MetaMask/metamask-extension/pull/10045): Fix token validation in Send flow
- [#10048](https://github.com/MetaMask/metamask-extension/pull/10048): Display boolean values when signing typed data
- [#10070](https://github.com/MetaMask/metamask-extension/pull/10070): Add eth_getProof
- [#10043](https://github.com/MetaMask/metamask-extension/pull/10043): Improve swaps maximum gas estimation
- [#10069](https://github.com/MetaMask/metamask-extension/pull/10069): Fetch swap quote refresh time from API
- [#10040](https://github.com/MetaMask/metamask-extension/pull/10040): Disable console in contentscript to reduce noise

## 8.1.8 Wed Dec 09 2020

- [#9992](https://github.com/MetaMask/metamask-extension/pull/9992): Improve transaction params validation
- [#9991](https://github.com/MetaMask/metamask-extension/pull/9991): Don't allow more than 15% slippage
- [#9994](https://github.com/MetaMask/metamask-extension/pull/9994): Prevent unwanted 'no quotes available' message when going back to build quote screen while having insufficient funds
- [#9999](https://github.com/MetaMask/metamask-extension/pull/9999): Fix missing contacts upon restart

## 8.1.7 Tue Dec 08 2020

- Revert SES lockdown

## 8.1.6 Wed Dec 02 2020

- [#9916](https://github.com/MetaMask/metamask-extension/pull/9916): Fix QR code scans interpretting payment requests as token addresses
- [#9847](https://github.com/MetaMask/metamask-extension/pull/9847): Add alt text for images in list items
- [#9960](https://github.com/MetaMask/metamask-extension/pull/9960): Ensure watchAsset returns errors for invalid token symbols
- [#9968](https://github.com/MetaMask/metamask-extension/pull/9968): Adds tokens from v1.19.0 of metamask/contract-metadata to add token lists
- [#9970](https://github.com/MetaMask/metamask-extension/pull/9970): Etherscan links support Goerli network
- [#9899](https://github.com/MetaMask/metamask-extension/pull/9899): Show price impact warnings on swaps quote screen
- [#9867](https://github.com/MetaMask/metamask-extension/pull/9867): Replace use of ethgasstation
- [#9984](https://github.com/MetaMask/metamask-extension/pull/9984): Show correct gas estimates when users don't have sufficient balance for contract transaction
- [#9993](https://github.com/MetaMask/metamask-extension/pull/9993): Add 48x48 MetaMask icon for use by browsers

## 8.1.5 Wed Nov 18 2020

- [#9871](https://github.com/MetaMask/metamask-extension/pull/9871): Show send text upon hover in main asset list
- [#9855](https://github.com/MetaMask/metamask-extension/pull/9855): Make edit icon and account name in account details modal focusable
- [#9853](https://github.com/MetaMask/metamask-extension/pull/9853): Provide alternative text for images where appropriate
- [#9869](https://github.com/MetaMask/metamask-extension/pull/9869): Remove CoinSwitch from the Deposit modal
- [#9883](https://github.com/MetaMask/metamask-extension/pull/9883): Move add contact button in fullscreen/expanded view of settings lower to expose the close button.
- [#9891](https://github.com/MetaMask/metamask-extension/pull/9891): Add token verification message to swaps build quote screen
- [#9896](https://github.com/MetaMask/metamask-extension/pull/9896): Show failed token balance updates
- [#9909](https://github.com/MetaMask/metamask-extension/pull/9909): Update asset page etherscan link to the address-filtered token page on Etherscan
- [#9910](https://github.com/MetaMask/metamask-extension/pull/9910): Revert "Show a 'send eth' button on home screen in full screen mode"
- [#9907](https://github.com/MetaMask/metamask-extension/pull/9907): Ensure "Known contract address" warning is shown on send screen even when changing asset
- [#9911](https://github.com/MetaMask/metamask-extension/pull/9911): Fix display of Ledger connection error
- [#9918](https://github.com/MetaMask/metamask-extension/pull/9918): Fix missing icon in asset page dropdown and in advanced gas modal button group

## 8.1.4 Tue Nov 10 2020

- [#9687](https://github.com/MetaMask/metamask-extension/pull/9687): Allow speeding up of underpriced transactions
- [#9694](https://github.com/MetaMask/metamask-extension/pull/9694): normalize UI component font styles
- [#9695](https://github.com/MetaMask/metamask-extension/pull/9695): normalize app component font styles
- [#9696](https://github.com/MetaMask/metamask-extension/pull/9696): normalize deprecated itcss font styles
- [#9697](https://github.com/MetaMask/metamask-extension/pull/9697): normalize page font styles
- [#9740](https://github.com/MetaMask/metamask-extension/pull/9740): Standardize network settings page
- [#9750](https://github.com/MetaMask/metamask-extension/pull/9750): Make swap arrows accessible, make swaps advanced options accessible
- [#9766](https://github.com/MetaMask/metamask-extension/pull/9766): Use 1px borders on inputs and buttons
- [#9767](https://github.com/MetaMask/metamask-extension/pull/9767): Remove border radius from transfer button
- [#9764](https://github.com/MetaMask/metamask-extension/pull/9764): Update custom RPC network dropdown icons
- [#9763](https://github.com/MetaMask/metamask-extension/pull/9763): Add confirmation for network dropdown delete action
- [#9583](https://github.com/MetaMask/metamask-extension/pull/9583): Use `chainId` for incoming transactions controller
- [#9748](https://github.com/MetaMask/metamask-extension/pull/9748): Autofocus input, improve accessibility of restore page
- [#9778](https://github.com/MetaMask/metamask-extension/pull/9778): Shorten unit input width and use ellipses for overflow
- [#9746](https://github.com/MetaMask/metamask-extension/pull/9746): Make the login screen's Restore and Import links accessible
- [#9780](https://github.com/MetaMask/metamask-extension/pull/9780): Display decimal chain ID in network form
- [#9599](https://github.com/MetaMask/metamask-extension/pull/9599): Use MetaSwap API for gas price estimation in swaps
- [#9518](https://github.com/MetaMask/metamask-extension/pull/9518): Make all UI tabs accessible via keyboard
- [#9808](https://github.com/MetaMask/metamask-extension/pull/9808): Always allow overwriting invalid custom RPC chain ID
- [#9812](https://github.com/MetaMask/metamask-extension/pull/9812): Fix send header cancel button alignment
- [#9271](https://github.com/MetaMask/metamask-extension/pull/9271): Do not check popupIsOpen on Vivaldi
- [#9306](https://github.com/MetaMask/metamask-extension/pull/9306): Fix UI crash when dapp submits negative gas price
- [#9257](https://github.com/MetaMask/metamask-extension/pull/9257): Add sort and search to AddRecipient accounts list
- [#9824](https://github.com/MetaMask/metamask-extension/pull/9824): Move `externally_connectable` from base to Chrome manifest
- [#9815](https://github.com/MetaMask/metamask-extension/pull/9815): Add support for custom network RPC URL with basic auth
- [#9822](https://github.com/MetaMask/metamask-extension/pull/9822): Make QR code button focusable
- [#9832](https://github.com/MetaMask/metamask-extension/pull/9832): Warn instead of throw on duplicate web3
- [#9838](https://github.com/MetaMask/metamask-extension/pull/9838): @metamask/controllers@4.0.0
- [#9856](https://github.com/MetaMask/metamask-extension/pull/9856): Prevent user from getting stuck on opt in page
- [#9845](https://github.com/MetaMask/metamask-extension/pull/9845): Show a 'send eth' button on home screen in full screen mode
- [#9871](https://github.com/MetaMask/metamask-extension/pull/9871): Show send text upon hover in main asset list
- [#9880](https://github.com/MetaMask/metamask-extension/pull/9880): Properly detect U2F errors in hardware wallet

## 8.1.3 Mon Oct 26 2020

- [#9642](https://github.com/MetaMask/metamask-extension/pull/9642) Prevent excessive overflow from swap dropdowns
- [#9658](https://github.com/MetaMask/metamask-extension/pull/9658): Fix sorting Quote Source column of quote sort list
- [#9667](https://github.com/MetaMask/metamask-extension/pull/9667): Fix adding contact with QR code
- [#9674](https://github.com/MetaMask/metamask-extension/pull/9674): Fix ENS resolution of `.eth` URLs with query strings
- [#9691](https://github.com/MetaMask/metamask-extension/pull/9691): Bump @metamask/inpage-provider from 6.1.0 to 6.3.0
- [#9700](https://github.com/MetaMask/metamask-extension/pull/9700): Provide image sizing so there's no jump when opening the swaps token search
- [#9568](https://github.com/MetaMask/metamask-extension/pull/9568): Add ses lockdown to build system
- [#9705](https://github.com/MetaMask/metamask-extension/pull/9705): Prevent memory leak from selected account copy tooltip
- [#9671](https://github.com/MetaMask/metamask-extension/pull/9671): Prevent old fetches from polluting the swap state
- [#9702](https://github.com/MetaMask/metamask-extension/pull/9702): Keyboard navigation for swaps dropdowns
- [#9646](https://github.com/MetaMask/metamask-extension/pull/9646): Switch from Matomo to Segment
- [#9745](https://github.com/MetaMask/metamask-extension/pull/9745): Fix fetching swaps when initial network not Mainnet
- [#9621](https://github.com/MetaMask/metamask-extension/pull/9621): Include aggregator fee as part of displayed network fees
- [#9736](https://github.com/MetaMask/metamask-extension/pull/9736): Bump eth-contract-metadata from 1.16.0 to 1.17.0
- [#9743](https://github.com/MetaMask/metamask-extension/pull/9743): Fix "+-" prefix on swap token amount
- [#9715](https://github.com/MetaMask/metamask-extension/pull/9715): Focus on wallet address in buy workflow

## 8.1.2 Mon Oct 19 2020

- [#9608](https://github.com/MetaMask/metamask-extension/pull/9608): Ensure QR code scanner works
- [#9624](https://github.com/MetaMask/metamask-extension/pull/9624): Help users avoid insufficient gas prices in swaps
- [#9614](https://github.com/MetaMask/metamask-extension/pull/9614): Update swaps network fee tooltip
- [#9623](https://github.com/MetaMask/metamask-extension/pull/9623): Prevent reducing the gas limit for swaps
- [#9630](https://github.com/MetaMask/metamask-extension/pull/9630): Fix UI crash when trying to render estimated time remaining of non-submitted transaction
- [#9633](https://github.com/MetaMask/metamask-extension/pull/9633): Update View Quote page to better represent the MetaMask fee

## 8.1.1 Tue Oct 13 2020

- [#9586](https://github.com/MetaMask/metamask-extension/pull/9586): Prevent build quote crash when swapping from non-tracked token with balance (#9586)
- [#9592](https://github.com/MetaMask/metamask-extension/pull/9592): Remove commitment to maintain a public metrics dashboard (#9592)
- [#9596](https://github.com/MetaMask/metamask-extension/pull/9596): Fix TypeError when `signTypedData` throws (#9596)
- [#9591](https://github.com/MetaMask/metamask-extension/pull/9591): Fix Firefox overflow on transaction items with long amounts (#9591)
- [#9601](https://github.com/MetaMask/metamask-extension/pull/9601): Update text content of invalid custom network alert (#9601)
- [#9575](https://github.com/MetaMask/metamask-extension/pull/9575): Ensure proper hover display for accounts in main menu (#9575)
- [#9576](https://github.com/MetaMask/metamask-extension/pull/9576): Autofocus the appropriate text fields in the Create/Import/Hardware screen (#9576)
- [#9581](https://github.com/MetaMask/metamask-extension/pull/9581): AutoFocus the from input on swaps screen (#9581)
- [#9602](https://github.com/MetaMask/metamask-extension/pull/9602): Prevent swap button from being focused when disabled (#9602)
- [#9609](https://github.com/MetaMask/metamask-extension/pull/9609): Ensure swaps customize gas modal values are set correctly (#9609)

## 8.1.0 Tue Oct 13 2020

- [#9565](https://github.com/MetaMask/metamask-extension/pull/9565): Ensure address book entries are shared between networks with the same chain ID
- [#9552](https://github.com/MetaMask/metamask-extension/pull/9552): Fix `eth_signTypedData_v4` chain ID validation for non-default networks
- [#9551](https://github.com/MetaMask/metamask-extension/pull/9551): Allow the "Localhost 8545" network to be edited, and require a chain ID to be specified for it
- [#9491](https://github.com/MetaMask/metamask-extension/pull/9491): Validate custom network chain IDs against endpoint `eth_chainId` return values
- [#9487](https://github.com/MetaMask/metamask-extension/pull/9487): Require chain IDs to be specified for custom networks
- [#9482](https://github.com/MetaMask/metamask-extension/pull/9482): Add MetaMask Swaps 🌻
- [#9422](https://github.com/MetaMask/metamask-extension/pull/9422): Fix data backup feature (i.e. syncing with 3box)
- [#9434](https://github.com/MetaMask/metamask-extension/pull/9434): Improve gas input UI by using tooltip instead of a modal to communicate gas data
- [#9433](https://github.com/MetaMask/metamask-extension/pull/9433): Improve visual style and layout of the basic tab of the customize gas modal
- [#9415](https://github.com/MetaMask/metamask-extension/pull/9415): Fix UI bug in token approval confirmation notifications
- [#9414](https://github.com/MetaMask/metamask-extension/pull/9414): Update Wyre purchase URL
- [#9411](https://github.com/MetaMask/metamask-extension/pull/9411): Rename 'Ethereum Main Network' in network selector to 'Etherum Mainnet'
- [#9409](https://github.com/MetaMask/metamask-extension/pull/9409): Fix info tooltip on the alert settings screen when used in firefox
- [#9406](https://github.com/MetaMask/metamask-extension/pull/9406): Fix UI bug in customize gas modal: shwo left border when the first button is selected
- [#9395](https://github.com/MetaMask/metamask-extension/pull/9395): Correctly save new Contact Book addressed after editing them in 'Settings > Contact'
- [#9293](https://github.com/MetaMask/metamask-extension/pull/9293): Improve Italian translations
- [#9295](https://github.com/MetaMask/metamask-extension/pull/9295): Ensure the extension can be unlocked without network/internet access
- [#9344](https://github.com/MetaMask/metamask-extension/pull/9344): Add messages to Ledger connection process
- [#9329](https://github.com/MetaMask/metamask-extension/pull/9329): Hide seedphrase by default when restoring vault, and provide option for it to be shown
- [#9333](https://github.com/MetaMask/metamask-extension/pull/9333): Ensure names of token symbols are shown when token amounts in the token list are long
- [#9321](https://github.com/MetaMask/metamask-extension/pull/9321): Warn users when sending tokens to the token address
- [#9288](https://github.com/MetaMask/metamask-extension/pull/9288): Fix bug that caused the accounts list to be empty after entering an incorrect password when attempting to export private key
- [#9314](https://github.com/MetaMask/metamask-extension/pull/9314): Improve/fix error text for when ENS names are not found, on mainnet
- [#9307](https://github.com/MetaMask/metamask-extension/pull/9307): Improve 'Contact Us' copy in settings
- [#9283](https://github.com/MetaMask/metamask-extension/pull/9283): Fix capitalization of copy on MetaMetrics opt-in page
- [#9269](https://github.com/MetaMask/metamask-extension/pull/9269): Add lock icon to default networks in the Settings network page, to indicate they are not editable
- [#9189](https://github.com/MetaMask/metamask-extension/pull/9189): Hide gas price/speed estimate button, and link to advanced gas modal, in send flow on non-main network
- [#9184](https://github.com/MetaMask/metamask-extension/pull/9184): Improve visual styling of back button in account modal
- [#9152](https://github.com/MetaMask/metamask-extension/pull/9152): Fix vertical align of the network name in network dropdown button
- [#9073](https://github.com/MetaMask/metamask-extension/pull/9073): Use new Euclid font throughout MetaMask

## 8.0.10 Wed Sep 16 2020

- [#9423](https://github.com/MetaMask/metamask-extension/pull/9423): Update default phishing list
- [#9416](https://github.com/MetaMask/metamask-extension/pull/9416): Fix fetching a new phishing list on Firefox

## 8.0.9 Wed Aug 19 2020

- [#9228](https://github.com/MetaMask/metamask-extension/pull/9228): Move transaction confirmation footer buttons to scrollable area
- [#9256](https://github.com/MetaMask/metamask-extension/pull/9256): Handle non-String web3 property access
- [#9266](https://github.com/MetaMask/metamask-extension/pull/9266): Use @metamask/controllers@2.0.5
- [#9189](https://github.com/MetaMask/metamask-extension/pull/9189): Hide ETH Gas Station estimates on non-main network

## 8.0.8 Fri Aug 14 2020

- [#9211](https://github.com/MetaMask/metamask-extension/pull/9211): Fix Etherscan redirect on notification click
- [#9237](https://github.com/MetaMask/metamask-extension/pull/9237): Reduce volume of web3 usage metrics
- [#9227](https://github.com/MetaMask/metamask-extension/pull/9227): Permit all-caps addresses

## 8.0.7 Fri Aug 07 2020

- [#9065](https://github.com/MetaMask/metamask-extension/pull/9065): Change title of "Reveal Seed Words" page to "Reveal Seed Phrase"
- [#8974](https://github.com/MetaMask/metamask-extension/pull/8974): Add tooltip to copy button for contacts and seed phrase
- [#9063](https://github.com/MetaMask/metamask-extension/pull/9063): Fix broken UI upon failed password validation
- [#9075](https://github.com/MetaMask/metamask-extension/pull/9075): Fix shifted popup notification when browser is in fullscreen on macOS
- [#9085](https://github.com/MetaMask/metamask-extension/pull/9085): Support longer text in network dropdown
- [#8873](https://github.com/MetaMask/metamask-extension/pull/8873): Fix onboarding bug where user can be asked to verify seed phrase twice
- [#9104](https://github.com/MetaMask/metamask-extension/pull/9104): Replace "Email us" button with "Contact us" button
- [#9137](https://github.com/MetaMask/metamask-extension/pull/9137): Fix bug where `accountsChanged` events stop after a dapp connection is closed.
- [#9152](https://github.com/MetaMask/metamask-extension/pull/9152): Fix network name alignment
- [#9144](https://github.com/MetaMask/metamask-extension/pull/9144): Add web3 usage metrics and prepare for web3 removal

## 8.0.6 Wed Jul 22 2020

- [#9030](https://github.com/MetaMask/metamask-extension/pull/9030): Hide "delete" button when editing contact of wallet account
- [#9031](https://github.com/MetaMask/metamask-extension/pull/9031): Fix crash upon removing contact
- [#9032](https://github.com/MetaMask/metamask-extension/pull/9032): Do not show spend limit for approvals
- [#9046](https://github.com/MetaMask/metamask-extension/pull/9046): Update @metamask/inpage-provider@6.1.0
- [#9048](https://github.com/MetaMask/metamask-extension/pull/9048): Skip attempts to resolve 0x contract prefix
- [#9051](https://github.com/MetaMask/metamask-extension/pull/9051): Use content-hash@2.5.2
- [#9056](https://github.com/MetaMask/metamask-extension/pull/9056): Display at least one significant digit of small non-zero token balances

## 8.0.5 Thu Jul 16 2020

- [#8942](https://github.com/MetaMask/metamask-extension/pull/8942): Fix display of incoming transactions (#8942)
- [#8998](https://github.com/MetaMask/metamask-extension/pull/8998): Fix `web3_clientVersion` method (#8998)
- [#9003](https://github.com/MetaMask/metamask-extension/pull/9003): @metamask/inpage-provider@6.0.1 (#9003)
- [#9006](https://github.com/MetaMask/metamask-extension/pull/9006): Hide loading indication after `personal_sign` (#9006)
- [#9011](https://github.com/MetaMask/metamask-extension/pull/9011): Display pending notifications after connect flow (#9011)
- [#9012](https://github.com/MetaMask/metamask-extension/pull/9012): Skip render when home page is closing or redirecting (#9012)
- [#9010](https://github.com/MetaMask/metamask-extension/pull/9010): Limit number of transactions passed outside of TransactionController (#9010)
- [#9023](https://github.com/MetaMask/metamask-extension/pull/9023): Clear AccountTracker accounts and CachedBalances on createNewVaultAndRestore (#9023)
- [#9025](https://github.com/MetaMask/metamask-extension/pull/9025): Catch gas estimate errors (#9025)
- [#9026](https://github.com/MetaMask/metamask-extension/pull/9026): Clear transactions on createNewVaultAndRestore (#9026)

## 8.0.4 Tue Jul 07 2020

- [#8934](https://github.com/MetaMask/metamask-extension/pull/8934): Fix transaction activity on custom networks
- [#8936](https://github.com/MetaMask/metamask-extension/pull/8936): Fix account tracker optimization

## 8.0.3 Mon Jul 06 2020

- [#8921](https://github.com/MetaMask/metamask-extension/pull/8921): Restore missing 'data' provider event, and fix 'notification' event
- [#8923](https://github.com/MetaMask/metamask-extension/pull/8923): Normalize the 'from' parameter for `eth_sendTransaction`
- [#8924](https://github.com/MetaMask/metamask-extension/pull/8924): Fix handling of multiple `eth_requestAccount` messages from the same domain
- [#8917](https://github.com/MetaMask/metamask-extension/pull/8917): Update Italian translations

## 8.0.2 Fri Jul 03 2020

- [#8907](https://github.com/MetaMask/metamask-extension/pull/8907): Tolerate missing or falsey substitutions
- [#8908](https://github.com/MetaMask/metamask-extension/pull/8908): Fix activity log inline buttons
- [#8909](https://github.com/MetaMask/metamask-extension/pull/8909): Prevent confirming blank suggested token
- [#8910](https://github.com/MetaMask/metamask-extension/pull/8910): Handle suggested token resolved elsewhere
- [#8913](https://github.com/MetaMask/metamask-extension/pull/8913): Fix Kovan chain ID constant

## 8.0.1 Thu Jul 02 2020

- [#8874](https://github.com/MetaMask/metamask-extension/pull/8874): Fx overflow behaviour of add token list
- [#8885](https://github.com/MetaMask/metamask-extension/pull/8885): Show `origin` in connect flow rather than site name
- [#8883](https://github.com/MetaMask/metamask-extension/pull/8883): Allow setting a custom nonce of zero
- [#8889](https://github.com/MetaMask/metamask-extension/pull/8889): Fix language code format mismatch
- [#8891](https://github.com/MetaMask/metamask-extension/pull/8891): Prevent showing connected accounts without origin
- [#8893](https://github.com/MetaMask/metamask-extension/pull/8893): Prevent manually connecting to extension UI
- [#8895](https://github.com/MetaMask/metamask-extension/pull/8895): Allow localized messages to not use substitutions
- [#8897](https://github.com/MetaMask/metamask-extension/pull/8897): Update eth-keyring-controller to fix erasure of imported/hardware account names
- [#8896](https://github.com/MetaMask/metamask-extension/pull/8896): Include relative time polyfill locale data
- [#8898](https://github.com/MetaMask/metamask-extension/pull/8898): Replace percentage opacity value

## 8.0.0 Mon Jun 23 2020

- [#7004](https://github.com/MetaMask/metamask-extension/pull/7004): Add permission system
- [#7261](https://github.com/MetaMask/metamask-extension/pull/7261): Search accounts by name
- [#7483](https://github.com/MetaMask/metamask-extension/pull/7483): Buffer 3 blocks before dropping a transaction
- [#7620](https://github.com/MetaMask/metamask-extension/pull/7620): Handle one specific permissions request per tab
- [#7686](https://github.com/MetaMask/metamask-extension/pull/7686): Add description to Reset Account in settings
- [#7362](https://github.com/MetaMask/metamask-extension/pull/7362): Allow custom IPFS gateway and use more secure default gateway
- [#7696](https://github.com/MetaMask/metamask-extension/pull/7696): Adjust colour of Reset Account button to reflect danger
- [#7602](https://github.com/MetaMask/metamask-extension/pull/7602): Support new onboarding library
- [#7672](https://github.com/MetaMask/metamask-extension/pull/7672): Update custom token symbol length restriction message
- [#7747](https://github.com/MetaMask/metamask-extension/pull/7747): Handle 'Enter' keypress on restore from seed screen
- [#7810](https://github.com/MetaMask/metamask-extension/pull/7810): Remove padding around advanced gas info icon
- [#7840](https://github.com/MetaMask/metamask-extension/pull/7840): Force background state update after removing an account
- [#7853](https://github.com/MetaMask/metamask-extension/pull/7853): Change "Log In/Out" terminology to "Unlock/Lock"
- [#7863](https://github.com/MetaMask/metamask-extension/pull/7863): Add mechanism to randomize seed phrase filename
- [#7933](https://github.com/MetaMask/metamask-extension/pull/7933): Sort seed phrase confirmation buttons alphabetically
- [#7987](https://github.com/MetaMask/metamask-extension/pull/7987): Add support for 24 word seed phrases
- [#7971](https://github.com/MetaMask/metamask-extension/pull/7971): Use contact name instead of address during send flow
- [#8050](https://github.com/MetaMask/metamask-extension/pull/8050): Add title attribute to transaction title
- [#7831](https://github.com/MetaMask/metamask-extension/pull/7831): Implement encrypt/decrypt feature
- [#8125](https://github.com/MetaMask/metamask-extension/pull/8125): Add setting for disabling Eth Phishing Detection
- [#8148](https://github.com/MetaMask/metamask-extension/pull/8148): Prevent external domains from submitting more than one perm request at a time
- [#8149](https://github.com/MetaMask/metamask-extension/pull/8149): Wait for extension unlock before processing eth_requestAccounts
- [#8201](https://github.com/MetaMask/metamask-extension/pull/8201): Add Idle Timeout for Sync with mobile
- [#8247](https://github.com/MetaMask/metamask-extension/pull/8247): Update Italian translation
- [#8246](https://github.com/MetaMask/metamask-extension/pull/8246): Make seed phrase import case-insensitive
- [#8254](https://github.com/MetaMask/metamask-extension/pull/8254): Convert Connected Sites page to modal
- [#8259](https://github.com/MetaMask/metamask-extension/pull/8259): Update token cell to show inline stale balance warning
- [#8264](https://github.com/MetaMask/metamask-extension/pull/8264): Move asset list to home tab on small screens
- [#8270](https://github.com/MetaMask/metamask-extension/pull/8270): Connected status indicator
- [#8078](https://github.com/MetaMask/metamask-extension/pull/8078): Allow selecting multiple accounts during connect flow
- [#8318](https://github.com/MetaMask/metamask-extension/pull/8318): Focus the notification popup if it's already open
- [#8356](https://github.com/MetaMask/metamask-extension/pull/8356): Position notification relative to last focused window
- [#8358](https://github.com/MetaMask/metamask-extension/pull/8358): Close notification UI if no unapproved confirmations
- [#8293](https://github.com/MetaMask/metamask-extension/pull/8293): Add popup explaining connection indicator to existing users
- [#8435](https://github.com/MetaMask/metamask-extension/pull/8435): Correctly detect changes to background state
- [#7912](https://github.com/MetaMask/metamask-extension/pull/7912): Disable import button for empty string/file
- [#8246](https://github.com/MetaMask/metamask-extension/pull/8246): Make seed phrase import case-insensitive
- [#8312](https://github.com/MetaMask/metamask-extension/pull/8312): Alert user upon switching to unconnected account
- [#8445](https://github.com/MetaMask/metamask-extension/pull/8445): Only updating pending transactions upon block update
- [#8467](https://github.com/MetaMask/metamask-extension/pull/8467): Fix firefox popup location
- [#8486](https://github.com/MetaMask/metamask-extension/pull/8486): Prevent race condition where transaction value set in UI is overwritten
- [#8490](https://github.com/MetaMask/metamask-extension/pull/8490): Fix default gas race condition
- [#8491](https://github.com/MetaMask/metamask-extension/pull/8491): Update tokens after importing account
- [#8496](https://github.com/MetaMask/metamask-extension/pull/8496): Enable disconnecting a single account or all accounts
- [#8502](https://github.com/MetaMask/metamask-extension/pull/8502): Add support for IPFS address resolution
- [#8419](https://github.com/MetaMask/metamask-extension/pull/8419): Add version dimension to metrics event
- [#8508](https://github.com/MetaMask/metamask-extension/pull/8508): Open notification UI when eth_requestAccounts waits for unlock
- [#8533](https://github.com/MetaMask/metamask-extension/pull/8533): Prevent negative values on gas inputs
- [#8550](https://github.com/MetaMask/metamask-extension/pull/8550): Allow disabling alerts
- [#8563](https://github.com/MetaMask/metamask-extension/pull/8563): Synchronously update transaction status
- [#8567](https://github.com/MetaMask/metamask-extension/pull/8567): Improve Spanish localized message
- [#8532](https://github.com/MetaMask/metamask-extension/pull/8532): Add switch to connected account alert
- [#8575](https://github.com/MetaMask/metamask-extension/pull/8575): Stop polling for recent blocks on custom networks when UI is closed
- [#8579](https://github.com/MetaMask/metamask-extension/pull/8579): Fix Matomo dimension IDs
- [#8592](https://github.com/MetaMask/metamask-extension/pull/8592): Handle trailing / in block explorer URLs
- [#8313](https://github.com/MetaMask/metamask-extension/pull/8313): Add Connected Accounts modal
- [#8609](https://github.com/MetaMask/metamask-extension/pull/8609): Sticky position the tabs at the top
- [#8634](https://github.com/MetaMask/metamask-extension/pull/8634): Define global `web3` as non-enumerable
- [#8601](https://github.com/MetaMask/metamask-extension/pull/8601): warn user when sending from different account
- [#8612](https://github.com/MetaMask/metamask-extension/pull/8612): Persist home tab state
- [#8564](https://github.com/MetaMask/metamask-extension/pull/8564): Implement new transaction list design
- [#8596](https://github.com/MetaMask/metamask-extension/pull/8596): Restrict the size of the permissions metadata store
- [#8654](https://github.com/MetaMask/metamask-extension/pull/8654): Update account options menu design
- [#8657](https://github.com/MetaMask/metamask-extension/pull/8657): Implement new fullscreen design
- [#8663](https://github.com/MetaMask/metamask-extension/pull/8663): Show hostname in the disconnect confirmation
- [#8665](https://github.com/MetaMask/metamask-extension/pull/8665): Make address display wider in Account Details
- [#8670](https://github.com/MetaMask/metamask-extension/pull/8670): Fix token `decimal` type
- [#8653](https://github.com/MetaMask/metamask-extension/pull/8653): Limit Dapp permissions to primary account
- [#8666](https://github.com/MetaMask/metamask-extension/pull/8666): Manually connect via the full connect flow
- [#8677](https://github.com/MetaMask/metamask-extension/pull/8677): Add metrics events for Wyre and CoinSwitch
- [#8680](https://github.com/MetaMask/metamask-extension/pull/8680): Fix connect hardware styling
- [#8689](https://github.com/MetaMask/metamask-extension/pull/8689): Fix create account form styling
- [#8702](https://github.com/MetaMask/metamask-extension/pull/8702): Fix tab content disappearing during scrolling on macOS Firefox
- [#8696](https://github.com/MetaMask/metamask-extension/pull/8696): Implement asset page
- [#8716](https://github.com/MetaMask/metamask-extension/pull/8716): Add nonce to transaction details
- [#8717](https://github.com/MetaMask/metamask-extension/pull/8717): Use URL origin instead of hostname for permission domains
- [#8747](https://github.com/MetaMask/metamask-extension/pull/8747): Fix account menu entry for imported accounts
- [#8768](https://github.com/MetaMask/metamask-extension/pull/8768): Permissions: Do not display HTTP/HTTPS URL schemes for unique hosts
- [#8730](https://github.com/MetaMask/metamask-extension/pull/8730): Hide seed phrase during Account Import
- [#8785](https://github.com/MetaMask/metamask-extension/pull/8785): Rename 'History' tab to 'Activity'
- [#8781](https://github.com/MetaMask/metamask-extension/pull/8781): use UI button for add token functionality
- [#8786](https://github.com/MetaMask/metamask-extension/pull/8786): Show fiat amounts inline on token transfers
- [#8789](https://github.com/MetaMask/metamask-extension/pull/8789): Warn users to only add custom networks that they trust
- [#8802](https://github.com/MetaMask/metamask-extension/pull/8802): Consolidate connected account alerts
- [#8810](https://github.com/MetaMask/metamask-extension/pull/8810): Remove all user- and translator-facing instances of 'dapp'
- [#8836](https://github.com/MetaMask/metamask-extension/pull/8836): Update method data when cached method data is empty
- [#8833](https://github.com/MetaMask/metamask-extension/pull/8833): Improve error handling when signature requested without a keyholder address
- [#8850](https://github.com/MetaMask/metamask-extension/pull/8850): Stop upper-casing exported private key
- [#8631](https://github.com/MetaMask/metamask-extension/pull/8631): Include imported accounts in mobile sync

## 7.7.9 Tue Apr 28 2020

- [#8446](https://github.com/MetaMask/metamask-extension/pull/8446): Fix popup not opening
- [#8449](https://github.com/MetaMask/metamask-extension/pull/8449): Skip adding history entry for empty txMeta diffs
- [#8447](https://github.com/MetaMask/metamask-extension/pull/8447): Delete Dai/Sai migration notification
- [#8460](https://github.com/MetaMask/metamask-extension/pull/8460): Update deposit copy for Wyre
- [#8458](https://github.com/MetaMask/metamask-extension/pull/8458): Snapshot txMeta without cloning history
- [#8459](https://github.com/MetaMask/metamask-extension/pull/8459): Fix method registry initialization
- [#8455](https://github.com/MetaMask/metamask-extension/pull/8455): Add Dai/Sai to currency display
- [#8461](https://github.com/MetaMask/metamask-extension/pull/8461): Prevent network switch upon close of network timeout overlay
- [#8457](https://github.com/MetaMask/metamask-extension/pull/8457): Add INR currency option
- [#8462](https://github.com/MetaMask/metamask-extension/pull/8462): Fix display of Kovan and Rinkeby chain IDs
- [#8465](https://github.com/MetaMask/metamask-extension/pull/8465): Use ethereum-ens-network-map for network support
- [#8463](https://github.com/MetaMask/metamask-extension/pull/8463): Update deprecated Etherscam link
- [#8474](https://github.com/MetaMask/metamask-extension/pull/8474): Only update pending transactions upon block update
- [#8476](https://github.com/MetaMask/metamask-extension/pull/8476): Update eth-contract-metadata
- [#8509](https://github.com/MetaMask/metamask-extension/pull/8509): Fix Tohen Typo

## 7.7.8 Wed Mar 11 2020

- [#8176](https://github.com/MetaMask/metamask-extension/pull/8176): Handle and set gas estimation when max mode is clicked
- [#8178](https://github.com/MetaMask/metamask-extension/pull/8178): Use specified gas limit when speeding up a transaction

## 7.7.7 Wed Mar 04 2020

- [#8162](https://github.com/MetaMask/metamask-extension/pull/8162): Remove invalid Ledger accounts
- [#8163](https://github.com/MetaMask/metamask-extension/pull/8163): Fix account index check

## 7.7.6 Mon Mar 02 2020

- [#8154](https://github.com/MetaMask/metamask-extension/pull/8154): Prevent signing from incorrect Ledger account

## 7.7.5 Fri Feb 14 2020

- [#8053](https://github.com/MetaMask/metamask-extension/pull/8053): Inline the source text not the binary encoding for inpage script
- [#8049](https://github.com/MetaMask/metamask-extension/pull/8049): Add warning to watchAsset API when editing a known token
- [#8051](https://github.com/MetaMask/metamask-extension/pull/8051): Update Wyre ETH purchase url
- [#8059](https://github.com/MetaMask/metamask-extension/pull/8059): Attempt ENS resolution on any valid domain name

## 7.7.4 Wed Jan 29 2020

- [#7918](https://github.com/MetaMask/metamask-extension/pull/7918): Update data on Approve screen after updating custom spend limit
- [#7919](https://github.com/MetaMask/metamask-extension/pull/7919): Allow editing max spend limit
- [#7920](https://github.com/MetaMask/metamask-extension/pull/7920): Validate custom spend limit
- [#7944](https://github.com/MetaMask/metamask-extension/pull/7944): Only resolve ENS on mainnet
- [#7954](https://github.com/MetaMask/metamask-extension/pull/7954): Update ENS registry addresses

## 7.7.3 Fri Jan 24 2020

- [#7894](https://github.com/MetaMask/metamask-extension/pull/7894): Update GABA dependency version
- [#7901](https://github.com/MetaMask/metamask-extension/pull/7901): Use eth-contract-metadata@1.12.1
- [#7910](https://github.com/MetaMask/metamask-extension/pull/7910): Fixing broken JSON import help link

## 7.7.2 Fri Jan 10 2020

- [#7753](https://github.com/MetaMask/metamask-extension/pull/7753): Fix gas estimate for tokens
- [#7473](https://github.com/MetaMask/metamask-extension/pull/7473): Fix transaction order on transaction confirmation screen

## 7.7.1 Wed Dec 04 2019

- [#7488](https://github.com/MetaMask/metamask-extension/pull/7488): Fix text overlap when expanding transaction
- [#7491](https://github.com/MetaMask/metamask-extension/pull/7491): Update gas when asset is changed on send screen
- [#7500](https://github.com/MetaMask/metamask-extension/pull/7500): Remove unused onClick prop from Dropdown component
- [#7502](https://github.com/MetaMask/metamask-extension/pull/7502): Fix chainId for non standard networks
- [#7519](https://github.com/MetaMask/metamask-extension/pull/7519): Fixing hardware connect error display
- [#7501](https://github.com/MetaMask/metamask-extension/pull/7501): Fix accessibility of first-time-flow terms checkboxes
- [#7579](https://github.com/MetaMask/metamask-extension/pull/7579): Prevent Maker migration dismissal timeout state from being overwritten
- [#7581](https://github.com/MetaMask/metamask-extension/pull/7581): Persist Maker migration dismissal timeout
- [#7484](https://github.com/MetaMask/metamask-extension/pull/7484): Ensure transactions are shown in the order they are received
- [#7604](https://github.com/MetaMask/metamask-extension/pull/7604): Process URL fragment for ens-ipfs redirects
- [#7628](https://github.com/MetaMask/metamask-extension/pull/7628): Fix typo that resulted in degrated account menu performance
- [#7558](https://github.com/MetaMask/metamask-extension/pull/7558): Use localized messages for NotificationModal buttons

## 7.7.0 Thu Nov 28 2019 [WITHDRAWN]

- [#7004](https://github.com/MetaMask/metamask-extension/pull/7004): Connect distinct accounts per site
- [#7480](https://github.com/MetaMask/metamask-extension/pull/7480): Fixed link on root README.md
- [#7482](https://github.com/MetaMask/metamask-extension/pull/7482): Update Wyre ETH purchase url
- [#7484](https://github.com/MetaMask/metamask-extension/pull/7484): Ensure transactions are shown in the order they are received
- [#7491](https://github.com/MetaMask/metamask-extension/pull/7491): Update gas when token is changed on the send screen
- [#7501](https://github.com/MetaMask/metamask-extension/pull/7501): Fix accessibility of first-time-flow terms checkboxes
- [#7502](https://github.com/MetaMask/metamask-extension/pull/7502): Fix chainId for non standard networks
- [#7579](https://github.com/MetaMask/metamask-extension/pull/7579): Fix timing of DAI migration notifications after dismissal
- [#7519](https://github.com/MetaMask/metamask-extension/pull/7519): Fixing hardware connect error display
- [#7558](https://github.com/MetaMask/metamask-extension/pull/7558): Use localized messages for NotificationModal buttons
- [#7488](https://github.com/MetaMask/metamask-extension/pull/7488): Fix text overlap when expanding transaction

## 7.6.1 Tue Nov 19 2019

- [#7475](https://github.com/MetaMask/metamask-extension/pull/7475): Add 'Remind Me Later' to the Maker notification
- [#7436](https://github.com/MetaMask/metamask-extension/pull/7436): Add additional rpcUrl verification
- [#7468](https://github.com/MetaMask/metamask-extension/pull/7468): Show transaction fee units on approve screen

## 7.6.0 Mon Nov 18 2019

- [#7450](https://github.com/MetaMask/metamask-extension/pull/7450): Add migration notification for users with non-zero Sai
- [#7461](https://github.com/MetaMask/metamask-extension/pull/7461): Import styles for showing multiple notifications
- [#7451](https://github.com/MetaMask/metamask-extension/pull/7451): Add button disabled when password is empty

## 7.5.3 Fri Nov 15 2019

- [#7412](https://github.com/MetaMask/metamask-extension/pull/7412): lock eth-contract-metadata (#7412)
- [#7416](https://github.com/MetaMask/metamask-extension/pull/7416): Add eslint import plugin to help detect unresolved paths
- [#7414](https://github.com/MetaMask/metamask-extension/pull/7414): Ensure SignatureRequestOriginal 'beforeunload' handler is bound (#7414)
- [#7430](https://github.com/MetaMask/metamask-extension/pull/7430): Update badge colour
- [#7408](https://github.com/MetaMask/metamask-extension/pull/7408): Utilize the full size of icon space (#7408)
- [#7431](https://github.com/MetaMask/metamask-extension/pull/7431): Add all icons to manifest (#7431)
- [#7426](https://github.com/MetaMask/metamask-extension/pull/7426): Ensure Etherscan result is valid before reading it (#7426)
- [#7434](https://github.com/MetaMask/metamask-extension/pull/7434): Update 512px icon (#7434)
- [#7410](https://github.com/MetaMask/metamask-extension/pull/7410): Fix sourcemaps for Sentry
- [#7420](https://github.com/MetaMask/metamask-extension/pull/7420): Adds and end to end test for typed signature requests
- [#7439](https://github.com/MetaMask/metamask-extension/pull/7439): Add metricsEvent to contextTypes (#7439)
- [#7419](https://github.com/MetaMask/metamask-extension/pull/7419): Added webRequest.RequestFilter to filter main_frame .eth requests (#7419)

## 7.5.2 Thu Nov 14 2019

- [#7414](https://github.com/MetaMask/metamask-extension/pull/7414): Ensure SignatureRequestOriginal 'beforeunload' handler is bound

## 7.5.1 Tuesday Nov 13 2019

- [#7402](https://github.com/MetaMask/metamask-extension/pull/7402): Fix regression for signed types data screens
- [#7390](https://github.com/MetaMask/metamask-extension/pull/7390): Update json-rpc-engine
- [#7401](https://github.com/MetaMask/metamask-extension/pull/7401): Reject connection request on window close

## 7.5.0 Mon Nov 04 2019

- [#7328](https://github.com/MetaMask/metamask-extension/pull/7328): ignore known transactions on first broadcast and continue with normal flow
- [#7327](https://github.com/MetaMask/metamask-extension/pull/7327): eth_getTransactionByHash will now check metamask's local history for pending transactions
- [#7333](https://github.com/MetaMask/metamask-extension/pull/7333): Cleanup beforeunload handler after transaction is resolved
- [#7038](https://github.com/MetaMask/metamask-extension/pull/7038): Add support for ZeroNet
- [#7334](https://github.com/MetaMask/metamask-extension/pull/7334): Add web3 deprecation warning
- [#6924](https://github.com/MetaMask/metamask-extension/pull/6924): Add Estimated time to pending tx
- [#7177](https://github.com/MetaMask/metamask-extension/pull/7177): ENS Reverse Resolution support
- [#6891](https://github.com/MetaMask/metamask-extension/pull/6891): New signature request v3 UI
- [#7348](https://github.com/MetaMask/metamask-extension/pull/7348): fix width in first time flow button
- [#7271](https://github.com/MetaMask/metamask-extension/pull/7271): Redesign approve screen
- [#7354](https://github.com/MetaMask/metamask-extension/pull/7354): fix account menu width
- [#7379](https://github.com/MetaMask/metamask-extension/pull/7379): Set default advanced tab gas limit
- [#7380](https://github.com/MetaMask/metamask-extension/pull/7380): Fix advanced tab gas chart
- [#7374](https://github.com/MetaMask/metamask-extension/pull/7374): Hide accounts dropdown scrollbars on Firefox
- [#7357](https://github.com/MetaMask/metamask-extension/pull/7357): Update to gaba@1.8.0
- [#7335](https://github.com/MetaMask/metamask-extension/pull/7335): Add onbeforeunload and have it call onCancel

## 7.4.0 Tue Oct 29 2019

- [#7186](https://github.com/MetaMask/metamask-extension/pull/7186): Use `AdvancedGasInputs` in `AdvancedTabContent`
- [#7304](https://github.com/MetaMask/metamask-extension/pull/7304): Move signTypedData signing out to keyrings
- [#7306](https://github.com/MetaMask/metamask-extension/pull/7306): correct the zh-TW translation
- [#7309](https://github.com/MetaMask/metamask-extension/pull/7309): Freeze Promise global on boot
- [#7296](https://github.com/MetaMask/metamask-extension/pull/7296): Add "Retry" option for failed transactions
- [#7319](https://github.com/MetaMask/metamask-extension/pull/7319): Fix transaction list item status spacing issue
- [#7218](https://github.com/MetaMask/metamask-extension/pull/7218): Add hostname and extensionId to site metadata
- [#7324](https://github.com/MetaMask/metamask-extension/pull/7324): Fix contact deletion
- [#7326](https://github.com/MetaMask/metamask-extension/pull/7326): Fix edit contact details
- [#7325](https://github.com/MetaMask/metamask-extension/pull/7325): Update eth-json-rpc-filters to fix memory leak
- [#7334](https://github.com/MetaMask/metamask-extension/pull/7334): Add web3 deprecation warning

## 7.3.1 Mon Oct 21 2019

- [#7298](https://github.com/MetaMask/metamask-extension/pull/7298): Turn off full screen vs popup a/b test

## 7.3.0 Fri Sep 27 2019

- [#6972](https://github.com/MetaMask/metamask-extension/pull/6972): 3box integration
- [#7168](https://github.com/MetaMask/metamask-extension/pull/7168): Add fixes for German translations
- [#7170](https://github.com/MetaMask/metamask-extension/pull/7170): Remove the disk store
- [#7176](https://github.com/MetaMask/metamask-extension/pull/7176): Performance: Delivery optimized images
- [#7189](https://github.com/MetaMask/metamask-extension/pull/7189): add goerli to incoming tx
- [#7190](https://github.com/MetaMask/metamask-extension/pull/7190): Remove unused locale messages
- [#7173](https://github.com/MetaMask/metamask-extension/pull/7173): Fix RPC error messages
- [#7205](https://github.com/MetaMask/metamask-extension/pull/7205): address book entries by chainId
- [#7207](https://github.com/MetaMask/metamask-extension/pull/7207): obs-store/local-store should upgrade webextension error to real error
- [#7162](https://github.com/MetaMask/metamask-extension/pull/7162): Add a/b test for full screen transaction confirmations
- [#7089](https://github.com/MetaMask/metamask-extension/pull/7089): Add advanced setting to enable editing nonce on confirmation screens
- [#7239](https://github.com/MetaMask/metamask-extension/pull/7239): Update ETH logo, update deposit Ether logo height and width
- [#7255](https://github.com/MetaMask/metamask-extension/pull/7255): Use translated string for state log
- [#7266](https://github.com/MetaMask/metamask-extension/pull/7266): fix issue of xyz ens not resolving
- [#7253](https://github.com/MetaMask/metamask-extension/pull/7253): Prevent Logout Timer that's longer than a week.
- [#7285](https://github.com/MetaMask/metamask-extension/pull/7285): Lessen the length of ENS validation to 3
- [#7287](https://github.com/MetaMask/metamask-extension/pull/7287): Fix phishing detect script

## 7.2.3 Fri Oct 04 2019

- [#7252](https://github.com/MetaMask/metamask-extension/pull/7252): Fix gas limit when sending tx without data to a contract
- [#7260](https://github.com/MetaMask/metamask-extension/pull/7260): Do not transate on seed phrases
- [#7252](https://github.com/MetaMask/metamask-extension/pull/7252): Ensure correct tx category when sending to contracts without tx data

## 7.2.2 Tue Sep 24 2019

- [#7213](https://github.com/MetaMask/metamask-extension/pull/7213): Update minimum Firefox verison to 56.0

## 7.2.1 Tue Sep 17 2019

- [#7180](https://github.com/MetaMask/metamask-extension/pull/7180): Add `appName` message to each locale

## 7.2.0 Mon Sep 8, 2019

- [#7099](https://github.com/MetaMask/metamask-extension/pull/7099): Update localization from Transifex Brave
- [#7137](https://github.com/MetaMask/metamask-extension/pull/7137): Fix validation of empty block explorer url's in custom network form
- [#7128](https://github.com/MetaMask/metamask-extension/pull/7128): Support for eth_signTypedData_v4
- [#7110](https://github.com/MetaMask/metamask-extension/pull/7110): Adds `chaindIdChanged` event to the ethereum provider
- [#7091](https://github.com/MetaMask/metamask-extension/pull/7091): Improve browser performance issues caused by missing locale errors
- [#7085](https://github.com/MetaMask/metamask-extension/pull/7085): Prevent ineffectual speed ups of pending transactions that don't have the lowest nonce
- [#7156](https://github.com/MetaMask/metamask-extension/pull/7156): Set minimum Firefox version to v56.2 to support Waterfox
- [#7157](https://github.com/MetaMask/metamask-extension/pull/7157): Add polyfill for AbortController
- [#7161](https://github.com/MetaMask/metamask-extension/pull/7161): Replace `undefined` selectedAddress with `null`
- [#7171](https://github.com/MetaMask/metamask-extension/pull/7171): Fix recipient field of approve screen

## 7.1.1 Tue Aug 27 2019

- [#7059](https://github.com/MetaMask/metamask-extension/pull/7059): Remove blockscale, replace with ethgasstation
- [#7037](https://github.com/MetaMask/metamask-extension/pull/7037): Remove Babel 6 from internal dependencies
- [#7093](https://github.com/MetaMask/metamask-extension/pull/7093): Allow dismissing privacy mode notification from popup
- [#7087](https://github.com/MetaMask/metamask-extension/pull/7087): Add breadcrumb spacing on Contacts page
- [#7081](https://github.com/MetaMask/metamask-extension/pull/7081): Fix confirm token transaction amount display
- [#7088](https://github.com/MetaMask/metamask-extension/pull/7088): Fix BigNumber conversion error
- [#7072](https://github.com/MetaMask/metamask-extension/pull/7072): Right-to-left CSS (using module for conversion)
- [#6878](https://github.com/MetaMask/metamask-extension/pull/6878): Persian translation
- [#7012](https://github.com/MetaMask/metamask-extension/pull/7012): Added missed phrases to RU locale

## 7.1.0 Fri Aug 16 2019

- [#7035](https://github.com/MetaMask/metamask-extension/pull/7035): Filter non-ERC-20 assets during mobile sync (#7035)
- [#7021](https://github.com/MetaMask/metamask-extension/pull/7021): Using translated string for end of flow messaging (#7021)
- [#7018](https://github.com/MetaMask/metamask-extension/pull/7018): Rename Contacts List settings tab to Contacts (#7018)
- [#7013](https://github.com/MetaMask/metamask-extension/pull/7013): Connections settings tab (#7013)
- [#6996](https://github.com/MetaMask/metamask-extension/pull/6996): Fetch & display received transactions (#6996)
- [#6991](https://github.com/MetaMask/metamask-extension/pull/6991): Remove reload from Share Address button (#6991)
- [#6978](https://github.com/MetaMask/metamask-extension/pull/6978): Address book fixes (#6978)
- [#6944](https://github.com/MetaMask/metamask-extension/pull/6944): Show recipient alias in confirm header if exists (#6944)
- [#6930](https://github.com/MetaMask/metamask-extension/pull/6930): Add support for eth_signTypedData_v4 (#6930)
- [#7046](https://github.com/MetaMask/metamask-extension/pull/7046): Update Italian translation (#7046)
- [#7047](https://github.com/MetaMask/metamask-extension/pull/7047): Add warning about reload on network change

## 7.0.1 Thu Aug 08 2019

- [#6975](https://github.com/MetaMask/metamask-extension/pull/6975): Ensure seed phrase backup notification only shows up for new users

## 7.0.0 Fri Aug 02 2019

- [#6828](https://github.com/MetaMask/metamask-extension/pull/6828): Capitalized speed up label to match rest of UI
- [#6874](https://github.com/MetaMask/metamask-extension/pull/6928): Allows skipping of seed phrase challenge during onboarding, and completing it at a later time
- [#6900](https://github.com/MetaMask/metamask-extension/pull/6900): Prevent opening of asset dropdown if no tokens in account
- [#6904](https://github.com/MetaMask/metamask-extension/pull/6904): Set privacy mode as default
- [#6914](https://github.com/MetaMask/metamask-extension/pull/6914): Adds Address Book feature
- [#6928](https://github.com/MetaMask/metamask-extension/pull/6928): Disable Copy Tx ID and block explorer link for transactions without hash
- [#6967](https://github.com/MetaMask/metamask-extension/pull/6967): Fix mobile sync

## 6.7.3 Thu Jul 18 2019

- [#6888](https://github.com/MetaMask/metamask-extension/pull/6888): Fix bug with resubmitting unsigned transactions.

## 6.7.2 Mon Jul 01 2019

- [#6713](https://github.com/MetaMask/metamask-extension/pull/6713): \* Normalize and Validate txParams in TransactionStateManager.addTx too
- [#6759](https://github.com/MetaMask/metamask-extension/pull/6759): Update to Node.js v10
- [#6694](https://github.com/MetaMask/metamask-extension/pull/6694): Fixes #6694
- [#6743](https://github.com/MetaMask/metamask-extension/pull/6743): \* Add tests for ImportWithSeedPhrase#parseSeedPhrase
- [#6740](https://github.com/MetaMask/metamask-extension/pull/6740): Fixes #6740
- [#6741](https://github.com/MetaMask/metamask-extension/pull/6741): Fixes #6741
- [#6761](https://github.com/MetaMask/metamask-extension/pull/6761): Fixes #6760, correct PropTypes for nextRoute
- [#6754](https://github.com/MetaMask/metamask-extension/pull/6754): Use inline source maps in development
- [#6589](https://github.com/MetaMask/metamask-extension/pull/6589): Document hotfix protocol
- [#6738](https://github.com/MetaMask/metamask-extension/pull/6738): Add codeowner for package-lock-old.json package-lock.json package.json packagelock-old.json files
- [#6648](https://github.com/MetaMask/metamask-extension/pull/6648): Add loading view to notification.html
- [#6731](https://github.com/MetaMask/metamask-extension/pull/6731): Add brave as a platform type for MetaMask

## 6.7.1 Fri Jun 28 2019

- [#6764](https://github.com/MetaMask/metamask-extension/pull/6764): Fix display of token amount on confirm transaction screen

## 6.7.0 Tue Jun 18 2019

- [#6623](https://github.com/MetaMask/metamask-extension/pull/6623): Improve contract method data fetching (#6623)
- [#6551](https://github.com/MetaMask/metamask-extension/pull/6551): Adds 4byte registry fallback to getMethodData() (#6435)
- [#6718](https://github.com/MetaMask/metamask-extension/pull/6718): Add delete to custom RPC form
- [#6700](https://github.com/MetaMask/metamask-extension/pull/6700): Fix styles on 'import account' page, update help link
- [#6714](https://github.com/MetaMask/metamask-extension/pull/6714): Wrap smaller custom block explorer url text
- [#6706](https://github.com/MetaMask/metamask-extension/pull/6706): Pin ethereumjs-tx
- [#6700](https://github.com/MetaMask/metamask-extension/pull/6700): Fix styles on 'import account' page, update help link
- [#6775](https://github.com/MetaMask/metamask-extension/pull/6775): Started adding visual documentation of MetaMask plugin components with the account menu component first

## 6.6.2 Fri Jun 07 2019

- [#6690](https://github.com/MetaMask/metamask-extension/pull/6690): Update dependencies, re-enable npm audit CI job
- [#6700](https://github.com/MetaMask/metamask-extension/pull/6700): Fix styles on 'import account' page, update help link

## 6.6.1 Thu Jun 06 2019

- [#6691](https://github.com/MetaMask/metamask-extension/pull/6691): Revert "Improve ENS Address Input" to fix bugs on input field on non-main networks.

## 6.6.0 Mon Jun 03 2019

- [#6659](https://github.com/MetaMask/metamask-extension/pull/6659): Enable Ledger hardware wallet support on Firefox
- [#6671](https://github.com/MetaMask/metamask-extension/pull/6671): bugfix: reject enable promise on user rejection
- [#6625](https://github.com/MetaMask/metamask-extension/pull/6625): Ensures that transactions cannot be confirmed if gas limit is below 21000.
- [#6633](https://github.com/MetaMask/metamask-extension/pull/6633): Fix grammatical error in i18n endOfFlowMessage6

## 6.5.3 Thu May 16 2019

- [#6619](https://github.com/MetaMask/metamask-extension/pull/6619): bugfix: show extension window if locked regardless of approval
- [#6388](https://github.com/MetaMask/metamask-extension/pull/6388): Transactions/pending - check nonce against the network and mark as dropped if not included in a block
- [#6606](https://github.com/MetaMask/metamask-extension/pull/6606): Improve ENS Address Input
- [#6615](https://github.com/MetaMask/metamask-extension/pull/6615): Adds e2e test for removing imported accounts.

## 6.5.2 Wed May 15 2019

- [#6613](https://github.com/MetaMask/metamask-extension/pull/6613): Hardware Wallet Fix

## 6.5.1 Tue May 14 2019

- Fix bug where approve method would show a warning. #6602
- [#6593](https://github.com/MetaMask/metamask-extension/pull/6593): Fix wording of autoLogoutTimeLimitDescription

## 6.5.0 Fri May 10 2019

- [#6568](https://github.com/MetaMask/metamask-extension/pull/6568): feature: integrate gaba/PhishingController
- [#6490](https://github.com/MetaMask/metamask-extension/pull/6490): Redesign custom RPC form
- [#6558](https://github.com/MetaMask/metamask-extension/pull/6558): Adds auto logout with customizable time frame
- [#6578](https://github.com/MetaMask/metamask-extension/pull/6578): Fixes ability to send to token contract addresses
- [#6557](https://github.com/MetaMask/metamask-extension/pull/6557): Adds drag and drop functionality to seed phrase entry.
- [#6526](https://github.com/MetaMask/metamask-extension/pull/6526): Include token checksum address in prices lookup for token rates
- [#6502](https://github.com/MetaMask/metamask-extension/pull/6502): Add subheader to all settings subviews
- [#6501](https://github.com/MetaMask/metamask-extension/pull/6501): Improve confirm screen loading performance by fixing home screen rendering bug

## 6.4.1 Fri Apr 26 2019

- [#6521](https://github.com/MetaMask/metamask-extension/pull/6521): Revert "Adds 4byte registry fallback to getMethodData()" to fix stalling bug.

## 6.4.0 Wed Apr 17 2019

- [#6445](https://github.com/MetaMask/metamask-extension/pull/6445): \* Move send to pages/
- [#6470](https://github.com/MetaMask/metamask-extension/pull/6470): update publishing.md with dev diagram
- [#6403](https://github.com/MetaMask/metamask-extension/pull/6403): Update to eth-method-registry@1.2.0
- [#6468](https://github.com/MetaMask/metamask-extension/pull/6468): Fix switcher height when Custom RPC is selected or loading
- [#6459](https://github.com/MetaMask/metamask-extension/pull/6459): feature: add Goerli support
- [#6444](https://github.com/MetaMask/metamask-extension/pull/6444): Fixes #6321 & #6421 - Add Localhost 8545 for network dropdown names
- [#6454](https://github.com/MetaMask/metamask-extension/pull/6454): Bump eth-contract-metadata
- [#6448](https://github.com/MetaMask/metamask-extension/pull/6448): Remove unneeded array cloning in getSendToAccounts selector
- [#6056](https://github.com/MetaMask/metamask-extension/pull/6056): repeated getSelectedAddress() func send.selectors.js removed
- [#6422](https://github.com/MetaMask/metamask-extension/pull/6422): Added Chrome limited site access solution doc
- [#6424](https://github.com/MetaMask/metamask-extension/pull/6424): feature: switch token pricing to CoinGecko API
- [#6428](https://github.com/MetaMask/metamask-extension/pull/6428): Don't inject web3 on sharefile.com
- [#6417](https://github.com/MetaMask/metamask-extension/pull/6417): Metrics updates
- [#6420](https://github.com/MetaMask/metamask-extension/pull/6420): Fix links to MetamaskInpageProvider in porting_to_new_environment.md
- [#6362](https://github.com/MetaMask/metamask-extension/pull/6362): Remove broken image walkthrough from metamaskbot comment
- [#6401](https://github.com/MetaMask/metamask-extension/pull/6401): metamask-controller - use improved provider-as-middleware utility
- [#6406](https://github.com/MetaMask/metamask-extension/pull/6406): remove user actions controller
- [#6399](https://github.com/MetaMask/metamask-extension/pull/6399): doc - publishing - typo fix
- [#6396](https://github.com/MetaMask/metamask-extension/pull/6396): pin eth-contract-metadata to last commit hash
- [#6397](https://github.com/MetaMask/metamask-extension/pull/6397): Change coinbase to wyre
- [#6395](https://github.com/MetaMask/metamask-extension/pull/6395): bump ledger and trezor keyring
- [#6389](https://github.com/MetaMask/metamask-extension/pull/6389): Fix display of gas chart on Ethereum networks
- [#6382](https://github.com/MetaMask/metamask-extension/pull/6382): Remove NoticeController

## 6.3.2 Mon Apr 8 2019

- [#6389](https://github.com/MetaMask/metamask-extension/pull/6389): Fix display of gas chart on ethereum networks
- [#6395](https://github.com/MetaMask/metamask-extension/pull/6395): Fixes for signing methods for ledger and trezor devices
- [#6397](https://github.com/MetaMask/metamask-extension/pull/6397): Fix Wyre link

## 6.3.1 Fri Mar 26 2019

- [#6353](https://github.com/MetaMask/metamask-extension/pull/6353): Open restore vault in full screen when clicked from popup
- [#6372](https://github.com/MetaMask/metamask-extension/pull/6372): Prevents duplicates of account addresses from showing in send screen "To" dropdown
- [#6374](https://github.com/MetaMask/metamask-extension/pull/6374): Ensures users are placed on correct confirm screens even when registry service fails

## 6.3.0 Mon Mar 25 2019

- [#6300](https://github.com/MetaMask/metamask-extension/pull/6300): Gas chart hidden on custom networks
- [#6301](https://github.com/MetaMask/metamask-extension/pull/6301): Fix gas fee in the submitted step of the transaction details activity log
- [#6302](https://github.com/MetaMask/metamask-extension/pull/6302): Replaces the coinbase link in the deposit modal with one for wyre
- [#6307](https://github.com/MetaMask/metamask-extension/pull/6307): Centre the notification in the current window
- [#6312](https://github.com/MetaMask/metamask-extension/pull/6312): Fixes popups not showing when screen size is odd
- [#6326](https://github.com/MetaMask/metamask-extension/pull/6326): Fix oversized loading overlay on gas customization modal.
- [#6330](https://github.com/MetaMask/metamask-extension/pull/6330): Stop reloading dapps on network change allowing dapps to decide if it should refresh or not
- [#6332](https://github.com/MetaMask/metamask-extension/pull/6332): Enable mobile sync
- [#6333](https://github.com/MetaMask/metamask-extension/pull/6333): Redesign of the settings screen
- [#6340](https://github.com/MetaMask/metamask-extension/pull/6340): Cancel transactions and signature requests on the closing of notification windows
- [#6341](https://github.com/MetaMask/metamask-extension/pull/6341): Disable transaction "Cancel" button when balance is insufficient
- [#6347](https://github.com/MetaMask/metamask-extension/pull/6347): Enable privacy mode by default for first time users

## 6.2.2 Tue Mar 12 2019

- [#6271](https://github.com/MetaMask/metamask-extension/pull/6271): Centre all notification popups
- [#6268](https://github.com/MetaMask/metamask-extension/pull/6268): Improve Korean translations
- [#6279](https://github.com/MetaMask/metamask-extension/pull/6279): Nonmultiple notifications for batch txs
- [#6280](https://github.com/MetaMask/metamask-extension/pull/6280): No longer check network when validating checksum addresses

## 6.2.1 Wed Mar 06 2019

## 6.2.0 Tue Mar 05 2019

- [#6192](https://github.com/MetaMask/metamask-extension/pull/6192): Improves design and UX of onboarding flow
- [#6195](https://github.com/MetaMask/metamask-extension/pull/6195): Fixes gas estimation when sending to contracts
- [#6223](https://github.com/MetaMask/metamask-extension/pull/6223): Fixes display of notification windows when metamask is active in a tab
- [#6171](https://github.com/MetaMask/metamask-extension/pull/6171): Adds MetaMetrics usage analytics system

## 6.1.0 Tue Feb 19 2019

- [#6182](https://github.com/MetaMask/metamask-extension/pull/6182): Change "Token Address" to "Token Contract Address"
- [#6177](https://github.com/MetaMask/metamask-extension/pull/6177): Fixes #6176
- [#6146](https://github.com/MetaMask/metamask-extension/pull/6146): \* Add Copy Tx ID button to transaction-list-item-details
- [#6133](https://github.com/MetaMask/metamask-extension/pull/6133): Checksum address before slicing it for the confirm screen
- [#6147](https://github.com/MetaMask/metamask-extension/pull/6147): Add button to force edit token symbol when adding custom token
- [#6124](https://github.com/MetaMask/metamask-extension/pull/6124): recent-blocks - dont listen for block when on infura providers -[#5973] (https://github.com/MetaMask/metamask-extension/pull/5973): Fix incorrectly showing checksums on non-ETH blockchains (issue 5838)

## 6.0.1 Tue Feb 12 2019

- [#6139](https://github.com/MetaMask/metamask-extension/pull/6139) Fix advanced gas controls on the confirm screen
- [#6134](https://github.com/MetaMask/metamask-extension/pull/6134) Trim whitespace from seed phrase during import
- [#6119](https://github.com/MetaMask/metamask-extension/pull/6119) Update Italian translation
- [#6125](https://github.com/MetaMask/metamask-extension/pull/6125) Improved Traditional Chinese translation

## 6.0.0 Thu Feb 07 2019

- [#6082](https://github.com/MetaMask/metamask-extension/pull/6082): Migrate all users to the new UI
- [#6114](https://github.com/MetaMask/metamask-extension/pull/6114): Add setting for inputting gas price with a text field for advanced users.
- [#6091](https://github.com/MetaMask/metamask-extension/pull/6091): Add Swap feature to CurrencyInput
- [#6090](https://github.com/MetaMask/metamask-extension/pull/6090): Change gas labels to Slow/Average/Fast
- [#6112](https://github.com/MetaMask/metamask-extension/pull/6112): Extract advanced gas input controls to their own component
- [#5929](https://github.com/MetaMask/metamask-extension/pull/5929): Update design of phishing warning screen
- [#6120](https://github.com/MetaMask/metamask-extension/pull/6120): Add class to sign footer button
- [#6116](https://github.com/MetaMask/metamask-extension/pull/6116): Fix locale codes contains underscore never being preferred

## 5.3.5 Mon Feb 4 2019

- [#6084](https://github.com/MetaMask/metamask-extension/pull/6087): Privacy mode fixes

## 5.3.4 Thu Jan 31 2019

- [#6079](https://github.com/MetaMask/metamask-extension/pull/6079): fix - migration 30

## 5.3.3 Wed Jan 30 2019

- [#6006](https://github.com/MetaMask/metamask-extension/pull/6006): Update privacy notice
- [#6072](https://github.com/MetaMask/metamask-extension/pull/6072): Improved Spanish translations
- [#5854](https://github.com/MetaMask/metamask-extension/pull/5854): Add visual indicator when displaying a cached balance.
- [#6044](https://github.com/MetaMask/metamask-extension/pull/6044): Fix bug that interferred with using multiple custom networks.

## 5.3.2 Mon Jan 28 2019

- [#6021](https://github.com/MetaMask/metamask-extension/pull/6021): Order shapeshift transactions by time within the transactions list
- [#6052](https://github.com/MetaMask/metamask-extension/pull/6052): Add and use cached method signatures to reduce provider requests
- [#6048](https://github.com/MetaMask/metamask-extension/pull/6048): Refactor BalanceComponent to jsx
- [#6026](https://github.com/MetaMask/metamask-extension/pull/6026): Prevent invalid chainIds when adding custom rpcs
- [#6029](https://github.com/MetaMask/metamask-extension/pull/6029): Fix grammar error in Current Conversion
- [#6024](https://github.com/MetaMask/metamask-extension/pull/6024): Disable account dropdown on signing screens

## 5.3.1 Wed Jan 16 2019

- [#5966](https://github.com/MetaMask/metamask-extension/pull/5966): Update Slovenian translation
- [#6005](https://github.com/MetaMask/metamask-extension/pull/6005): Set auto conversion off for token/eth conversion
- [#6008](https://github.com/MetaMask/metamask-extension/pull/6008): Fix confirm screen for sending ether tx with hex data
- [#5999](https://github.com/MetaMask/metamask-extension/pull/5999): Refine app description
- [#5997](https://github.com/MetaMask/metamask-extension/pull/5997): Harden Drizzle test runner script
- [#5995](https://github.com/MetaMask/metamask-extension/pull/5995): Fix bug where MetaMask user calls non-standard ERC20 methods such as `mint`, `tokenData` will be `undefined` and an uncaught error will break the UI
- [#5970](https://github.com/MetaMask/metamask-extension/pull/5970): Fixed a word in french translation (several occurrences of connection instead of connexion)
- [#5977](https://github.com/MetaMask/metamask-extension/pull/5977): Fix Component#componentDidUpdate usage
- [#5992](https://github.com/MetaMask/metamask-extension/pull/5992): Add scrolling button to account list
- [#5989](https://github.com/MetaMask/metamask-extension/pull/5989): fix typo in phishing.html title

## 5.3.0 Wed Jan 02 2019

- [#5978](https://github.com/MetaMask/metamask-extension/pull/5978): Fix etherscan links on notifications
- [#5980](https://github.com/MetaMask/metamask-extension/pull/5980): Fix drizzle tests
- [#5922](https://github.com/MetaMask/metamask-extension/pull/5922): Prevent users from changing the From field in the send screen
- [#5932](https://github.com/MetaMask/metamask-extension/pull/5932): Fix displayed time and date in the activity log. Remove vreme library, add luxon library.
- [#5924](https://github.com/MetaMask/metamask-extension/pull/5924): transactions - throw an error if a transaction is generated while the network is loading
- [#5893](https://github.com/MetaMask/metamask-extension/pull/5893): Add loading network screen

## 5.2.2 Wed Dec 12 2018

- [#5925](https://github.com/MetaMask/metamask-extension/pull/5925): Fix speed up button not showing for transactions with the lowest nonce
- [#5923](https://github.com/MetaMask/metamask-extension/pull/5923): Update the Phishing Warning notice text to not use inline URLs
- [#5919](https://github.com/MetaMask/metamask-extension/pull/5919): Fix some styling and translations in the gas customization modal

## 5.2.1 Wed Dec 12 2018

- [#5917] bugfix: Ensures that advanced tab gas limit reflects tx gas limit

## 5.2.0 Mon Dec 11 2018

- [#5704] Implements new gas customization features for sending, confirming and speeding up transactions
- [#5886] Groups transactions - speed up, cancel and original - by nonce in the transaction history list
- [#5892] bugfix: eliminates infinite spinner issues caused by switching quickly from a loading network that ultimately fails to resolve
- [$5902] bugfix: provider crashes caused caching issues in `json-rpc-engine`. Fixed in (https://github.com/MetaMask/json-rpc-engine/commit/6de511afbd03ccef4550ea43ff4010b7d7a84039)

## 5.1.0 Mon Dec 03 2018

- [#5860](https://github.com/MetaMask/metamask-extension/pull/5860): Fixed an infinite spinner bug.
- [#5875](https://github.com/MetaMask/metamask-extension/pull/5875): Update phishing warning copy
- [#5863](https://github.com/MetaMask/metamask-extension/pull/5863): bugfix: normalize contract addresss when fetching exchange rates
- [#5843](https://github.com/MetaMask/metamask-extension/pull/5843): Use selector for state.metamask.accounts in all cases.

## 5.0.4 Thu Nov 29 2018

- [#5878](https://github.com/MetaMask/metamask-extension/pull/5878): Formats 32-length byte strings passed to personal_sign as hex, rather than UTF8.
- [#5840](https://github.com/MetaMask/metamask-extension/pull/5840): transactions/tx-gas-utils - add the acctual response for eth_getCode for NO_CONTRACT_ERROR's && add a debug object to simulationFailed
- [#5848](https://github.com/MetaMask/metamask-extension/pull/5848): Soften accusatory language on phishing warning
- [#5835](https://github.com/MetaMask/metamask-extension/pull/5835): Open full-screen UI on install
- Locked versions for some dependencies to avoid possible issues from event-stream hack.
- [#5831](https://github.com/MetaMask/metamask-extension/pull/5831): Hide app-header when provider request pending
- [#5786](https://github.com/MetaMask/metamask-extension/pull/5786): \* transactions - autofill gasPrice for retry attempts with either the recomened gasprice or a %10 bump
- [#5801](https://github.com/MetaMask/metamask-extension/pull/5801): transactions - ensure err is defined when setting tx failed
- [#5792](https://github.com/MetaMask/metamask-extension/pull/5792): Consider HW Wallets for signTypedMessage
- [#5829](https://github.com/MetaMask/metamask-extension/pull/5829): Show disabled cursor in .network-disabled state
- [#5827](https://github.com/MetaMask/metamask-extension/pull/5827): Trim whitespace from seed phrase during import
- [#5832](https://github.com/MetaMask/metamask-extension/pull/5832): Show Connect Requests count in extension badge
- [#5816](https://github.com/MetaMask/metamask-extension/pull/5816): Increase Token Symbol length to twelve
- [#5819](https://github.com/MetaMask/metamask-extension/pull/5819): With the EIP 1102 updates, MetaMask _does_ now open itself when visiting some websites. Changed the wording here to clarify that MetaMask will not open itself to ask you for your seed phrase.
- [#5810](https://github.com/MetaMask/metamask-extension/pull/5810): Bump Node version to 8.13
- [#5797](https://github.com/MetaMask/metamask-extension/pull/5797): Add Firefox and Brave support for Trezor
- [#5799](https://github.com/MetaMask/metamask-extension/pull/5799): Fix usage of setState in ConfirmTransactionBase#handleSubmit
- [#5798](https://github.com/MetaMask/metamask-extension/pull/5798): Show byte count for hex data on confirm screen
- [#5334](https://github.com/MetaMask/metamask-extension/pull/5334): Default to the new UI for first time users
- [#5791](https://github.com/MetaMask/metamask-extension/pull/5791): Bump eth-ledger-bridge-keyring

## 5.0.3 Mon Nov 19 2018

- [#5547](https://github.com/MetaMask/metamask-extension/pull/5547): Bundle some ui dependencies separately to limit the build size of ui.js
- Resubmit approved transactions on new block, to fix bug where an error can stick transactions in this state.
- Fixed a bug that could cause an error when sending the max number of tokens.

## 5.0.2 Friday November 9 2018

- Fixed bug that caused accounts to update slowly to sites. #5717
- Fixed bug that could lead to some sites crashing. #5709

## 5.0.1 Wednesday November 7 2018

- Fixed bug in privacy mode that made it not work correctly on Firefox.

## 5.0.0 Tuesday November 6 2018

- Implements EIP 1102 as a user-activated "Privacy Mode".

## 4.17.1 Saturday November 3 2018

- Revert chain ID lookup change which introduced a bug which caused problems when connecting to mainnet via Infura's RESTful API.

## 4.17.0 Thursday November 1 2018

- Fix bug where data lookups like balances would get stale data (stopped block-tracker bug)
- Transaction Details now show entry for onchain failure
- [#5559](https://github.com/MetaMask/metamask-extension/pull/5559) Localize language names in translation select list
- [#5283](https://github.com/MetaMask/metamask-extension/pull/5283): Fix bug when eth.getCode() called with no contract
- [#5563](https://github.com/MetaMask/metamask-extension/pull/5563#pullrequestreview-166769174) Feature: improve Hatian Creole translations
- Feature: improve Slovenian translations
- Add support for alternate `wallet_watchAsset` rpc method name
- Attempt chain ID lookup via `eth_chainId` before `net_version`
- Fix account display width for large currency values

## 4.16.0 Wednesday October 17 2018

- Feature: Add toggle for primary currency (eth/fiat)
- Feature: add tooltip for view etherscan tx
- Feature: add Polish translations
- Feature: improve Korean translations
- Feature: improve Italian translations
- Bug Fix: Fix bug with "pending" block reference
- Bug Fix: Force AccountTracker to update balances on network change
- Bug Fix: Fix document extension check when injecting web3
- Bug Fix: Fix some support links

## 4.15.0 Thursday October 11 2018

- A rollback release, equivalent to `v4.11.1` to be deployed in the case that `v4.14.0` is found to have bugs.

## 4.14.0 Thursday October 11 2018

- Update transaction statuses when switching networks.
- [#5470](https://github.com/MetaMask/metamask-extension/pull/5470) 100% coverage in French locale, fixed the procedure to verify proposed locale.
- Added rudimentary support for the subscription API to support web3 1.0 and Truffle's Drizzle.
- [#5502](https://github.com/MetaMask/metamask-extension/pull/5502) Update Italian translation.

## 4.13.0

- A rollback release, equivalent to `v4.11.1` to be deployed in the case that `v4.12.0` is found to have bugs.

## 4.12.0 Thursday September 27 2018

- Reintroduces changes from 4.10.0

## 4.11.1 Tuesday September 25 2018

- Adds Ledger support.

## 4.11.0 Monday September 24 2018

- Identical to 4.9.3. A rollback version to give time to fix bugs in the 4.10.x branch.

## 4.10.0 Mon Sep 17 2018

- [#4803](https://github.com/MetaMask/metamask-extension/pull/4803): Implement EIP-712: Sign typed data, but continue to support v1.
- [#4898](https://github.com/MetaMask/metamask-extension/pull/4898): Restore multiple consecutive accounts with balances.
- [#4279](https://github.com/MetaMask/metamask-extension/pull/4279): New BlockTracker and Json-Rpc-Engine based Provider.
- [#5050](https://github.com/MetaMask/metamask-extension/pull/5050): Add Ledger hardware wallet support.
- [#4919](https://github.com/MetaMask/metamask-extension/pull/4919): Refactor and Redesign Transaction List.
- [#5182](https://github.com/MetaMask/metamask-extension/pull/5182): Add Transaction Details to the Transaction List view.
- [#5229](https://github.com/MetaMask/metamask-extension/pull/5229): Clear old seed words when importing new seed words.
- [#5264](https://github.com/MetaMask/metamask-extension/pull/5264): Improve click area for adjustment arrows buttons.
- [#4606](https://github.com/MetaMask/metamask-extension/pull/4606): Add new metamask_watchAsset method.
- [#5189](https://github.com/MetaMask/metamask-extension/pull/5189): Fix bug where Ropsten loading message is shown when connecting to Kovan.
- [#5256](https://github.com/MetaMask/metamask-extension/pull/5256): Add mock EIP-1102 support

## 4.9.3 Wed Aug 15 2018

- [#4897](https://github.com/MetaMask/metamask-extension/pull/4897): QR code scan for recipient addresses.
- [#4961](https://github.com/MetaMask/metamask-extension/pull/4961): Add a download seed phrase link.
- [#5060](https://github.com/MetaMask/metamask-extension/pull/5060): Fix bug where gas was not updating properly.

## 4.9.2 Mon Aug 09 2018

- [#5020](https://github.com/MetaMask/metamask-extension/pull/5020): Fix bug in migration #28 ( moving tokens to specific accounts )

## 4.9.1 Mon Aug 09 2018

- [#4884](https://github.com/MetaMask/metamask-extension/pull/4884): Allow to have tokens per account and network.
- [#4989](https://github.com/MetaMask/metamask-extension/pull/4989): Continue to use original signedTypedData.
- [#5010](https://github.com/MetaMask/metamask-extension/pull/5010): Fix ENS resolution issues.
- [#5000](https://github.com/MetaMask/metamask-extension/pull/5000): Show error while allowing confirmation of tx where simulation fails.
- [#4995](https://github.com/MetaMask/metamask-extension/pull/4995): Shows retry button on dApp initialized transactions.

## 4.9.0 Mon Aug 07 2018

- [#4926](https://github.com/MetaMask/metamask-extension/pull/4926): Show retry button on the latest tx of the earliest nonce.
- [#4888](https://github.com/MetaMask/metamask-extension/pull/4888): Suggest using the new user interface.
- [#4947](https://github.com/MetaMask/metamask-extension/pull/4947): Prevent sending multiple transasctions on multiple confirm clicks.
- [#4844](https://github.com/MetaMask/metamask-extension/pull/4844): Add new tokens auto detection.
- [#4667](https://github.com/MetaMask/metamask-extension/pull/4667): Remove rejected transactions from transaction history.
- [#4625](https://github.com/MetaMask/metamask-extension/pull/4625): Add Trezor Support.
- [#4625](https://github.com/MetaMask/metamask-extension/pull/4625/commits/523cf9ad33d88719520ae5e7293329d133b64d4d): Allow to remove accounts (Imported and Hardware Wallets)
- [#4814](https://github.com/MetaMask/metamask-extension/pull/4814): Add hex data input to send screen.
- [#4691](https://github.com/MetaMask/metamask-extension/pull/4691): Redesign of the Confirm Transaction Screen.
- [#4840](https://github.com/MetaMask/metamask-extension/pull/4840): Now shows notifications when transactions are completed.
- [#4855](https://github.com/MetaMask/metamask-extension/pull/4855): Allow the use of HTTP prefix for custom rpc urls.
- [#4855](https://github.com/MetaMask/metamask-extension/pull/4855): network.js: convert rpc protocol to lower case.
- [#4898](https://github.com/MetaMask/metamask-extension/pull/4898): Restore multiple consecutive accounts with balances.

## 4.8.0 Thur Jun 14 2018

- [#4513](https://github.com/MetaMask/metamask-extension/pull/4513): Attempting to import an empty private key will now show a clear error.
- [#4570](https://github.com/MetaMask/metamask-extension/pull/4570): Fix bug where metamask data would stop being written to disk after prolonged use.
- [#4523](https://github.com/MetaMask/metamask-extension/pull/4523): Fix bug where account reset did not work with custom RPC providers.
- [#4524](https://github.com/MetaMask/metamask-extension/pull/4524): Fix for Brave i18n getAcceptLanguages.
- [#4557](https://github.com/MetaMask/metamask-extension/pull/4557): Fix bug where nonce mutex was never released.
- [#4566](https://github.com/MetaMask/metamask-extension/pull/4566): Add phishing notice.
- [#4591](https://github.com/MetaMask/metamask-extension/pull/4591): Allow Copying Token Addresses and link to Token on Etherscan.

## 4.7.4 Tue Jun 05 2018

- Add diagnostic reporting for users with multiple HD keyrings
- Throw explicit error when selected account is unset

## 4.7.3 Mon Jun 04 2018

- Hide token now uses new modal
- Indicate the current selected account on the popup account view
- Reduce height of notice container in onboarding
- Fixes issue where old nicknames were kept around causing errors

## 4.7.2 Sun Jun 03 2018

- Fix bug preventing users from logging in. Internally accounts and identities were out of sync.
- Fix support links to point to new support system (Zendesk)
- Fix bug in migration #26 ( moving account nicknames to preferences )
- Clears account nicknames on restore from seedPhrase

## 4.7.1 Fri Jun 01 2018

- Fix bug where errors were not returned to Dapps.

## 4.7.0 Wed May 30 2018

- Fix Brave support
- Adds error messages when passwords don't match in onboarding flow.
- Adds modal notification if a retry in the process of being confirmed is dropped.
- New unlock screen design.
- Design improvements to the add token screen.
- Fix inconsistencies in confirm screen between extension and browser window modes.
- Fix scrolling in deposit ether modal.
- Fix styling of app spinner.
- Font weight changed from 300 to 400.
- New reveal screen design.
- Styling improvements to labels in first time flow and signature request headers.
- Allow other extensions to make access our ethereum provider API ([#3997](https://github.com/MetaMask/metamask-extension/pull/3997))

## 4.6.1 Mon Apr 30 2018

- Fix bug where sending a transaction resulted in an infinite spinner
- Allow transactions with a 0 gwei gas price
- Handle encoding errors in ERC20 symbol + digits
- Fix ShapeShift forms (new + old ui)
- Fix sourcemaps

## 4.6.0 Thu Apr 26 2018

- Correctly format currency conversion for locally selected preferred currency.
- Improved performance of 3D fox logo.
- Fetch token prices based on contract address, not symbol
- Fix bug that prevents setting language locale in settings.
- Show checksum addresses throughout the UI
- Allow transactions with a 0 gwei gas price
- Made provider RPC errors contain useful messages

## 4.5.5 Fri Apr 06 2018

- Graceful handling of unknown keys in txParams
- Fixes buggy handling of historical transactions with unknown keys in txParams
- Fix link for 'Learn More' in the Add Token Screen to open to a new tab.
- Fix Download State Logs button [#3791](https://github.com/MetaMask/metamask-extension/issues/3791)
- Enhanced migration error handling + reporting

## 4.5.4 (aborted) Thu Apr 05 2018

- Graceful handling of unknown keys in txParams
- Fix link for 'Learn More' in the Add Token Screen to open to a new tab.
- Fix Download State Logs button [#3791](https://github.com/MetaMask/metamask-extension/issues/3791)
- Fix migration error reporting

## 4.5.3 Wed Apr 04 2018

- Fix bug where checksum address are messing with balance issue [#3843](https://github.com/MetaMask/metamask-extension/issues/3843)
- new ui: fix the confirm transaction screen

## 4.5.2 Wed Apr 04 2018

- Fix overly strict validation where transactions were rejected with hex encoded "chainId"

## 4.5.1 Tue Apr 03 2018

- Fix default network (should be mainnet not Rinkeby)
- Fix Sentry automated error reporting endpoint

## 4.5.0 Mon Apr 02 2018

- (beta ui) Internationalization: Select your preferred language in the settings screen
- Internationalization: various locale improvements
- Fix bug where the "Reset account" feature would not clear the network cache.
- Increase maximum gas limit, to allow very gas heavy transactions, since block gas limits have been stable.

## 4.4.0 Mon Mar 26 2018

- Internationalization: Taiwanese, Thai, Slovenian
- Fixes bug where MetaMask would not open once its storage grew too large.
- Updates design of new-ui Add Token screen
- New-ui can send to ens addresses
- Update new-ui button styles
- Signed-type-data notification handles long messages
- Popup extension in new-ui uses new on-boarding designs
- Buy ether step of new-ui on-boarding uses new buy ether modal designs

## 4.3.0 Wed Mar 21 2018

- (beta) Add internationalization support! Includes translations for 13 (!!) new languages: French, Spanish, Italian, German, Dutch, Portuguese, Japanese, Korean, Vietnamese, Mandarin, Hindi, Tagalog, and Russian! Select "Try Beta" in the menu to take them for a spin. Read more about the community effort [here](https://medium.com/gitcoin/metamask-internationalizes-via-gitcoin-bf1390c0301c)
- No longer uses nonces specified by the dapp
- Will now throw an error if the `to` field in txParams is not valid.
- Will strip null values from the `to` field.
- (beta) No longer shows token confirmation screen when performing a non-send
- (beta) Fixes bug where tx data was nullified when repricing a tx
- Fix flashing Login screen after logging in or restoring from seed phrase.
- Increase tap areas for menu buttons on mobile
- Change all fonts in new-ui onboarding to Roboto, size 400
- Add a welcome screen to new-ui onboarding flow
- Make new-ui create password screen responsive
- Hide network dropdown before account is initialized
- Fix bug that could prevent MetaMask from saving the latest vault.

## 4.2.0 Tue Mar 06 2018

- Replace "Loose" wording to "Imported".
- Replace "Unlock" wording with "Log In".
- Add Imported Account disclaimer.
- Allow adding custom tokens to classic ui when balance is 0
- Allow editing of symbol and decimal info when adding custom token in new-ui
- NewUI shapeshift form can select all coins (not just BTC)
- Add most of Microsoft Edge support.

## 4.1.3 2018-2-28

- Ensure MetaMask's inpage provider is named MetamaskInpageProvider to keep some sites from breaking.
- Add retry transaction button back into classic ui.
- Add network dropdown styles to support long custom RPC urls

## 4.1.2 2018-2-28

- Actually includes all the fixes mentioned in 4.1.1 (sorry)

## 4.1.1 2018-2-28

- Fix "Add Token" screen referencing missing token logo urls
- Prevent user from switching network during signature request
- Fix misleading language "Contract Published" -> "Contract Deployment"
- Fix cancel button on "Buy Eth" screen
- Improve new-ui onboarding flow style

## 4.1.0 2018-2-27

- Report failed txs to Sentry with more specific message
- Fix internal feature flags being sometimes undefined
- Standardized license to MIT

## 4.0.0 2018-2-22

- Introduce new MetaMask user interface.

## 3.14.2 2018-2-15

- Fix bug where log subscriptions would break when switching network.
- Fix bug where storage values were cached across blocks.
- Add MetaMask light client [testing container](https://github.com/MetaMask/mesh-testing)

## 3.14.1 2018-2-1

- Further fix scrolling for Firefox.

## 3.14.0 2018-2-1

- Removed unneeded data from storage
- Add a "reset account" feature to Settings
- Add warning for importing some kinds of files.
- Scrollable Setting view for Firefox.

## 3.13.8 2018-1-29

- Fix provider for Kovan network.
- Bump limit for EventEmitter listeners before warning.
- Display Error when empty string is entered as a token address.

## 3.13.7 2018-1-22

- Add ability to bypass gas estimation loading indicator.
- Forward failed transactions to Sentry error reporting service
- Re-add changes from 3.13.5

## 3.13.6 2017-1-18

- Roll back changes to 3.13.4 to fix some issues with the new Infura REST provider.

## 3.13.5 2018-1-16

- Estimating gas limit for simple ether sends now faster & cheaper, by avoiding VM usage on recipients with no code.
- Add an extra px to address for Firefox clipping.
- Fix Firefox scrollbar.
- Open metamask popup for transaction confirmation before gas estimation finishes and add a loading screen over transaction confirmation.
- Fix bug that prevented eth_signTypedData from signing bytes.
- Further improve gas price estimation.

## 3.13.4 2018-1-9

- Remove recipient field if application initializes a tx with an empty string, or 0x, and tx data. Throw an error with the same condition, but without tx data.
- Improve gas price suggestion to be closer to the lowest that will be accepted.
- Throw an error if a application tries to submit a tx whose value is a decimal, and inform that it should be in wei.
- Fix bug that prevented updating custom token details.
- No longer mark long-pending transactions as failed, since we now have button to retry with higher gas.
- Fix rounding error when specifying an ether amount that has too much precision.
- Fix bug where incorrectly inputting seed phrase would prevent any future attempts from succeeding.

## 3.13.3 2017-12-14

- Show tokens that are held that have no balance.
- Reduce load on Infura by using a new block polling endpoint.

## 3.13.2 2017-12-9

- Reduce new block polling interval to 8000 ms, to ease server load.

## 3.13.1 2017-12-7

- Allow Dapps to specify a transaction nonce, allowing dapps to propose resubmit and force-cancel transactions.

## 3.13.0 2017-12-7

- Allow resubmitting transactions that are taking long to complete.

## 3.12.1 2017-11-29

- Fix bug where a user could be shown two different seed phrases.
- Detect when multiple web3 extensions are active, and provide useful error.
- Adds notice about seed phrase backup.

## 3.12.0 2017-10-25

- Add support for alternative ENS TLDs (Ethereum Name Service Top-Level Domains).
- Lower minimum gas price to 0.1 GWEI.
- Remove web3 injection message from production (thanks to @ChainsawBaby)
- Add additional debugging info to our state logs, specifically OS version and browser version.

## 3.11.2 2017-10-21

- Fix bug where reject button would sometimes not work.
- Fixed bug where sometimes MetaMask's connection to a page would be unreliable.

## 3.11.1 2017-10-20

- Fix bug where log filters were not populated correctly
- Fix bug where web3 API was sometimes injected after the page loaded.
- Fix bug where first account was sometimes not selected correctly after creating or restoring a vault.
- Fix bug where imported accounts could not use new eth_signTypedData method.

## 3.11.0 2017-10-11

- Add support for new eth_signTypedData method per EIP 712.
- Fix bug where some transactions would be shown as pending forever, even after successfully mined.
- Fix bug where a transaction might be shown as pending forever if another tx with the same nonce was mined.
- Fix link to support article on token addresses.

## 3.10.9 2017-10-5

- Only rebrodcast transactions for a day not a days worth of blocks
- Remove Slack link from info page, since it is a big phishing target.
- Stop computing balance based on pending transactions, to avoid edge case where users are unable to send transactions.

## 3.10.8 2017-9-28

- Fixed usage of new currency fetching API.

## 3.10.7 2017-9-28

- Fixed bug where sometimes the current account was not correctly set and exposed to web apps.
- Added AUD, HKD, SGD, IDR, PHP to currency conversion list

## 3.10.6 2017-9-27

- Fix bug where newly created accounts were not selected.
- Fix bug where selected account was not persisted between lockings.

## 3.10.5 2017-9-27

- Fix block gas limit estimation.

## 3.10.4 2017-9-27

- Fix bug that could mis-render token balances when very small. (Not actually included in 3.9.9)
- Fix memory leak warning.
- Fix bug where new event filters would not include historical events.

## 3.10.3 2017-9-21

- Fix bug where metamask-dapp connections are lost on rpc error
- Fix bug that would sometimes display transactions as failed that could be successfully mined.

## 3.10.2 2017-9-18

rollback to 3.10.0 due to bug

## 3.10.1 2017-9-18

- Add ability to export private keys as a file.
- Add ability to export seed words as a file.
- Changed state logs to a file download than a clipboard copy.
- Add specific error for failed recipient address checksum.
- Fixed a long standing memory leak associated with filters installed by dapps
- Fix link to support center.
- Fixed tooltip icon locations to avoid overflow.
- Warn users when a dapp proposes a high gas limit (90% of blockGasLimit or higher
- Sort currencies by currency name (thanks to strelok1: https://github.com/strelok1).

## 3.10.0 2017-9-11

- Readded loose keyring label back into the account list.
- Remove cryptonator from chrome permissions.
- Add info on token contract addresses.
- Add validation preventing users from inputting their own addresses as token tracking addresses.
- Added button to reject all transactions (thanks to davidp94! https://github.com/davidp94)

## 3.9.13 2017-9-8

- Changed the way we initialize the inpage provider to fix a bug affecting some developers.

## 3.9.12 2017-9-6

- Fix bug that prevented Web3 1.0 compatibility
- Make eth_sign deprecation warning less noisy
- Add useful link to eth_sign deprecation warning.
- Fix bug with network version serialization over synchronous RPC
- Add MetaMask version to state logs.
- Add the total amount of tokens when multiple tokens are added under the token list
- Use HTTPS links for Etherscan.
- Update Support center link to new one with HTTPS.
- Make web3 deprecation notice more useful by linking to a descriptive article.

## 3.9.11 2017-8-24

- Fix nonce calculation bug that would sometimes generate very wrong nonces.
- Give up resubmitting a transaction after 3500 blocks.

## 3.9.10 2017-8-23

- Improve nonce calculation, to prevent bug where people are unable to send transactions reliably.
- Remove link to eth-tx-viz from identicons in tx history.

## 3.9.9 2017-8-18

- Fix bug where some transaction submission errors would show an empty screen.
- Fix bug that could mis-render token balances when very small.
- Fix formatting of eth_sign "Sign Message" view.
- Add deprecation warning to eth_sign "Sign Message" view.

## 3.9.8 2017-8-16

- Reenable token list.
- Remove default tokens.

## 3.9.7 2017-8-15

- hotfix - disable token list
- Added a deprecation warning for web3 https://github.com/ethereum/mist/releases/tag/v0.9.0

## 3.9.6 2017-8-09

- Replace account screen with an account drop-down menu.
- Replace account buttons with a new account-specific drop-down menu.

## 3.9.5 2017-8-04

- Improved phishing detection configuration update rate

## 3.9.4 2017-8-03

- Fixed bug that prevented transactions from being rejected.

## 3.9.3 2017-8-03

- Add support for EGO ujo token
- Continuously update blacklist for known phishing sites in background.
- Automatically detect suspicious URLs too similar to common phishing targets, and blacklist them.

## 3.9.2 2017-7-26

- Fix bugs that could sometimes result in failed transactions after switching networks.
- Include stack traces in txMeta's to better understand the life cycle of transactions
- Enhance blacklister functionality to include levenshtein logic. (credit to @sogoiii and @409H for their help!)

## 3.9.1 2017-7-19

- No longer automatically request 1 ropsten ether for the first account in a new vault.
- Now redirects from known malicious sites faster.
- Added a link to our new support page to the help screen.
- Fixed bug where a new transaction would be shown over the current transaction, creating a possible timing attack against user confirmation.
- Fixed bug in nonce tracker where an incorrect nonce would be calculated.
- Lowered minimum gas price to 1 Gwei.

## 3.9.0 2017-7-12

- Now detects and blocks known phishing sites.

## 3.8.6 2017-7-11

- Make transaction resubmission more resilient.
- No longer validate nonce client-side in retry loop.
- Fix bug where insufficient balance error was sometimes shown on successful transactions.

## 3.8.5 2017-7-7

- Fix transaction resubmit logic to fail slightly less eagerly.

## 3.8.4 2017-7-7

- Improve transaction resubmit logic to fail more eagerly when a user would expect it to.

## 3.8.3 2017-7-6

- Re-enable default token list.
- Add origin header to dapp-bound requests to allow providers to throttle sites.
- Fix bug that could sometimes resubmit a transaction that had been stalled due to low balance after balance was restored.

## 3.8.2 2017-7-3

- No longer show network loading indication on config screen, to allow selecting custom RPCs.
- Visually indicate that network spinner is a menu.
- Indicate what network is being searched for when disconnected.

## 3.8.1 2017-6-30

- Temporarily disabled loading popular tokens by default to improve performance.
- Remove SEND token button until a better token sending form can be built, due to some precision issues.
- Fix precision bug in token balances.
- Cache token symbol and precisions to reduce network load.
- Transpile some newer JavaScript, restores compatibility with some older browsers.

## 3.8.0 2017-6-28

- No longer stop rebroadcasting transactions
- Add list of popular tokens held to the account detail view.
- Add ability to add Tokens to token list.
- Add a warning to JSON file import.
- Add "send" link to token list, which goes to TokenFactory.
- Fix bug where slowly mined txs would sometimes be incorrectly marked as failed.
- Fix bug where badge count did not reflect personal_sign pending messages.
- Seed word confirmation wording is now scarier.
- Fix error for invalid seed words.
- Prevent users from submitting two duplicate transactions by disabling submit.
- Allow Dapps to specify gas price as hex string.
- Add button for copying state logs to clipboard.

## 3.7.8 2017-6-12

- Add an `ethereum:` prefix to the QR code address
- The default network on installation is now MainNet
- Fix currency API URL from cryptonator.
- Update gasLimit params with every new block seen.
- Fix ENS resolver symbol UI.

## 3.7.7 2017-6-8

- Fix bug where metamask would show old data after computer being asleep or disconnected from the internet.

## 3.7.6 2017-6-5

- Fix bug that prevented publishing contracts.

## 3.7.5 2017-6-5

- Prevent users from sending to the `0x0` address.
- Provide useful errors when entering bad characters in ENS name.
- Add ability to copy addresses from transaction confirmation view.

## 3.7.4 2017-6-2

- Fix bug with inflight cache that caused some block lookups to return bad values (affected OasisDex).
- Fixed bug with gas limit calculation that would sometimes create unsubmittable gas limits.

## 3.7.3 2017-6-1

- Rebuilt to fix cache clearing bug.

## 3.7.2 2017-5-31

- Now when switching networks sites that use web3 will reload
- Now when switching networks the extension does not restart
- Cleanup decimal bugs in our gas inputs.
- Fix bug where submit button was enabled for invalid gas inputs.
- Now enforce 95% of block's gasLimit to protect users.
- Removing provider-engine from the inpage provider. This fixes some error handling inconsistencies introduced in 3.7.0.
- Added "inflight cache", which prevents identical requests from clogging up the network, dramatically improving ENS performance.
- Fixed bug where filter subscriptions would sometimes fail to unsubscribe.
- Some contracts will now display logos instead of jazzicons.
- Some contracts will now have names displayed in the confirmation view.

## 3.7.0 2017-5-23

- Add Transaction Number (nonce) to transaction list.
- Label the pending tx icon with a tooltip.
- Fix bug where website filters would pile up and not deallocate when leaving a site.
- Continually resubmit pending txs for a period of time to ensure successful broadcast.
- ENS names will no longer resolve to their owner if no resolver is set. Resolvers must be explicitly set and configured.

## 3.6.5 2017-5-17

- Fix bug where edited gas parameters would not take effect.
- Trim currency list.
- Enable decimals in our gas prices.
- Fix reset button.
- Fix event filter bug introduced by newer versions of Geth.
- Fix bug where decimals in gas inputs could result in strange values.

## 3.6.4 2017-5-8

- Fix main-net ENS resolution.

## 3.6.3 2017-5-8

- Fix bug that could stop newer versions of Geth from working with MetaMask.

## 3.6.2 2017-5-8

- Input gas price in Gwei.
- Enforce Safe Gas Minimum recommended by EthGasStation.
- Fix bug where block-tracker could stop polling for new blocks.
- Reduce UI size by removing internal web3.
- Fix bug where gas parameters would not properly update on adjustment.

## 3.6.1 2017-4-30

- Made fox less nosy.
- Fix bug where error was reported in debugger console when Chrome opened a new window.

## 3.6.0 2017-4-26

- Add Rinkeby Test Network to our network list.

## 3.5.4 2017-4-25

- Fix occasional nonce tracking issue.
- Fix bug where some events would not be emitted by web3.
- Fix bug where an error would be thrown when composing signatures for networks with large ID values.

## 3.5.3 2017-4-24

- Popup new transactions in Firefox.
- Fix transition issue from account detail screen.
- Revise buy screen for more modularity.
- Fixed some other small bugs.

## 3.5.2 2017-3-28

- Fix bug where gas estimate totals were sometimes wrong.
- Add link to Kovan Test Faucet instructions on buy view.
- Inject web3 into loaded iFrames.

## 3.5.1 2017-3-27

- Fix edge case where users were unable to enable the notice button if notices were short enough to not require a scrollbar.

## 3.5.0 2017-3-27

- Add better error messages for when a transaction fails on approval
- Allow sending to ENS names in send form on Ropsten.
- Added an address book functionality that remembers the last 15 unique addresses sent to.
- Can now change network to custom RPC URL from lock screen.
- Removed support for old, lightwallet based vault. Users who have not opened app in over a month will need to recover with their seed phrase. This will allow Firefox support sooner.
- Fixed bug where spinner wouldn't disappear on incorrect password submission on seed word reveal.
- Polish the private key UI.
- Enforce minimum values for gas price and gas limit.
- Fix bug where total gas was sometimes not live-updated.
- Fix bug where editing gas value could have some abrupt behaviors (#1233)
- Add Kovan as an option on our network list.
- Fixed bug where transactions on other networks would disappear when submitting a transaction on another network.

## 3.4.0 2017-3-8

- Add two most recently used custom RPCs to network dropdown menu.
- Add personal_sign method support.
- Add personal_ecRecover method support.
- Add ability to customize gas and gasPrice on the transaction approval screen.
- Increase default gas buffer to 1.5x estimated gas value.

## 3.3.0 2017-2-20

- net_version has been made synchronous.
- Test suite for migrations expanded.
- Network now changeable from lock screen.
- Improve test coverage of eth.sign behavior, including a code example of verifying a signature.

## 3.2.2 2017-2-8

- Revert eth.sign behavior to the previous one with a big warning. We will be gradually implementing the new behavior over the coming time. https://github.com/ethereum/wiki/wiki/JSON-RPC#eth_sign

- Improve test coverage of eth.sign behavior, including a code example of verifying a signature.

## 3.2.2 2017-2-8

- Revert eth.sign behavior to the previous one with a big warning. We will be gradually implementing the new behavior over the coming time. https://github.com/ethereum/wiki/wiki/JSON-RPC#eth_sign

## 3.2.1 2017-2-8

- Revert back to old style message signing.
- Fixed some build errors that were causing a variety of bugs.

## 3.2.0 2017-2-8

- Add ability to import accounts in JSON file format (used by Mist, Geth, MyEtherWallet, and more!)
- Fix unapproved messages not being included in extension badge.
- Fix rendering bug where the Confirm transaction view would let you approve transactions when the account has insufficient balance.

## 3.1.2 2017-1-24

- Fix "New Account" default keychain

## 3.1.1 2017-1-20

- Fix HD wallet seed export

## 3.1.0 2017-1-18

- Add ability to import accounts by private key.
- Fixed bug that returned the wrong transaction hashes on private networks that had not implemented EIP 155 replay protection (like TestRPC).

## 3.0.1 2017-1-17

- Fixed bug that prevented eth.sign from working.
- Fix the displaying of transactions that have been submitted to the network in Transaction History

## 3.0.0 2017-1-16

- Fix seed word account generation (https://medium.com/metamask/metamask-3-migration-guide-914b79533cdd#.t4i1qmmsz).
- Fix Bug where you see an empty transaction flash by on the confirm transaction view.
- Create visible difference in transaction history between an approved but not yet included in a block transaction and a transaction who has been confirmed.
- Fix memory leak in RPC Cache
- Override RPC commands eth_syncing and web3_clientVersion
- Remove certain non-essential permissions from certain builds.
- Add a check for when a tx is included in a block.
- Fix bug where browser-solidity would sometimes warn of a contract creation error when there was none.
- Minor modifications to network display.
- Network now displays properly for pending transactions.
- Implement replay attack protections allowed by EIP 155.
- Fix bug where sometimes loading account data would fail by querying a future block.

## 2.14.1 2016-12-20

- Update Coinbase info. and increase the buy amount to $15
- Fixed ropsten transaction links
- Temporarily disable extension reload detection causing infinite reload bug.
- Implemented basic checking for valid RPC URIs.

## 2.14.0 2016-12-16

- Removed Morden testnet provider from provider menu.
- Add support for notices.
- Fix broken reload detection.
- Fix transaction forever cached-as-pending bug.

## 2.13.11 2016-11-23

- Add support for synchronous RPC method "eth_uninstallFilter".
- Forgotten password prompts now send users directly to seed word restoration.

## 2.13.10 2016-11-22

- Improve gas calculation logic.
- Default to Dapp-specified gas limits for transactions.
- Ropsten networks now properly point to the faucet when attempting to buy ether.
- Ropsten transactions now link to etherscan correctly.

## 2.13.9 2016-11-21

- Add support for the new, default Ropsten Test Network.
- Fix bug that would cause MetaMask to occasionally lose its StreamProvider connection and drop requests.
- Fix bug that would cause the Custom RPC menu item to not appear when Localhost 8545 was selected.
- Point ropsten faucet button to actual faucet.
- Phase out ethereumjs-util from our encryptor module.

## 2.13.8 2016-11-16

- Show a warning when a transaction fails during simulation.
- Fix bug where 20% of gas estimate was not being added properly.
- Render error messages in confirmation screen more gracefully.

## 2.13.7 2016-11-8

- Fix bug where gas estimate would sometimes be very high.
- Increased our gas estimate from 100k gas to 20% of estimate.
- Fix GitHub link on info page to point at current repository.

## 2.13.6 2016-10-26

- Add a check for improper Transaction data.
- Inject up to date version of web3.js
- Now nicknaming new accounts "Account #" instead of "Wallet #" for clarity.
- Fix bug where custom provider selection could show duplicate items.
- Fix bug where connecting to a local morden node would make two providers appear selected.
- Fix bug that was sometimes preventing transactions from being sent.

## 2.13.5 2016-10-18

- Increase default max gas to `100000` over the RPC's `estimateGas` response.
- Fix bug where slow-loading dapps would sometimes trigger infinite reload loops.

## 2.13.4 2016-10-17

- Add custom transaction fee field to send form.
- Fix bug where web3 was being injected into XML files.
- Fix bug where changing network would not reload current Dapps.

## 2.13.3 2016-10-4

- Fix bug where log queries were filtered out.
- Decreased vault confirmation button font size to help some Linux users who could not see it.
- Made popup a little taller because it would sometimes cut off buttons.
- Fix bug where long account lists would get scrunched instead of scrolling.
- Add legal information to relevant pages.
- Rename UI elements to be more consistent with one another.
- Updated Terms of Service and Usage.
- Prompt users to re-agree to the Terms of Service when they are updated.

## 2.13.2 2016-10-4

- Fix bug where chosen FIAT exchange rate does no persist when switching networks
- Fix additional parameters that made MetaMask sometimes receive errors from Parity.
- Fix bug where invalid transactions would still open the MetaMask popup.
- Removed hex prefix from private key export, to increase compatibility with Geth, MyEtherWallet, and Jaxx.

## 2.13.1 2016-09-23

- Fix a bug with estimating gas on Parity
- Show loading indication when selecting ShapeShift as purchasing method.

## 2.13.0 2016-09-18

- Add Parity compatibility, fixing Geth dependency issues.
- Add a link to the transaction in history that goes to https://metamask.github.io/eth-tx-viz
  too help visualize transactions and to where they are going.
- Show "Buy Ether" button and warning on tx confirmation when sender balance is insufficient

## 2.12.1 2016-09-14

- Fixed bug where if you send a transaction from within MetaMask extension the
  popup notification opens up.
- Fixed bug where some tx errors would block subsequent txs until the plugin was refreshed.

## 2.12.0 2016-09-14

- Add a QR button to the Account detail screen
- Fixed bug where opening MetaMask could close a non-metamask popup.
- Fixed memory leak that caused occasional crashes.

## 2.11.1 2016-09-12

- Fix bug that prevented caches from being cleared in Opera.

## 2.11.0 2016-09-12

- Fix bug where pending transactions from Test net (or other networks) show up In Main net.
- Add fiat conversion values to more views.
- On fresh install, open a new tab with the MetaMask Introduction video. Does not open on update.
- Block negative values from transactions.
- Fixed a memory leak.
- MetaMask logo now renders as super lightweight SVG, improving compatibility and performance.
- Now showing loading indication during vault unlocking, to clarify behavior for users who are experiencing slow unlocks.
- Now only initially creates one wallet when restoring a vault, to reduce some users' confusion.

## 2.10.2 2016-09-02

- Fix bug where notification popup would not display.

## 2.10.1 2016-09-02

- Fix bug where provider menu did not allow switching to custom network from a custom network.
- Sending a transaction from within MetaMask no longer triggers a popup.
- The ability to build without livereload features (such as for production) can be enabled with the gulp --disableLiveReload flag.
- Fix Ethereum JSON RPC Filters bug.

## 2.10.0 2016-08-29

- Changed transaction approval from notifications system to popup system.
- Add a back button to locked screen to allow restoring vault from seed words when password is forgotten.
- Forms now retain their values even when closing the popup and reopening it.
- Fixed a spelling error in provider menu.

## 2.9.2 2016-08-24

- Fixed shortcut bug from preventing installation.

## 2.9.1 2016-08-24

- Added static image as fallback for when WebGL isn't supported.
- Transaction history now has a hard limit.
- Added info link on account screen that visits Etherscan.
- Fixed bug where a message signing request would be lost if the vault was locked.
- Added shortcut to open MetaMask (Ctrl+Alt+M or Cmd+Opt/Alt+M)
- Prevent API calls in tests.
- Fixed bug where sign message confirmation would sometimes render blank.

## 2.9.0 2016-08-22

- Added ShapeShift to the transaction history
- Added affiliate key to Shapeshift requests
- Added feature to reflect current conversion rates of current vault balance.
- Modify balance display logic.

## 2.8.0 2016-08-15

- Integrate ShapeShift
- Add a form for Coinbase to specify amount to buy
- Fix various typos.
- Make dapp-metamask connection more reliable
- Remove Ethereum Classic from provider menu.

## 2.7.3 2016-07-29

- Fix bug where changing an account would not update in a live Dapp.

## 2.7.2 2016-07-29

- Add Ethereum Classic to provider menu
- Fix bug where host store would fail to receive updates.

## 2.7.1 2016-07-27

- Fix bug where web3 would sometimes not be injected in time for the application.
- Fixed bug where sometimes when opening the plugin, it would not fully open until closing and re-opening.
- Got most functionality working within Firefox (still working on review process before it can be available).
- Fixed menu dropdown bug introduced in Chrome 52.

## 2.7.0 2016-07-21

- Added a Warning screen about storing ETH
- Add buy Button!
- MetaMask now throws descriptive errors when apps try to use synchronous web3 methods.
- Removed firefox-specific line in manifest.

## 2.6.2 2016-07-20

- Fixed bug that would prevent the plugin from reopening on the first try after receiving a new transaction while locked.
- Fixed bug that would render 0 ETH as a non-exact amount.

## 2.6.1 2016-07-13

- Fix tool tips on Eth balance to show the 6 decimals
- Fix rendering of recipient SVG in tx approval notification.
- New vaults now generate only one wallet instead of three.
- Bumped version of web3 provider engine.
- Fixed bug where some lowercase or uppercase addresses were not being recognized as valid.
- Fixed bug where gas cost was misestimated on the tx confirmation view.

## 2.6.0 2016-07-11

- Fix formatting of ETH balance
- Fix formatting of account details.
- Use web3 minified dist for faster inject times
- Fix issue where dropdowns were not in front of icons.
- Update transaction approval styles.
- Align failed and successful transaction history text.
- Fix issue where large domain names and large transaction values would misalign the transaction history.
- Abbreviate ether balances on transaction details to maintain formatting.
- General code cleanup.

## 2.5.0 2016-06-29

- Implement new account design.
- Added a network indicator mark in dropdown menu
- Added network name next to network indicator
- Add copy transaction hash button to completed transaction list items.
- Unify wording for transaction approve/reject options on notifications and the extension.
- Fix bug where confirmation view would be shown twice.

## 2.4.5 2016-06-29

- Fixed bug where MetaMask interfered with PDF loading.
- Moved switch account icon into menu bar.
- Changed status shapes to be a yellow warning sign for failure and ellipsis for pending transactions.
- Now enforce 20 character limit on wallet names.
- Wallet titles are now properly truncated in transaction confirmation.
- Fix formatting on terms & conditions page.
- Now enforce 30 character limit on wallet names.
- Fix out-of-place positioning of pending transaction badges on wallet list.
- Change network status icons to reflect current design.

## 2.4.4 2016-06-23

- Update web3-stream-provider for batch payload bug fix

## 2.4.3 2016-06-23

- Remove redundant network option buttons from settings page
- Switch out font family Transat for Montserrat

## 2.4.2 2016-06-22

- Change out export icon for key.
- Unify copy to clipboard icon
- Fixed eth.sign behavior.
- Fix behavior of batched outbound transactions.

## 2.4.0 2016-06-20

- Clean up UI.
- Remove nonfunctional QR code button.
- Make network loading indicator clickable to select accessible network.
- Show more characters of addresses when space permits.
- Fixed bug when signing messages under 64 hex characters long.
- Add disclaimer view with placeholder text for first time users.

## 2.3.1 2016-06-09

- Style up the info page
- Cache identicon images to optimize for long lists of transactions.
- Fix out of gas errors

## 2.3.0 2016-06-06

- Show network status in title bar
- Added seed word recovery to config screen.
- Clicking network status indicator now reveals a provider menu.

## 2.2.0 2016-06-02

- Redesigned init, vault create, vault restore and seed confirmation screens.
- Added pending transactions to transaction list on account screen.
- Clicking a pending transaction takes you back to the transaction approval screen.
- Update provider-engine to fix intermittent out of gas errors.

## 2.1.0 2016-05-26

- Added copy address button to account list.
- Fixed back button on confirm transaction screen.
- Add indication of pending transactions to account list screen.
- Fixed bug where error warning was sometimes not cleared on view transition.
- Updated eth-lightwallet to fix a critical security issue.

## 2.0.0 2016-05-23

- UI Overhaul per Vlad Todirut's designs.
- Replaced identicons with jazzicons.
- Fixed glitchy transitions.
- Added support for capitalization-based address checksums.
- Send value is no longer limited by javascript number precision, and is always in ETH.
- Added ability to generate new accounts.
- Added ability to locally nickname accounts.

## 1.8.4 2016-05-13

- Point rpc servers to https endpoints.

## 1.8.3 2016-05-12

- Bumped web3 to 0.6.0
- Really fixed `eth_syncing` method response.

## 1.8.2 2016-05-11

- Fixed bug where send view would not load correctly the first time it was visited per account.
- Migrated all users to new scalable backend.
- Fixed `eth_syncing` method response.

## 1.8.1 2016-05-10

- Initial usage of scalable blockchain backend.
- Made official providers more easily configurable for us internally.

## 1.8.0 2016-05-10

- Add support for calls to `eth.sign`.
- Moved account exporting within subview of the account detail view.
- Added buttons to the account export process.
- Improved visual appearance of account detail transition where button heights would change.
- Restored back button to account detail view.
- Show transaction list always, never collapsed.
- Changing provider now reloads current Dapps
- Improved appearance of transaction list in account detail view.

## 1.7.0 2016-04-29

- Account detail view is now the primary view.
- The account detail view now has a "Change acct" button which shows the account list.
- Clicking accounts in the account list now both selects that account and displays that account's detail view.
- Selected account is now persisted between sessions, so the current account stays selected.
- Account icons are now "identicons" (deterministically generated from the address).
- Fixed link to Slack channel.
- Added a context guard for "define" to avoid UMD's exporting themselves to the wrong module system, fixing interference with some websites.
- Transaction list now only shows transactions for the current account.
- Transaction list now only shows transactions for the current network (mainnet, testnet, testrpc).
- Fixed transaction links to etherscan blockchain explorer.
- Fixed some UI transitions that had weird behavior.

## 1.6.0 2016-04-22

- Pending transactions are now persisted to localStorage and resume even after browser is closed.
- Completed transactions are now persisted and can be displayed via UI.
- Added transaction list to account detail view.
- Fix bug on config screen where current RPC address was always displayed wrong.
- Fixed bug where entering a decimal value when sending a transaction would result in sending the wrong amount.
- Add save button to custom RPC input field.
- Add quick-select button for RPC on `localhost:8545`.
- Improve config view styling.
- Users have been migrated from old test-net RPC to a newer test-net RPC.

## 1.5.1 2016-04-15

- Corrected text above account list. Selected account is visible to all sites, not just the current domain.
- Merged the UI codebase into the main plugin codebase for simpler maintenance.
- Fix Ether display rounding error. Now rendering to four decimal points.
- Fix some inpage synchronous methods
- Change account rendering to show four decimals and a leading zero.

## 1.5.0 2016-04-13

- Added ability to send ether.
- Fixed bugs related to using Javascript numbers, which lacked appropriate precision.
- Replaced Etherscan main-net provider with our own production RPC.

## 1.4.0 2016-04-08

- Removed extra entropy text field for simplified vault creation.
- Now supports exporting an account's private key.
- Unified button and input styles across the app.
- Removed some non-working placeholder UI until it works.
- Fix popup's web3 stream provider
- Temporarily deactivated fauceting indication because it would activate when restoring an empty account.

## 1.3.2 2016-04-04

- When unlocking, first account is auto-selected.
- When creating a first vault on the test-net, the first account is auto-funded.
- Fixed some styling issues.

## 1.0.1-1.3.1

Many changes not logged. Hopefully beginning to log consistently now!

## 1.0.0

Made seed word restoring BIP44 compatible.

## 0.14.0

Added the ability to restore accounts from seed words.
