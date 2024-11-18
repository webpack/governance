# webpack TSC Charter

## Section 0. Guiding Principle

The webpack project is part of the OpenJS Foundation. The project operates transparently, openly, collaboratively, 
and ethically. Project proposals, timelines, and status must not merely be open, but also easily visible to outsiders.

## Section 1. Scope

The webpack project is a highly flexible and efficient module bundler for modern JavaScript applications. Its primary 
purpose is to transform and bundle various modules (JavaScript, CSS, images, etc.) into a format suitable for web 
applications. Webpack focuses on enhancing the developer experience, providing optimizations for production environments, 
and enabling configurations to support a wide range of use cases and edge cases for specific projects.

With this, webpack not only simplifies the process of managing application dependencies, but it also offers tools to 
optimize performance, maintainability, and scalability. The webpack community contributes solutions to common challenges 
in modern web development, helping developers streamline their workflows and build robust applications.

### 1.1: In-scope

- Bundling JavaScript files and their dependencies into a single output (or multiple outputs) for browser environments
- Handling of asset files such as CSS, images, fonts, and other static resources
- Optimization of assets for production, including minification, compression, and tree shaking (removal of unused code)
- Enabling hot module replacement (HMR) for faster development feedback loops
- Configuration and extensibility through plugins and loaders
- Support for code splitting and lazy loading to enhance performance
- Integrating with modern JavaScript frameworks (e.g., React, Vue, Angular)
- Providing detailed build reports and debugging tools for development and production
- Supporting multiple output formats (e.g., AMD, CommonJS, ES Modules) for compatibility with various environments
- Community-driven tools and best practices provided through 
  [plugins](https://webpack.js.org/plugins/) and [guides](https://webpack.js.org/guides/)
- Technical help and discussions via community platforms such as 
  [GitHub Discussions](https://github.com/webpack/webpack/discussions)

In addition to the main repository, `webpack` (bundler), the organization maintains and manages several other core 
projects that are integral to the ecosystem such as `webpack-dev-server`, `webpack-cli`,  and `webpack-contrib` projects.

These repositories, along with others housed within the `github.com/webpack` and `github.com/webpack-contrib are owned by the webpack project.`.

### 1.2: Out-of-Scope

- Testing frameworks (e.g., unit, integration, or end-to-end testing tools).
- APIs and tools that uses webpack in any way and are not in the webpack organization.
- Server-side rendering directly (although it can integrate with SSR frameworks).
- `webpack`-related frameworks and libraries that operate in their own capacity.

## Section 2. Relationship with OpenJS Foundation CPC.

Most large, complex open source communities have both a business and a technical governance model. Technical leadership 
for the projects within the OpenJS Foundation is delegated to the projects through their project charters by the OpenJS 
Cross Project Council (CPC). In the case of the webpack project, it is delegated to the webpack Technical Steering 
Committee ("TSC"). OpenJS Foundation's business leadership is the Board of Directors (the "Board").

This charter can only be amended with the approval of the CPC.

## Section 3. Establishment of the TSC

TSC members can be either _regular_ members or _voting_ members. Regular members can attend meetings and participate in 
TSC discussions, but do not vote. Voting members can do everything regular members can do, and also have the ability to 
cast votes when consensus is not reached on an issue.

TSC memberships are not time-limited. There is no maximum size of the TSC. The TSC must have at least four voting 
members.

The TSC may add additional voting members to the TSC by a standard TSC motion. A TSC member can be removed from the TSC by voluntary 
resignation or by a standard TSC motion. A standard TSC motion can be used to change a regular TSC member to a voting 
TSC member, or to change a voting TSC member to a regular TSC member.

No more than one-fourth of the TSC voting members may be affiliated with the same employer. If a change in TSC voting 
membership or a change of employment by a TSC voting member creates a situation where more than one-fourth of the TSC 
voting membership shares an employer, then the situation must be immediately remedied by the removal of voting member 
status from one or more TSC voting members affiliated with the over-represented employer(s).

The TSC shall meet regularly using tools that enable participation by the community (e.g. weekly on a Google Hangout On 
Air, or through any other appropriate means selected by the TSC). The meeting shall be directed by the TSC Chairperson. 
Responsibility for directing individual meetings may be delegated by the TSC Chairperson to any other TSC voting member. 
Minutes or an appropriate recording shall be taken and made available to the community through accessible public 
postings.

TSC voting members are expected to regularly participate in TSC activities.

A TSC voting member is automatically converted to a TSC regular member if they do not participate in three consecutive 
TSC votes.

## Section 4. Roles & Responsibilities of the TSC

Subject to such policies as may be set by the CPC, the TSC voting members are responsible for all technical development 
within the webpack project, including:

* Setting release dates.
* Release quality standards.
* Technical direction.
* Project governance and process.
* GitHub repository hosting.
* Conduct guidelines.
* Maintaining the list of additional Collaborators.
* Development process and any coding standards.
* Mediating technical conflicts between Collaborators or `webpack` projects.

The TSC voting members will define webpack project's release vehicles.

### Section 4.1. webpack Project Operations

The TSC voting members will establish and maintain a development process for the webpack project. The development 
process will establish guidelines for how the developers and community will operate. It will, for example, establish 
appropriate timelines for TSC review (e.g. agenda items must be published at least a certain number of hours in advance 
of a TSC meeting).

The TSC and entire technical community will follow any processes as may be specified by the OpenJS Foundation Board 
relating to the intake and license compliance review of contributions, including the OpenJS Foundation IP Policy.

### Section 4.2. Decision-making, Voting, and/or Elections

#### Section 4.2.1. Elections

Leadership roles in the webpack project will be peer elected representatives of the community.

For election of persons (such as the TSC Chairperson), a multiple-candidate method should be used, such as:

* [Condorcet][] or
* [Single Transferable Vote][]

Multiple-candidate methods may be reduced to simple election by plurality when there are only two candidates for one 
position to be filled. No election is required if there is only one candidate and no objections to the candidate's 
election. Elections shall be done within the projects by the Collaborators active in the project.

The TSC voting members will elect from amongst voting TSC members a TSC Chairperson to work on building an agenda for 
TSC meetings and a OpenJS Cross Project Council (CPC) voting member to represent the TSC in the OpenJS Foundation for a 
term of one year. The Chair and voting CPC member may be (but are not required to be) the same person. The TSC shall 
hold annual elections to select a TSC Chairperson and voting CPC member; there are no limits on the number of terms a 
TSC Chairperson or voting CPC member may serve.

#### Section 4.2.2. Voting

For internal project decisions, Collaborators shall operate under Lazy Consensus. The TSC voting members shall establish 
appropriate guidelines for implementing Lazy Consensus (e.g. expected notification and review time periods) within the 
development process.

The TSC voting members follow a [Consensus Seeking][] decision making model. When an agenda item has appeared to reach a 
consensus the moderator will ask "Does anyone object?" as a final call for dissent from the consensus.

For all votes, a simple majority of all TSC voting members for, or against, the issue wins. A TSC voting member may 
choose to participate in any vote through abstention.

All changes to this charter must be approved by the CPC.

#### Section 4.3. Other Project Roles

The webpack git repository is maintained by the TSC and additional Collaborators who are added by the TSC voting members 
on an ongoing basis.

Individuals making significant and valuable contributions are made Collaborators and given commit-access to the project.
These individuals are identified by the TSC and their addition as Collaborators is discussed during a TSC meeting. 
Modifications of the contents of the git repository are made on a collaborative basis as defined in the development 
process.

Collaborators may opt to elevate significant or controversial modifications, or modifications that have not found 
consensus to the TSC for discussion. The TSC voting members 
should serve as the final arbiter where required. The TSC will maintain and publish a list of current Collaborators, as 
well as a development process guide for Collaborators and Contributors looking to participate in the development effort.

## Section 5. Definitions

* **Contributors**: contribute code or other artifacts, but do not have the right to commit to the code base. 
  Contributors work with the project's Collaborators to have code committed to the code base. A Contributor may be 
  promoted to a Collaborator by the TSC. Contributors should rarely be blocked by the TSC and never by the CPC or 
  OpenJS Foundation Board.

* **Project**: a technical collaboration effort, e.g. a subsystem, that is organized through the project creation 
  process and approved by the TSC.

----

This work is a derivative of the [Node.js Project TSC Charter](https://github.com/nodejs/node/blob/main/TSC_CHARTER.md).

[condorcet]: https://en.wikipedia.org/wiki/Condorcet_method
[consensus seeking]: https://en.wikipedia.org/wiki/Consensus-seeking_decision-making
[single transferable vote]: https://en.wikipedia.org/wiki/Single_transferable_vote