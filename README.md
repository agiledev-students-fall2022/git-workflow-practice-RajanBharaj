# Application Security

If you didn't hear, recently, Uber was hacked. Find out more about this [here](https://www.bbc.com/news/technology-62925047). After reading the article, I learned that Uber was enrolled in a Bug Bounty program. I want to start an open debate about the benefits and fallbacks of Bug Bounty programs, and its effect on overall application security. 

### Bug Bounty Hunting

For those who don't know, bug bounties are a way to incentivise ethical hacking and decentivise black hat hackers. The idea is that companies enroll in or provide themselves Bug Bounty programs whereby they payout rewards to hackers who successsfully exploit vulnerabilities in their software and report it directly back to them. Usually the company defines a limited scope of what they want to be tested, and hackers have free reign to test exploits within that scope. Companies can choose either a predetermined payout, or to provide a payout structure whereby the more severe the vulnerability found/exploited, the higher the payout.

As we know from the article linked above, Uber was enrolled in such a program, so the question remains, is Bug Bounty hunting enough?

There are a few key problems with Bug Bounty hunting:
- **The limited scope**: The smaller the scope given in a bug bounty program, the less complete the penetration tests of hackers can be.
- **The compensation**: While the legality of bug bounties afford hackers with significantly less risk, they also provide significantly less reward. For hackers used to working black hat, the reward may not be enough to turn them ethical.
- **Quality assurance**: Does enrollment in bug bounty programs assist quality assurance, or make it so that quality assurance engineers are less motivated to do complete work?

Personally, I think Bug Bounty programs are the way forward, however, I think the issues outlined above need addressing. If we really want to deter black hat hackers, we have to provide fairer compensation and greater incentives. 

Related to software engineering, do you think it is the fault of poor engineering or quality assurance? Additionally, do you think that enrollment in such programs allows for sloppier work to be approved for production? In an ideal world, both quality assurance engineers and the Bug Bounty would work in tandem to provide a safer application. But does that really happen?

What do you think?

