---
layout: default
title: Governance
parent: 🛠️ Tools
nav_order: 1
---

# Governance
{: .fs-9 }
{: .d-inline-block }

Stable
{: .label .label-green }

Participate in DAO governance and voting.
{: .fs-6 .fw-300 }


[Launch App](https://app.octo.fi){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [Learn More](/docs/tools/explore){: .btn .fs-5 .mb-4 .mb-md-0 }

---

![](/assets/images/govern.jpg)

## Governance Tutorial

OctoFi empowers users to participate in governance for hundreds of projects, powered by Snapshot.

Contribute to foundational governance decisions such as:

- Community voting on new features to be implemented
- Funding allocations for development initiatives
- Decentralized listings and integrations process

![](/assets/images/govern-1.jpg)

### How to use Snapshot as proposal creator

1. Go to [app.opcto.fi](https://app.octo.fi) and connect wallet.
2. Ensure your selected wallet is where you hold $OCTO.
3. Navigate to Tools > Governance and select your chosen project.
4. Click on the button “Create New” top right of proposal list.
5. Fill out the field "Question" and it will be used at the title.
6. Fill out the "What is your Proposal" section and go into every possible detail. Don't forget plans about how to execute the idea or question, and funding, if needed.
7. Enter the voting options in the "Choices" section 
9. Select the Start Date 
10. Select the End Date (remember to allow enough time for voting)
11. Fill out the "Snapshot" field with relevant block number (you'll need read more about that number in the next section)

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

![](/assets/images/govern-2.jpg)

### How to use Snapshot for voting

1. Go to [app.opcto.fi](https://app.octo.fi) and connect wallet.
2. Ensure your selected wallet is where you hold $OCTO.
3. Navigate to Tools > Governance and select your chosen project.
4. Click on the option you want to vote for 
5. Sign the message via your wallet and you are done

To test your voting capabilities, cast your vote on OIP-0 which is set up purely for this tutorial.
