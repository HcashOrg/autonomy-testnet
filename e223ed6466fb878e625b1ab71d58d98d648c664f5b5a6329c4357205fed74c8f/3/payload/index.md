HC Bug Bounty Proposal
# HC-Bug-Bounty-Proposal
## What:

I suggest we start a bug bounty program to find security vulnerabilities in hc. This would help us improve our overall security posture and get a fresh set of eyes on our code and websites.

## Why:
We do not currently have a formal bug bounty program. A bug bounty program aims to use collective intelligence of many "bug bounty hunters" to find and fix security vulnerabilities.

Many times I observe people visiting our chatrooms and inquiring about a bug bounty program which shows there is a real interest in people who want to find vulnerabilities in HcashOrg and report them for an award.Having a formal program will enable us to funnel all reports through one single process and ensure that valid reports are looked at and fixed while keeping away bad reports that take up valuable dev time.

## How:
We will have a selfhosted program and use a @HcashOrg.org email for getting bug bounty reports.The bug bounty hunters will be sending us PGP encrypted emails of their findings in a predefined format.

We will be using the OWASP Risk Rating Methodology for scoring and prioritizing vulnerabilities (https://www.owasp.org/index.php/OWASP_Risk_Rating_Methodology)

We will also take into consideration the impact on the HcashOrg ecosystem. An RCE in dcrdocs (Low impact) is not the same as an RCE in dcrd or hcgui (Higher impact)

OWASP Risk Rating Methodology

Indicative payout amounts:

Note: up to 300 USD

Low: up to 1,000 USD

Medium: up to 3,000 USD

High: up to 10,000 USD

Critical: up to 25,000 USD

> To achieve all this we need a group of "vulnerability validators" who are verifiedHC contractors. Their jobs are as follows.