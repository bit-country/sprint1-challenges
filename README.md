# Sprint 1 Challenges

This challenge designed for all contributors to Bit.Country Tewai Chain who would like to get involved in Bit.Country development.

You can submit the challenges by sending an email to dev@bit.country or feel free to invite Bit.Country Core Contributor to your repo to review your code.(check out who are contributors on Challenge 1).

Let's get started!

## Challenge 1:

Getting to know and understand the concept of Bit.Country chain.

<ul>
<li>Clone Bit.Country Blockchain repo using <strong>challenges-v1</strong> branch Don't forget to leave a <strong>Star</strong> to show your support.</li>
<li><code>git clone -b challenges-v1 https://github.com/bit-country/Bit-Country-Blockchain.git </code></li>
<li>Ensure everything works as expected by compiling the code</li>
</ul>



## Challenge 2:

Implement Auction unit-test.

You may have seen the auction pallet has implemented some basic functionality of auctioning the Asset in the Bit.Country. However, there are missing some unit test for the Auction functionality. 

You need to write at least 5 test cases to ensure the Auction pallet working as expected. 

Here are some sample test cases but not limited to

<ul>
<li>Create auction</li>
<li>Bidding successful.</li>
<li>Biding fail due to insufficient fund</li>
<li>Simulate expired block number to ensure the Asset ownership transfer correctly after the end of the auction</li>
<li>Self bidding should be rejected</li>
<li>Bid on expired Auction</li>
</ul>



## Challenge 3:

Country Staking Pallet Design

Design the staking pallet that allows staking on country to earn reward per era. For the sake of simplicity, please consider the following into the consideration

<ul>
<li>Reward calculation could be a fixed percentage of own token staked per era (e.g 10 percent)</li>
<li>Reward distribution mechadism: either executed by offchain worker or your own innovation. You can check out how Polkadot payout reward through authorship with note_uncles and note_author. [pallet_staking](https://github.com/paritytech/substrate/blob/master/frame/staking/src/lib.rs#L3247)</li>
<li>No Slashing</li>
</ul>


## Challenge 4:

Country Staking Pallet implementation.

Implement into code based on the Design from Challenge 3. The code need to follow the naming convention, syntax standard, proven logic by having unit test covered.
