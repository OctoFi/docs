---
layout: default
title: DAOctopus
nav_order: 4
---

# 🐙 DAOctopus

The OCTO community governance platform [dao.octo.fi](https://dao.octo.fi) 
{: .fs-6 .fw-300 }

---

## Snapshot Governance Tutorial

[dao.octo.fi](https://dao.octo.fi) --> [snapshot.page/#/octofi](https://snapshot.page/#/octofi)

Openness and transparency are central to OctoFi’s mission in the delivery of decentralized finance <s>oracles</s> tentacles, and an accessible governance tool such as Snapshot is an essential component.

The primary use-case afforded by project supporters will be the foundational governance decisions. During early stages, OCTO governance tokens shall be used for the following:

- Participating in voting to settle governance decisions 
- Verifying data tentacles and support systems with staking
- Interest Program (Octo Yield)

### How to use Snapshot as proposal creator

1. Go to [dao.octo.fi](https://dao.octo.fi)
2. Click on the button in the right corner “Connect wallet”
3. Connect with one of the three wallet providers, where you hold $OCTO
4. Click on the button “New proposal” at the main page [snapshot.page/#/octofi](https://snapshot.page/#/octofi)
5. Fill out the field Title: OIP-\[consecutive number\] Title of your Proposal
6. Fill out the biggest field and tell the community about your idea or question, go into every detail. Don't forget plans about how to execute the idea or question, and funding, if needed.
7. Place the voting options 
8. Now go to the “Actions” box 
9. Select the start date 
10. Select the end date (Remember to give enough time for voting)
11. Fill out the Snapshot block number (now it's getting a bit crazy, read more about that number in the next section)


**Snapshot block number**

This number is important to lock the state of community members who are able to vote.

Means if you come around a nice proposal and the block number is in the past and you don't own any $OCTO yet or before the block number, you can't vote.

`H = h + ((t1 — t0) / a)`

Where:

- `H` = target block height
- `h` = current block height
- `t0` = current timestamp (in seconds)
- `t1` = target timestamp (in seconds)
- `a` = average time to solve a block (in seconds)

Easy right ?

Or... 

`last_block_number + ((future_time - time_now) / block_time)`

So, for example, using a [current epoch time](https://www.epochconverter.com) of 1481214124, the epoch time of 1482537600 for midnight Christmas Eve, and the last block of 2771338:

`2771338 + ((1482537600 - 1481214124) / 14) = 2865872`

Or just look at [etherscan.io/blocks](https://etherscan.io/blocks) and use the last block number ;-)

12. Click on “Publish” and create the proposal 
13. Sign the message via your wallet and done

### How to use Snapshot for voting

1. Go to [dao.octo.fi](https://dao.octo.fi)
2. Click on the button in the right corner “Connect wallet”
3. Connect with one of the three wallet provider, where you hold $OCTO
4. Click on the option you want to vote for 
5. Sign the message via your wallet and done

To test your voting capabilities, let's start with a simple question.

[*Who was Satoshi Nakamoto?*](https://snapshot.page/#/octofi/proposal/QmWHHTcf4tF4XvJSyaZzL5BmhV2xwoFvBh5rBoqGWXvGvi)
