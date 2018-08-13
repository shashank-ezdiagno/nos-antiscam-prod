This is the testnet build for the antiscam [dapp](https://github.com/nos-antiscam/client/)

**NOS link** - _nos://antiscam.neo_

## Getting started
### Access TestNet Build(No smart contract deployment needed)
* Run nos-client(login with your wallet address)
* In NOS Client _settings_, change the **Selected Network** to **nOSNet**
* Navigate to _nos://antiscam.neo_

## Dapp-UI Description
There is a form to start with - input address(or select from dropdown of favorites) to send asset(asset can be selected from dropdown)
Once the address is input and the focus is moved out of the address box,
following data is displayed related to the address:

* Whether the address is favorited by you(the owner address)
* Whether the address is flagged by you(the owner address)
* Number of times the address is flagged(overall)
* Comments added by anyone

There are a set of buttons to perform certain action on the address as well:

* Flag/unflag/Check Flag address
* Favorite/unfavorite/Check Favorite address
* Add comments

After every invoke action, there is a delay to confirm the block. So, wait for another
block to check whether your action has been performed.
For example - if you flag an address, wait for another block to check if the address
has been flagged.

Check whether the address has been flagged and decide whether you want to send the
asset to it or not. "Address is secure" text is an assurance that no one has flagged that address
and it is secure to send asset to that address.

Once you decide to send asset(selected from dropdown), input the amount and press the submit button.
You will get an alert with confirmation

Feedbacks are welcome.

<strong>This project is licensed under the terms of the MIT license.</strong>

