## Extension
This rule aims to implement a way to add additional "features" to messages sent of ICDEP without interfering with the original message.

1. As stated in the anti-duplication rule, we encode the placement of each index card in the total message at the top left corner of each card represented as a fraction out of the total number of cards in the message (x/n) starting at one (1). We will place a card at index zero (0/n) that will not be read as part of the message but will instead contain "header" information for the total transmission.
2. Information contained in this header card will include information such as addresses of recipients, the format of the message to determine how it should be read by the sender, and a list of the address of each node the card passed through on the network. 
3. The additional card allows for future mechanisms to be retrofitted to the ICDEP protocol, as we can write more mechanisms on the card.
