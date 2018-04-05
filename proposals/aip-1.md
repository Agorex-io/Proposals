---
aip: 1
title: Proposal Purpose and Guidelines
author: Scott Willeke (scott@willeke.com)
discussions-to: https://github.com/Agorex-io/Proposals/issues/1
status: Draft
type: Process
created: 2018-04-01

---

# What is an Agorex Improvement Proposal (AIP)? #
An AIP is a document providing information to the Agorex community or describing a new process that the Board of Directors executes on behalf of the exchange's community. The AIP should provide a rationale for and concise specification of the process. The AIP author is responsible for building consensus within the community and documenting dissenting opinions.

# Rationale #
To encourage and support our goal of providing a public, open, honest, community-run decentralized exchange, we need a well defined process for collecting, discussing, and adopting processes that the Board of Directors executes on behalf of the community.

We intend for AIPs to be the primary mechanisms for the community to propose new processes, raise issues, and collect community input on processes and issues. AIPs serve as the official documentation for the the processes that the Board of Directors executes on behalf of the community. Because the AIPs are maintained as text files in a versioned repository, their revision history is the historical record of the proposal.


# Proposal Types #
There are currently two types of proposals:

- An **Informational Proposal** describes an issue, or provides general guidelines or information to the community. Informational proposals do not necessarily represent community consensus or a recommendation, so community members and users are free to ignore Informational Proposals or follow their advice.

- A **Process Proposal** describes a process surrounding Agorex or proposes a change to (or an event in) a process. Process Proposals often require community consensus and unlike Informational Proposals, they are more than recommendations, and users are typically not free to ignore them. Examples include procedures, guidelines, changes to the decision-making process, and changes to the tools or environment used in Agorex development.


# Proposal Workflow #
The Proposal process begins with a new idea for Agorex. It is highly recommended that a single proposal contain a single key proposal or new idea. The more focused the proposal, the more successful it tends to be. The proposal editor reserves the right to reject proposals if they appear too unfocused or too broad. If in doubt, split your proposal into several well-focused ones.

Each proposal must have a **champion** - someone who writes the proposal using the style and format described below, shepherds the discussions in the appropriate forums, and attempts to build community consensus around the idea.

Vetting an idea publicly before going as far as writing an proposal is meant to save the potential author time. Asking the community first if an idea is original helps prevent too much time being spent on something that is guaranteed to be rejected based on prior discussions (searching the Internet does not always do the trick). It also helps to make sure the idea is applicable to the entire community and not just the author. Examples of appropriate public forums to gauge interest around your proposal include [the Issues section of this repository], [the Agorex subreddit], and one of [the Agorex Discord chat rooms]. In particular, [the Issues section of this repository] is an excellent place to discuss your proposal with the community and start creating more formalized language around your proposal.

Once the champion has asked the community whether an idea has any chance of acceptance, the champion should present a draft proposal by submitting a [pull request in this repository]. This gives the author a chance to continuously edit the draft AIP for proper formatting and quality. This also allows for further public comment and the author of the AIP to address concerns about the proposal. 

The [@Agorex-io/proposal-editors] facilitate champions and authors in the process. If they recommend it, a Proposal Editor will assign the AIP a number (generally the issue or PR number related to the AIP), label it as Informational or Process, give it status **Draft** (this is all done in the same PR branch). The AIP editor will not unreasonably deny an AIP in Draft status. Reasons for denying proposal status include duplication of effort, being technically unsound, not providing proper rationale, or not in keeping with the Agorex values.

For an AIP to be merged Draft status it still must meet certain minimum criteria. It must be a clear and complete description of the proposed process or issue. The process or issue must represent a net improvement.

## Acceptance Process ##

Once an AIP has been reviewed by a Proposal Editor, the Editor can recommend it for a vote for approval by the [Agorex Board of Directors]. Proposal pull requests must be reviewed and approved by a majority of the [Agorex Board of Directors]. We use GitHub's [required reviews for pull requests] to enforce this review and approval process. 


While the [Agorex Board of Directors] should quite liberally accept **Draft** status proposals subject to the criteria above, merging a proposal with a **Final** status such as **Final** or **Replaced** requires more review and rigor since, by merging a Final proposal The Board is agreeing to execute the proposed process on behalf of the community.

Once the proposal is reviewed and approved by The Board on behalf of the community, the status will be changed to "Final" and it will be merged. By merging an **Accepted** proposal, the Board is explicitly acknowledging their responsibility and intent to execute the proposed process on behalf of the community.


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


## Proposal Maintenance & Updates ##
Informational and Process AIPs may be updated over time to reflect changes to processes and other details. The precise process followed in these cases will depend on the nature and purpose of the AIP being updated.

# Proposal Structure: What belongs in a successful AIP? #

Each AIP should have the following parts:

- Preamble - [RFC 822] style headers containing metadata about the AIP, including the AIP number, a short descriptive title (limited to a maximum of 44 characters), the names, and optionally the contact info for each author, etc.

- Simple Summary - "If you can’t explain it simply, you don’t understand it well enough." Provide a simplified and layman-accessible explanation of the AIP.

- Abstract - a short (~200 word) description of the technical issue being addressed.

- Motivation - The motivation should explain what motivated the proposal, including a clear explanation of the problem that the AIP solves, and why a current process or (lack thereof) is inadequate to address the problem. AIP submissions without sufficient motivation may be rejected outright. 

- Rationale - The rationale fleshes out the proposal by describing why particular decisions were made. It should describe alternatives that were considered and reference any related works. The rationale should provide evidence of consensus within the community and discuss important objections or concerns raised during discussion.

- Copyright Waiver - All AIPs must be in public domain. See the bottom of this AIP for an example copyright waiver.


# Formats and Templates #
Proposals should be written in [markdown] format. Image files should be included in a subdirectory for that proposal.


# Proposal Header Preamble #
Each proposal must begin with an RFC 822 style header preamble, preceded and followed by three hyphens ('---'). The headers must appear in the following order. Headers marked with "*" are optional and are described below. All other headers are required.

` aip: ` <AIP number> (this is determined by the AIP Editor)

` title: ` \<AIP title\>

` author: `\<list of author's real names and optionally, email address\>

` * discussions-to: ` \<URL or mailing list address\>

` status: ` <Draft | Accepted | Deferred | Rejected | Withdrawn | Final | Superseded>

` type: `<Informational | Process>

` created: `<date created on, in ISO 8601 (yyyy-mm-dd) format>

` * requires: ` <AIP number(s)>

` * replaces: ` <AIP number(s)>

` * superseded-by: ` <AIP number(s)>


The `author` header lists the names, and optionally the email addresses of all the authors/owners of the AIP. The format of the Author header value must be `Random J. User <address@dom.ain>`. If the email address is included, and just `Random J. User` if the address is not given.

If there are multiple authors, each should be on a separate line following RFC 2822 continuation line conventions. Note that **personal email addresses in AIPs may not be obscured** as a defense against spam harvesters.

While an AIP is a draft, a `discussions-to` header will indicate the URL (preferred) or mailing list where the AIP is being discussed (preferably an issue in [the Issues section of this repository]).

The `type` header specifies the type of AIP: Process or Informational.

The `created` header records the date that the AIP was assigned a number. The header should be in yyyy-mm-dd format, e.g. 2001-08-14.

AIPs may have a `requires` header, indicating the AIP numbers that this AIP depends on.

AIPs may also have a `superseded-by` header indicating that an AIP has been rendered obsolete by a later document; the value is the number of the AIP that replaces the current document. The newer AIP must have a `replaces` header containing the number of the AIP that it rendered obsolete.

Headers that permit lists must separate elements with commas.


# Auxiliary Files #
AIPs may include auxiliary files such as diagrams. Such files must be named `aip-XXXX-Y.ext`, where "XXXX" is the AIP number, "Y" is a serial number (starting at 1), and "ext" is replaced by the actual file extension (e.g. "png").


# Transferring Proposal Ownership #
It occasionally becomes necessary to transfer ownership of AIPs to a new champion. In general, we'd like to retain the original author as a co-author of the transferred AIP, but that's really up to the original author. A good reason to transfer ownership is because the original author no longer has the time or interest in updating it or following through with the AIP process, or has fallen off the face of the 'net (i.e. is unreachable or not responding to email). A bad reason to transfer ownership is because you don't agree with the direction of the AIP. We try to build consensus around an AIP, but if that's not possible, you can always submit a competing AIP.

If you are interested in assuming ownership of an AIP, send a message asking to take over, addressed to both the original author and the AIP editor. If the original author doesn't respond to email in a timely manner, the AIP editor will make a unilateral decision (it's not like such decisions can't be reversed :).


# Proposal Editors #
The current AIP editors are members of the [@Agorex-io/proposal-editors] team.


# Proposal Editor Responsibilities and Workflow #
For each new AIP that comes in, an editor does the following:

- Read the AIP to check if it is ready: sound and complete. The ideas must technically make sense, even if they don't seem likely to be accepted.
- The title should accurately describe the content.
- Work with the author/champion to edit the AIP for language (spelling, grammar, sentence structure, etc.), markup (Github flavored Markdown).

If the AIP isn't ready, an editor will send it back to the author for revision, with specific instructions.

Once the AIP is ready for the repository, a AIP editor will:

- Assign an AIP number (generally the PR number or, if preferred by the author, the Issue number if there was discussion in [the Issues section of this repository] about this AIP).
- Recommend to the [Agorex Board of Directors] that they review and approve the corresponding pull request as described in _Proposal Workflow_ above.
- Merge the pull request to master upon approval of the Board.
- Send a message back to the AIP author with the next step (tagging them in an Issue comment or PR is sufficient).

AIP editors don't pass judgment on AIPs. They merely do the administrative & editorial part (which is generally a low volume task).


# Acknowledgements #
This document was derived heavily from [Ethereum's EIP 1] which was derived from [Bitcoin's BIP-0001] written by Amir Taaki which in turn was derived from [Python's PEP-0001]. In many places text was simply copied and modified. Although the EIP-1 text was written by Martin Becze and Hudson Jameson, the PEP-0001 text was written by Barry Warsaw, Jeremy Hylton, and David Goodger, they are not responsible for its use in the Agorex Improvement Process, and should not be bothered with questions specific to Agorex or the AIP. Please direct all comments to the AIP editors.

Thanks to [Jonathon Dunford], [Rohat Sahin], and other community members for their feedback and suggestions in the discussions on this proposal.


  [@Agorex-io/board-of-directors]: https://github.com/orgs/Agorex-io/teams/board-of-directors
  [Agorex Board of Directors]: https://github.com/orgs/Agorex-io/teams/board-of-directors
  [@Agorex-io/proposal-editors]: https://github.com/orgs/Agorex-io/teams/proposal-editors
  [the Issues section of this repository]: https://github.com/Agorex-io/Proposals/issues
  [the Agorex subreddit]: https://www.reddit.com/r/Agorex/
  [the Agorex Discord chat rooms]: https://discord.gg/bEPhszu
  [pull request in this repository]: https://github.com/Agorex-io/Proposals/pulls
  [required reviews for pull requests]: https://help.github.com/articles/about-required-reviews-for-pull-requests/
  [Enabling required reviews for pull requests (GitHub)]: https://help.github.com/articles/enabling-required-reviews-for-pull-requests/
  [RFC 822]: http://www.faqs.org/rfcs/rfc822.html
  [The Ethereum Community's EIP-1]: https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md
  [The Python Community's PEP 1]: https://www.python.org/dev/peps/pep-0001/
  [Ethereum's EIP 1]: https://github.com/ethereum/EIPs/blob/a90a5a3e58accea956dd8f1eacac5a17f98ec2e2/EIPS/eip-1.md
  [markdown]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
  [Bitcoin's BIP-0001]: https://github.com/bitcoin/bips
  [Python's PEP-0001]: https://www.python.org/dev/peps/
  [Jonathon Dunford]: https://github.com/JonathonDunford
  [Rohat Sahin]: https://github.com/rowmagnon

# Copyright #
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
