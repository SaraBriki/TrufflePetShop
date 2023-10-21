# Truffle Pet Shop
This introductory mini project was done within our terminal year's Blockchain class by following this guided [tutorial](https://trufflesuite.com/guides/pet-shop/) on the Truffle Suite website.

## 3-min Demo
Sorry for the separate videos, I had a problem with my screen recorder :(



https://github.com/SaraBriki/TrufflePetShop/assets/78980924/b9faee7c-af72-47af-804d-969c69f6abef



https://github.com/SaraBriki/TrufflePetShop/assets/78980924/bc72dfa0-18fa-4da3-b5ce-66f647c7ae53



https://github.com/SaraBriki/TrufflePetShop/assets/78980924/e07fc2b2-183b-42bd-b0a8-7d62b0545447

## Execution
These are the screenshots I took throughout the making of this project.
After installing Truffle using npm and setting up my development environment, I created a new truffle project and unpacked the Truffle Box offered by this tutorial to facilitate the execution of the project and aim our focus at the understanding of Ethereum's decentralized Blockchain and smart contracts while disregarding steps and details outside of this objective.

Here is the structure of the project:
![1-project-folder-content](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/e07d4b0c-58b4-4bda-8004-9972851e4210)

After that, I created my first smart contract and compiled it:
![2-create-contract](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/d0992e23-bb03-4f13-b0b4-3c46a3dae426)

![2-compile-contract](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/e2424dd7-e498-4027-913e-5b16e71165c2)

Then, I migrated the newly created contract to a Blockchain running locally using Ganache:
![3-migrate-contracts](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/9f91ad34-efca-45ba-afbd-97f6a6dc75c1)
![4-migrate-contracts](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/d9b9d3f1-dc31-48c4-aaa1-bc51d04d0126)

Here is the Blockchain's state after performing this migration:
![5-state-after-migration](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/0b122ea9-4d33-404b-bac3-9610281539ea)

And this is the transactions' view:
![6-transactions-view](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/1cfb5d5b-9acb-4a1a-b0fe-2f8b046da3ae)

Right after that, I wrote the following test file to test the smart contract I created previously:
![7-adoption-test-file](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/1158181b-5f13-41bf-ae55-b20235e9ccfa)

And the test results were the following:
![8-test-results](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/c31a2725-89f1-4592-8c39-c97bf9192194)

Then comes the creation of a web interface to interact smoothly with our smart contract. The front-end code was provided by this tutorial. To be able to run the decentralized web app, I instantiated Web3 locally using the following script:
![9-init-web3-script](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/3177edae-992f-4b44-a37c-e7973bd9c92a)

After adding some processing logic pertaining to our Ethereum Blockchain to the *app.js* file...
![9-app-js-code](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/6e7c9d9b-1f6a-4ce7-b176-b87b167c5267)

And before running the app on the browser, I had to add a browser extension called MetaMask to manage my crypto-wallet, and configure it to connect to the Ganache Blockchain running locally by providing MetaMask with a local RPC. Here is my MetaMask wallet:
![10-meta-mask](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/7e795684-274b-420d-9137-b04bdbfde0c6)

Now, I can run my web app and access it via the URL ```https:\\localhost:3000```!
![11-run-web-app](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/4383f3e8-53b9-4120-bf1d-7a719143d2db)
![11-web-app](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/9d260017-2861-4af0-b3b5-546054917e81)

Finally, I performed a transaction by adopting a very cute dog from the web app. I was prompted by MetaMask to confirm this transaction:
![12-meta-mask-confirm-transaction](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/bbd00fd8-51e8-493f-b734-fbccca35cedb)

The web app's UI was, of course, updated after performing the transaction. Under the picture of the dog I have adopted, the "Adopt" button is now disabled, and the text was replaced by "Success":
![13-ui-update-after-adopt](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/ece27c7e-6d1c-42c1-abf4-a13abf5d6fa3)

Here is the transaction now appearing in the MetaMask tab. I clicked on it to show the details:
![14-meta-mask-transaction](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/ca6f89e6-81db-4f71-b0bc-39a275611d18)
![15-transaction-details-meta-mask](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/400659a6-0d0e-4888-975b-817875b67196)

The transaction can also be found in Ganache's UI (you can check the first digits of the highlighted sender/recipient addresses to verify that it's indeed the same transaction):
![16-transaction-details-ganache](https://github.com/SaraBriki/TrufflePetShop/assets/78980924/7bffd49a-1f4e-4aa1-8ba4-f48d8f017b0b)

### That would be all! Thank you for reviewing my work. Until next time 😄!

