# Keebs-GH

This is a proposal of uniformisation of all the group buys occuring in the mechanical keyboard scene on the internet.

## Why?

The idea came when i figured out the number of interesting group buys i wanted to join but i missed because they were hidden in a huge number of threads. So the idea is to find a solution __TOGETHER__ to have a proper way to aggregate all the current group buys. Here is a proposal. If we could reach a standard format then we can build an aggregator for all the GB and make it easier for everyone to monitor.

__NOTE__: this project is COMPLETELY PROFITLESS and will stay in this state.

## Who

At the moment those communities have been in consideration for the aggregation:
- Geek Hack
- Reddit
- Desk Authority
- Keeb Talk

Some more?

## Constraints

All the active communities are not using the same forum framework, same post format and so on. Also people doing GroupBuys may not want to post to another platform. I don't want to be an administator of a platform to moderate all the submissions also.

## Proposal

### Standard Post Format

Using a standard post format we have a good start. For example https://www.reddit.com/r/mechmarket/ has a specific format for all the posts and for the group buys it's the same has https://geekhack.org/ .
Format is : `[GB] What ever ....`
Problem with this is we can't figure out the region of the GB and the end date. Proposal would be:
```
[GB] [REGION] [END-DATE] {TITLE} : {COMMENT}
```
#### Title

This describe the title of the group buy, which added to the region and date give us unicity to store it in the system.

#### Comment

I know some titles change during the group buy and it's normal, that's why this section has been added and could change throught the lifecycle of the group buy.

#### Region

This describe the region of the GB:
- US *United-States*
- EU *Europe*
- AS *Asia*
- WW *WorldWide*

#### End Date

This describe the end date of the group buy. The date format must be: MM/DD/YYYY

## Questions

- Does the status of the group buy may be added as a standard header format?
- Is it interesting to extend it to Interest Check?