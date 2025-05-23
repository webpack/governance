# webpack Project Governance

webpack is an open source project that depends on contributions from the community. Anyone may contribute to the project at any time by submitting code, participating in discussions, making suggestions, or any other contribution they see fit. This document describes how various types of contributors work within the webpack project.

* [Roles and Responsibilities](#roles-and-responsibilities)
  * [Contributors](#contributors)
  * [Committers](#committers)
  * [Reviewers](#reviewers)
* [Technical steering committee](#technical-steering-committee)
  * [TSC meetings](#tsc-meetings)
* [Consensus seeking process](#consensus-seeking-process)

## Roles and Responsibilities

### Contributors

Contributors are community members who contribute in concrete ways to the project, most often in the form of code and/or documentation. Anyone can become a Contributor, and contributions can take many forms. There is no expectation of commitment to the project, no specific skill requirements, and no selection process.

Contributors have read-only access to source code and so submit changes via pull requests. Contributor pull requests have their contribution reviewed and merged by a TSC member. TSC members and Committers work with Contributors to review their code and prepare it for merging.

As Contributors gain experience and familiarity with the project, their profile within, and commitment to, the community will increase. At some stage, they may find themselves being nominated as either a Website Team Member or Committer by an existing Website Team Member or Committer.

### Committers

Committers are community members who have shown that they are committed to the continued development of the project through ongoing engagement with the community. Committers are given push access to the project's GitHub repos and must abide by the project's [Contribution Guidelines](https://github.com/webpack/webpack/blob/main/CONTRIBUTING.md)

To become a Committer:

* One must have shown a willingness and ability to participate in the project as a team player. Typically, a potential Committer will need to show that they have an understanding of and alignment with the project, its objectives, and its strategy.
* Committers are expected to be respectful of every community member and to work collaboratively in the spirit of inclusion.

New Committers can be nominated by any existing Committer. Once they have been nominated, there will be a vote by the TSC members.

It is important to recognize that committership is a privilege, not a right. That privilege must be earned and once earned it can be removed by the TSC members by a standard TSC motion. However, under normal circumstances committership exists for as long as the Committer wishes to continue engaging with the project.

A Committer who shows an above-average level of contribution to the project, particularly with respect to its strategic direction and long-term health, may be nominated to become a reviewer, described below.

### Reviewers

Reviewers are community members who have contributed a significant amount of time to the project through triaging of issues, fixing bugs, implementing enhancements/features, and are trusted community leaders.

Reviewers may perform all of the duties of Committers, and also:

* May merge external pull requests for accepted issues upon reviewing and approving the changes.
* May merge their own pull requests once they have collected the feedback they deem necessary. (No pull request should be merged without at least one Committer/Reviewer/TSC member comment stating they've looked at the code.)

To become a Reviewer:

* Work in a helpful and collaborative way with the community.
* Have given good feedback on others' submissions and displayed an overall understanding of the code quality standards for the project.
* Commit to being a part of the community for the long-term.

A Committer is invited to become a Reviewer by existing Reviewers and TSC members. A nomination will result in discussion and then a decision by the TSC.

## Technical Steering Committee

A subset of the collaborators forms the Technical Steering Committee (TSC).
The TSC has final authority over this project, including:

* Technical direction
* Project governance and process (including this policy)
* Contribution policy
* GitHub repository hosting
* Conduct guidelines
* Maintaining the list of collaborators

The current list of TSC members is in
[the project README](https://github.com/webpack/webpack/blob/main/README.md#current-project-members).

The [TSC Charter][] governs the operations of the TSC. All changes to the
Charter need approval by the OpenJS Foundation Cross-Project Council (CPC).

### TSC meetings

The TSC meets in a Discord conference call or Discord thread. Each year,
the TSC elects a chair to run the meetings.

Any community member can create a GitHub issue asking that the TSC review
something.

The TSC may invite people to take part in a non-voting capacity.

During the meeting, the TSC chair ensures that someone takes minutes. After the
meeting, the TSC chair ensures that someone opens a pull request with the
minutes.

The TSC seeks to resolve as many issues as possible outside meetings using
[the webpack's governance repository issue tracker](https://github.com/webpack/governance/issues).

The process in the issue tracker is:

* A TSC member opens an issue explaining the proposal/issue and @-mentions
  @webpack/tsc.
* The proposal passes if, after 72 hours, there are two or more TSC voting
  member approvals and no TSC voting member opposition.
* If there is an extended impasse, a TSC member may make a motion for a vote.

## Consensus Seeking Process

The TSC follows a
[Consensus Seeking](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making)
decision making model.

When an agenda item has appeared to reach a consensus, the moderator
will ask "Does anyone object?" as a final call for dissent from the
consensus.

If an agenda item cannot reach a consensus, a TSC member can call for
either a closing vote or a vote to table the issue to the next
meeting. The call for a vote must be approved by a majority of the TSC
or else the discussion will continue. Simple majority wins.

----

_This document is an adaption of the [Node.js project Governance Model](https://github.com/nodejs/node/blob/main/GOVERNANCE.md) and the [ESlint project Governance Model](https://github.com/eslint/eslint/blob/main/docs/src/contribute/governance.md)_

[TSC Charter]: https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md
