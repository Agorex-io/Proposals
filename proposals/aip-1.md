---
aip: 1
title: Proposal Purpose and Guidelines
status: Draft
type: Process
author: Scott Willeke (scott@willeke.com)
created: 2018-04-01
---

# What is an Agorex Improvement Proposal (AIP)? #
An AIP is a document providing information to the Agorex community or describing process that the Agorex community follows. The AIP should provide a concise specification of a process and a rationale for it. The AIP author is responsible for building consensus within the community and documenting dissenting opinions.


# Rational #
To encourage and support our goal of providing a public, open, honest, community-run decentralized exchange, we need a well defined process for collecting, discussing, and adopting processes that the Board of Directors executes on behalf of the community.

We intend for AIPs to be the primary mechanisms for the community to propose new processes, raise issues, and collect community input on processes and issues. AIPs serve as the official documentation for the the processes that the Board of Directors executes on behalf of the community. Because the AIPs are maintained as text files in a versioned repository, their revision history is the historical record of the proposal.


# Proposal Types #
There are currently two types of proposals:

- An **Informational Proposal** describes an issue, or provides general guidelines or information to the community. Informational proposals do not necessarily represent community consensus or a recommendation, so community members and users are free to ignore Informational Proposals or follow their advice.

- A **Process Proposal** describes a process surrounding Agorex or proposes a change to (or an event in) a process. Process Proposals often require community consensus and unlike Informational Proposals, they are more than recommendations, and users are typically not free to ignore them. Examples include procedures, guidelines, changes to the decision-making process, and changes to the tools or environment used in Agorex development.


# Proposal Workflow #

The Proposal process begins with a new idea for Agorex. It is highly recommended that a single proposal contain a single key proposal or new idea. The more focused the proposal, the more successful it tends to be. The proposal editor reserves the right to reject proposals if they appear too unfocused or too broad. If in doubt, split your proposal into several well-focused ones.

Each proposal must have a **champion** - someone who writes the proposal using the style and format described below, shepherds the discussions in the appropriate forums, and attempts to build community consensus around the idea.

Vetting an idea publicly before going as far as writing an proposal is meant to save the potential author time. Asking the community first if an idea is original helps prevent too much time being spent on something that is guaranteed to be rejected based on prior discussions (searching the Internet does not always do the trick). It also helps to make sure the idea is applicable to the entire community and not just the author. Examples of appropriate public forums to gauge interest around your proposal include [the Issues section of this repository](https://github.com/Agorex-io/Proposals/issues), [the Agorex subreddit](https://www.reddit.com/r/Agorex/), and [one of the Agorex Discord chat rooms](https://discord.gg/bEPhszu). In particular, [the Issues section of this repository](https://github.com/Agorex-io/Proposals/issues) is an excellent place to discuss your proposal with the community and start creating more formalized language around your proposal.

Once the champion has asked the community whether an idea has any chance of acceptance, the champion should present a draft proposal by submitting a [pull request](https://github.com/Agorex-io/Proposals/pulls). This gives the author a chance to continuously edit the draft AIP for proper formatting and quality. This also allows for further public comment and the author of the AIP to address concerns about the proposal. 

The [@Agorex-io/proposal-editors](https://github.com/orgs/Agorex-io/teams/proposal-editors) facilitate champions and authors in the process. If they recommend it, a Proposal Editor will assign the AIP a number (generally the issue or PR number related to the AIP), label it as Informational or Process, give it status **Draft** (this is all done in the same PR branch). The AIP editor will not unreasonably deny an AIP in Draft status. Reasons for denying proposal status include duplication of effort, being technically unsound, not providing proper rational, or not in keeping with the Agorex values.

For an AIP to be merged Draft status it still must meet certain minimum criteria. It must be a clear and complete description of the proposed process or issue. The process or issue must represent a net improvement.

## Acceptance Process ##

Once an AIP has been reviewed by a Proposal Editor, the Editor can recommend it for a vote for approval by the [Agorex Board of Directors](https://github.com/orgs/Agorex-io/teams/board-of-directors). Proposal pull requests must be reviewed and approved by a majority of the [Agorex Board of Directors](https://github.com/orgs/Agorex-io/teams/board-of-directors). We use GitHub's [required reviews for pull requests](https://help.github.com/articles/about-required-reviews-for-pull-requests/) to enforce this review and approval process. 


While the [Agorex Board of Directors](https://github.com/orgs/Agorex-io/teams/board-of-directors) should quite liberally accept Draft status proposals subject to the criteria above, merging a proposal with a **Final** status such as **Final** or **Replaced** requires more review and rigor since, by merging a Final proposal The Board is agreeing to execute the proposed process on behalf of the community.

Once the proposal is reviewed and approved by The Board on behalf of the community, the status will be changed to "Final" and it will be merged.


## Deferred, Rejected, and Replaced ##

An AIP can also be assigned status **Deferred**. The AIP author or editor can assign the AIP this status when no progress is being made on the AIP. Once an AIP is deferred, the AIP editor can re-assign it to Draft status.

An AIP can also be **Rejected**. Perhaps after all is said and done it was not a good idea. It is still important to have a record of this fact.

AIPs can also be superseded by a different AIP, rendering the original obsolete. In this the superseeded Proposal should be marked as **Replaced** as part of the PR that the superseeding proposal is being proposed in.

## Proposal Statuses ##
The possible paths of the status of AIPs are as follows:

  Draft -> Accepted -> Final
  Draft -> Withdrawn
  Draft -> Rejected
  Draft -> Deferred
  Final -> Replaced

Unlike the EIP process, Informational and Process AIPs do not have the status "Active" and will have the status Final when they are accepted and the board is expected to execute the proposals on behalf of the community.


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
- **Roles:**
  - ONLY the [@Agorex-io/board-of-directors](https://github.com/orgs/Agorex-io/teams/board-of-directors) can approve proposals that move beyond a PR and end up merged to the repository. 
  - [@Agorex-io/proposal-editors](https://github.com/orgs/Agorex-io/teams/proposal-editors) cannot approve, but can facilitate the process and guide champions and authors. They can also edit PRs in progress to help get the preamble and formatting correct according to the workflow. 
  
- Assumes [required reviews have been set up **to include repository admins**](https://help.github.com/articles/enabling-required-reviews-for-pull-requests) option is on.
- Assumes [Dismiss stale pull request approvals when new commits are pushed](https://help.github.com/articles/enabling-required-reviews-for-pull-requests/) option is on.
- Assumes that **Board of Directors** is how we refer to the governing body for the community.
  - I'm using "Board of Directors" as we have referred to it this way most often (and in AIP-2 issue discussions).
- Assumes the target size for the Board of Directors is 9.
- Note that the EIP process in EIP-1 is written focused on proposals for featurs and feels retrofitted for process and informational proposals. I am trying to make this more designed around community/structural proposals first, and expect we'll add a "feature proposal" type later. I think this will be better basis for the process in our case (which is decidedly different circumstance than Ethereum which also maintains a protocol with many clients & implementations).


# Open Issues / TODO #
- [ ] Near the mention of "We use GitHub's [required reviews for pull requests]" above, but that is for every review/pull of the PR. PRs can be merged in a Draft status without being accepted. More final status (Accepted, Deferred, Rejected, and Replaced, Final) require more careful reviews. That needs clarified. Or we could make a different directory for Draft proposals and Accepted/Finalized/Active/Replaced proposals to keep the review/approval requirement lower for Draft proposals.
    - It can be difficult to easily preserve and view file history across renames, so I think we just require n of M board approvals for ALL pulls and make sure that they are trained to quite liberally merge draft proposals and very judiciously merge proposals with any other "final" status.
- [ ] Set up the [@Agorex-io/proposal-editors](https://github.com/orgs/Agorex-io/teams/proposal-editors) team.
- [ ] Set up the [@Agorex-io/board-of-directors](https://github.com/orgs/Agorex-io/teams/board-of-directors) team.
  - Initially proposal-editors and board-of-directors are likely to be the same members. Long term this may scale better to keep them separate.
- [ ] README.md
- [ ] add PULL_REQUEST_TEMPLATE.md
- [ ] Document and link to "Agorex values" above.
- [ ] Double check by searching for EIP and Ethereum in doc content.
- [ ] Double check by searching for Meta -> Proposal in doc content.
- Low priority:
  - [ ] Setup github pages on the repo.

# References #
- Pull Request Reviews: https://help.github.com/articles/about-pull-request-reviews/
- https://github.com/Agorex-io/Proposals/issues/1


# Future Consideration #
- Use PGP-signed commits?

# References #
- [About required reviews for pull requests (GitHub)](https://help.github.com/articles/about-required-reviews-for-pull-requests/) [Enabling required reviews for pull requests (GitHub)](https://help.github.com/articles/enabling-required-reviews-for-pull-requests/)
