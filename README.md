# Anonymous-auction-portal
An anonymous auction portal on ethereum blockchain

Consider the problem of Chinese auction or penny social. We will refer to it as simple “Auction". The organizers collect items to be auctioned off for raising funds. Before the auction, the items for auctions are received and arranged each with a bowl
to place the bid. A chairperson is a special person among the organizers. He/she heads the effort and is
the only person who can determine the winner by random drawing at the end of the auction. A set of
bidders buy sheets of tickets with their money. The bidder’s sheet has a stub that identifies the bidder’s
number, and tokens bought.
The bidders examine the items to bid, place the one or more tickets in the bowl in front of the items they
desire to bid for until all the tickets are used. After the auction period ends the chairperson, collects the
bowls, randomly selects a ticket from each item’s bowl to determine the winning bidder for that item. The
item is transferred to the winning bidder. Total money collected is the fund raised by the penny social
auction.

## I have implemented this concept on blockchain. This provides the added advantage of credibility, anonymity and decentrailization.

For the sake of simplicity I have made a few assumptions.
* Fixed number of bidders, initialized to 4. All 4 need to self-register. Funds transfer from bidder is
automatically done and is not in the scope of this application.
* Fixed number of items to be auctioned off, initialized to 3.
* Items auctioned are indexed from 0..N-1 where N is the number of items for auction. N is 2.
* Each bidder buys just 1 sheet of tickets or tokens; each sheet has only 5 tokens.
* Assume simple number for the serial numbers for the sheet of tickets: 0,1,2,3. Here we show the
tokens of bidder 0 and 1.
