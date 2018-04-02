---
aip: 1
title: Proposal Purpose and Guidelines
status: Draft
type: Meta
author: Scott Willeke (scott@willeke.com)
created: 2018-04-01
---

# What is an Agorex Improvement Proposal (AIP)? #
An AIP is a document providing information to the Agorex community or describing process that the Agorex community follows. The AIP should provide a concise specification of a process and a rationale for it. The AIP author is responsible for building consensus within the community and documenting dissenting opinions.


# Rational #
To encourage and support our goal of providing a public, open, honest, community-run decentralized exchange, we need a well defined process for collecting, discussing, and adopting processes that the Board of Directors executes on behalf of the community.

We intend for AIPs to be the primary mechanisms for the community to propose new processes, raise issues, and collect community input on processes and issues. AIPs serve as the official documentation for the the processes that the Board of Directors executes on behalf of the community. Because the AIPs are maintained as text files in a versioned repository, their revision history is the historical record of the proposal.


# Proposal Types #
There are three types of proposals:

- An **Informational Proposal** describes an issue, or provides general guidelines or information to the community, but does not propose a new feature. Informational proposals do not necessarily represent community consensus or a recommendation, so community members and users are free to ignore Informational proposals or follow their advice.
- A **Meta Proposal** describes a process surrounding Agorex or proposes a change to (or an event in) a process. Process proposals often require community consensus and unlike Informational Proposals, they are more than recommendations, and users are typically not free to ignore them. Examples include procedures, guidelines, changes to the decision-making process, and changes to the tools or environment used in Agorex development. Any meta-AIP is also considered a Process AIP.


# Proposal Workflow #
The [@Agorex-io/proposal-collaborators](https://github.com/orgs/Agorex-io/teams/proposal-collaborators) change the proposal status.

The Proposal process begins with a new idea for Agorex. It is highly recommended that a single proposal contain a single key proposal or new idea. The more focused the proposal, the more successful it tends to be. The proposal editor reserves the right to reject proposals if they appear too unfocused or too broad. If in doubt, split your proposal into several well-focused ones.

Each proposal must have a **champion** - someone who writes the proposal using the style and format described below, shepherds the discussions in the appropriate forums, and attempts to build community consensus around the idea.

Vetting an idea publicly before going as far as writing an proposal is meant to save the potential author time. Asking the community first if an idea is original helps prevent too much time being spent on something that is guaranteed to be rejected based on prior discussions (searching the Internet does not always do the trick). It also helps to make sure the idea is applicable to the entire community and not just the author. Examples of appropriate public forums to gauge interest around your proposal include [the Issues section of this repository](https://github.com/Agorex-io/Proposals/issues), [the Agorex subreddit](https://www.reddit.com/r/Agorex/), and [one of the Agorex Discord chat rooms](https://discord.gg/bEPhszu). In particular, [the Issues section of this repository](https://github.com/Agorex-io/Proposals/issues) is an excellent place to discuss your proposal with the community and start creating more formalized language around your proposal.

Once the champion has asked the community whether an idea has any chance of acceptance, the champion should present a draft proposal by submitting a [pull request](https://github.com/Agorex-io/Proposals/pulls). This gives the author a chance to continuously edit the draft AIP for proper formatting and quality. This also allows for further public comment and the author of the AIP to address concerns about the proposal.

If the [@Agorex-io/proposal-collaborators](https://github.com/orgs/Agorex-io/teams/proposal-collaborators)approve, the AIP editor will assign the AIP a number (generally the issue or PR number related to the AIP), label it as Informational or Meta, give it status "Draft", and add it to the git repository. The AIP editor will not unreasonably deny an AIP. Reasons for denying proposal status include duplication of effort, being technically unsound, not providing proper rational, or not in keeping with the Agorex values.

For an AIP to be accepted it must meet certain minimum criteria. It must be a clear and complete description of the proposed enhancement, process, or issue. The enhancement, process, or issue must represent a net improvement.

## Acceptance Process ##
In order to reach Accepted status, the pull request must be reviewed and approved by a majority of the [Agorex Board of Directors](https://github.com/orgs/Agorex-io/teams/board-of-directors). We use GitHub's [required reviews for pull requests](https://help.github.com/articles/about-required-reviews-for-pull-requests/) to enforce this review and approval process. Once the proposal is reviewed and accepted by the community, the status will be changed to "Final".


## Deferred, Rejected, and Superceeded ##

An AIP can also be assigned status "Deferred". The AIP author or editor can assign the AIP this status when no progress is being made on the AIP. Once an AIP is deferred, the AIP editor can re-assign it to draft status.

An EIP can also be "Rejected". Perhaps after all is said and done it was not a good idea. It is still important to have a record of this fact.

AIPs can also be superseded by a different EIP, rendering the original obsolete.

The possible paths of the status of EIPs are as follows:

![AIP Lifecycle](aip-1/lifecycle.png)

Informational and Process AIPs may also have a status of "Active" if they are never meant to be completed. E.g. EIP 1 (this EIP).


# Proposal Structure: What belongs in a successful Proposal? #

# Formats and Templates #

# Proposal Header Preamble #

# Auxiliary Files #

# Transferring Proposal Ownership #

# Proposal Editors #

# Proposal Editor Responsibilities and Workflow #

# History #

# Copyright #


# Assumptions #
- Assumes 2FA is required by the GitHub org and all directors on the Board of Directors are using 2FA when submitting PRs, commits, and reviewing proposals.
- Assumes [required reviews have been set up **to include repository admins**](https://help.github.com/articles/enabling-required-reviews-for-pull-requests) option is on.
- Assumes [Dismiss stale pull request approvals when new commits are pushed](https://help.github.com/articles/enabling-required-reviews-for-pull-requests/) option is on.
- Assumes that **Board of Directors** is how we refer to the governing body for the community.
  - I'm using "Board of Directors" as we have referred to it this way most often (and in AIP-2 issue discussions).
- Assumes the target size for the Board of Directors is 9.

# Open Issues / TODO #
- [ ] Near the mention of "We use GitHub's [required reviews for pull requests]" above, but that is for every review/pull of the PR. PRs can be merged in a Draft status without being accepted. More final status (Accepted, Deferred, Rejected, and Replaced, Final) require more careful reviews. That needs clarified. Or we could make a different directory for Draft proposals and Accepted/Finalized/Active/Replaced proposals to keep the review/approval requirement lower for Draft proposals.

- [ ] Set up the [@Agorex-io/proposal-collaborators](https://github.com/orgs/Agorex-io/teams/proposal-collaborators) team.
- [ ] Set up the [@Agorex-io/board-of-directors](https://github.com/orgs/Agorex-io/teams/board-of-directors) team.
- [ ] README.md
- [ ] add PULL_REQUEST_TEMPLATE.md
- [ ] Document and link to "Agorex values" above.
- [ ] Double check by searching for EIP and Ethereum in doc content.

# References #
- Pull Request Reviews: https://help.github.com/articles/about-pull-request-reviews/
- https://github.com/Agorex-io/Proposals/issues/1





-----------

AIP folder structure.

Statuses: 

All AIPs submitted as a PR

Required reviews:
Use Github required  https://help.github.com/articles/enabling-required-reviews-for-pull-requests/ to make X of N council members required



Only board/council members








I think we're aligned for now. I'll write up the draft and submit a PR. You all comment on it and we'll iterate on it with the intention to get it accepted this week.







# Future Consideration #
- Use PGP-signed commits?

# References #
- [About required reviews for pull requests (GitHub)](https://help.github.com/articles/about-required-reviews-for-pull-requests/) [Enabling required reviews for pull requests (GitHub)](https://help.github.com/articles/enabling-required-reviews-for-pull-requests/)






----------

# TODO #
- Add contributor guidelines: https://help.github.com/articles/setting-guidelines-for-repository-contributors/
- Bitcoin Talk Announcement
- Reddit
- Get website running
- Trading contract (that can be upgraded seamlessly)
- Consider COZ / NEO Governance for AIP-2: https://cityofzion.io/#governance, https://github.com/CityOfZion/governance