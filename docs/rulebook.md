### General rules

Submitting known issues will result in PERMABAN, no appeals.
Reaching out to the protocol team directly about your payment will result in PERMABAN, no appeals.
Spam submissions will result in PERMABAN, no appeals.

### Reward FAQ

Rewards will be distributed all at once after the event has concluded and the mitigations have been applied.

Reward distribution per auditor will be determined transparently and distributed directly by bytes032.

**The pay-per-vulnerability formula will be:**
- **Critical** - $3500
- **High** - $1750
- **Medium** - $800

There is a total cap of $20,000. If during the audit the cap is reached, the audit is considered **finished** and NO MORE submissions are accepted.

Read about severities [here]()

### Findings FAQ

**Duplicates**

*The duplicates mechanism is borrowed from [Immunefi](https://immunefisupport.zendesk.com/hc/en-us/articles/20215594250385-DeGate-s-Boosted-Bug-Bounty-Reward-Distribution-Rules).*

For this audit, duplicates are going to be considered valid submissions.

Rewards for a given bug are split with 80% going to the primary finder and the remaining 20% being equally split among all other finders (Duplicates).

Example:
- A critical vulnerability is found. The primary finder gets $2800. $700 is shared between duplicates. 
- If you are the only duplicate, you get $700. If there are 20 duplicates, you get $35.

As long as the impact is clear there's no need to hyper-optimize a POC. 

For example, if you submit a clearly valid Critical bug, and the next day someone submits the same bug but with a hyper-optimized POC, then you'll still get the 80% for the payout.

**Similar exploits under a single issue**

*Borrowed from [C4 SC verdict](https://docs.google.com/document/d/1Y2wJVt0d2URv8Pptmo7JqNd0DuPk_qF9EPJAj3iSQiE/edit)*

The findings are duplicates if they share the same root cause. 

More specifically, if fixing the Root Cause (in a reasonable manner) would cause the finding to no longer be exploitable, then the findings are duplicates.

**Speculation on future code**

*Borrowed from [C4 SC verdict](https://docs.google.com/document/d/1Y2wJVt0d2URv8Pptmo7JqNd0DuPk_qF9EPJAj3iSQiE/edit)*

Any issue that is not exploitable within the scope of the audit is defined as speculating on future code. 

Any such speculation only has the potential to be valid if the root cause is demonstrated to be in the contest scope. 

An auditor may make an argument on why a future code change that would make the bug manifest is reasonably likely.

If the exploitability relies on a particular 3rd party integration, the likelihood must factor in a competent integrator who has done due diligence.
