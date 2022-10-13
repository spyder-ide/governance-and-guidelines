# Spyder Governance Document

The [current official version of this document](https://github.com/spyder-ide/governance-and-guidelines/blob/main/governance.md), along with a list of individuals and institutions in the roles defined in the governance section below, is contained in the [Spyder Governance and Guidelines Repository](https://github.com/spyder-ide/governance-and-guidelines).

It was originally based on the [Pandas Main Governance Document](https://github.com/pandas-dev/pandas-governance/blob/f7352be07872048a07be3d3614ae142e004568df/governance.md) by [Wes McKinney](https://github.com/wesm) and [Tom Augspurger](https://github.com/TomAugspurger), also licensed [CC0-1.0](https://github.com/pandas-dev/pandas-governance/blob/f7352be07872048a07be3d3614ae142e004568df/LICENSE.md), which describes a similar governance model to that in use for Spyder.



## The Project

The Spyder Project (the Project) is an open source software project affiliated with the 501(c)3 NumFOCUS Foundation.
The goal of the Project is to develop graphical applications, libraries and utilities for scientific computing, data exploration/analysis/visualization, and research software development for the Python programming language.
The software developed by the Project (the Project Software) is released under the [MIT](https://opensource.org/licenses/MIT) (or similar) open source license, developed openly and hosted in public GitHub repositories under the [Spyder-IDE GitHub Organization](https://github.com/spyder-ide).
Examples of Project Software include the main [Spyder](https://github.com/spyder-ide/spyder) scientific Python development environment, the [Spyder-Kernels](https://github.com/spyder-ide/spyder-kernels) support package, the [QtPy](https://github.com/spyder-ide/qtpy) Qt abstraction layer, and the [Spyder-Docs](https://github.com/spyder-ide/spyder-docs) documentation.

The Project is developed by a global collective of distributed developers, called Contributors.
Contributors are individuals who have contributed code, documentation, designs or other work to one or more Project repositories.
Anyone can be a Contributor.
Contributors can be affiliated with any legal entity or none.
Contributors participate in the project by submitting, reviewing and discussing GitHub Pull Requests and Issues and participating in open and public Project discussions on GitHub, community calls and elsewhere.
The foundation of Project participation is openness and transparency.
A list of all Contributors can be found on the "Contributors" page of each individual Project repository, such as the [one for the main Spyder repository](https://github.com/spyder-ide/spyder/graphs/contributors).

Contributors with a sustained, formal relationship to the project are added as Organization Members, part of the Spyder-IDE Organization.
They are added to one or more Teams within the Organization, based on their interests, expertise and experience with—as well as the needs of—the Project.

The Project Community consists of all Contributors and Users of the Project.
Contributors work on behalf of and are responsible to the larger Project Community, and should strive to keep the barrier between Contributors and Users as low as possible.

The Project will be formally affiliated with the [501(c)3 NumFOCUS Foundation](https://numfocus.org), which will serve as its fiscal sponsor, may hold project trademarks and other intellectual property, helps manage project donations and acts as a parent legal entity.
Through its affiliation with NumFOCUS, the Project will have the right to receive tax-deductible donations in the United States of America.



## Governance

This section describes the governance and leadership model of the Project.

The foundations of Project governance are:

* Openness and Transparency
* Active Contribution
* Institutional Neutrality

Traditionally, Project leadership has been provided by a Lead Maintainer (Carlos Cordoba, and previously Spyder creator Pierre Raybaut) and a subset of Contributors, called the Spyder Core Developers, whose active and consistent contributions to the Project have been recognized by their being added to the Core Developers GitHub Team, which grants the Write role on the primary Project GitHub repository.
In general, all Project decisions are made through consensus among the Core Developers with input from the rest of the Community.
The Lead Maintainer can, but should rarely need to, make a final decision on a matter when there is not a clear consensus among the Core Developers.

While this informal approach has served the Project well, as the Project grows and faces more legal and financial decisions and interacts with other institutions, there is a need for a more formal governance model.
Moving forward, the Project leadership will formally consist of the Lead Maintainer and Core Developers.
This governance model is intended as the formalization of what the Project is already doing, rather than a change in direction.


### Lead Maintainer

The Project will have a Lead Maintainer, who is the Project's leader.
The Lead Maintainer has the final authority to make decisions for the Project, in the absence of clear consensus among the Core Developers.
Clear consensus is defined as at least two thirds of the Core Developers (counting the Lead Maintainer) being in agreement on a particular decision.
However, it is expected that the Lead Maintainer will only assert their final authority after reasonable efforts to build consensus have not been successful, or if the Core Developers collectively ask the Lead Maintainer to make a decision on a specific matter.
The Lead Maintainer is also a member of the Core Developers, and may delegate authority on a particular decision or set of decisions to any other Core Developer.

The Lead Maintainer may nominate a successor, subject to acceptance by a majority of Core Developers.
If the Lead Maintainer is unable to appoint a successor, the nominated successor is not approved, or the Lead Maintainer is recalled, the Core Developers will choose a successor by two-thirds vote.
If no Lead Maintainer candidate receives two-thirds of the votes of all active Core Developers after three rounds of voting, the Core Developers shall propose the Lead Maintainer candidates to the NumFOCUS board, who will then make the final decision.

In extraordinary circumstances, if the Lead Maintainer has lost the confidence of the Core Developers, a supermajority of two-thirds of all active Core Developers (not including the Lead Maintainer) may vote to recall the Lead Maintainer.
This is intended as a last resort, after exhausting all other reasonable efforts to resolve the situation.
If recalled, the Lead Maintainer would remain a Core Developer, with any further status changes happening as with any other member of that Team.


### Core Developers

The Project's Core Developers will consist of Project Contributors who have produced contributions that are substantial in quality and quantity, and sustained over at least one year.
The overall role of the Core Developers is to ensure, through working with the Lead Maintainer and taking input from the Community, the long-term well-being of the project, both technically and otherwise.
Further, it is expected that because of the quality and quantity of their contributions and their expert knowledge of the Project Software, the Core Developers will provide guidance, both technical and in terms of project direction, to less experienced contributors.

The Core Developers will be members of the "Core Developers" Team in the Spyder-IDE Organization, which is granted the Write role on the primary [`spyder`](https://github.com/spyder-ide/spyder) and [`spyder-kernels`](https://github.com/spyder-ide/spyder-kernels) repositories.
Users must be Core Developers to be granted Write-level access and above on these repositories, as well as Admin-level access on other repositories in the Spyder-IDE organization.
It is the Core Developers that vote on specific, major, high-level project governance issues as specified in this document.
Additionally, the Core Developers have primary responsibility for guiding the code review process and merging pull requests, and for administering and maintaining any key services and infrastructure on which the project relies.

To become eligible for becoming a Core Developer, an individual must be a Project Contributor who has produced contributions that are substantial in quality and quantity, and sustained over at least one year.
Potential Core Developers are nominated and voted upon by the existing Core Developers, after asking if the candidate is interested and willing to serve in that capacity.
A majority of all active Core Developers must vote in favor of adding the new member, unless at least one core developer votes against, in which case at least two thirds of all active Core Developers must vote in favor.
The Core Developers will be initially formed from the set of existing Contributors who are members of the Core Developers Team as of July 2022.

When considering potential new members, the Core Developers will look at candidates with a comprehensive view of their contributions.
This will include but is not limited to code, code review, infrastructure work, participation in communications channels, community help/building, education and outreach, design work, etc.
The Project wants to encourage a diverse array of backgrounds, viewpoints and talents on the Core Developer team, which is why code is not defined as the sole metric on which Core Developers membership will be evaluated.

If a Core Developer falls well below the threshold of activity over a period of one year that would qualify a candidate to be considered for Core Developer membership, they will be considered inactive.
The inactive Core Developer will then be approached by the Lead Maintainer to see if they plan on returning to active participation.
If they respond in the negative, or do not respond within 30 days, they will be removed as a Core Developer after a majority vote by the active Core Developers.
If they plan on returning to active participation soon, they will be given a grace period of six months.
If they do not do so after that time, they will be removed after a majority vote by the active Core Developers.

Upon removal, such Core Developers will remain members of the Spyder-IDE organization, and be removed from any Teams they may be members of and added to the Former Developers Team.
Retired Core Developers members will be also included on the People list, acknowledging the period during which they were active in the Core Developers Team.
All former Core Developers can be considered for membership again at any time in the future, like any other Project Contributor.

The Core Developers reserves the right to eject current Core Developers, if they are deemed to be actively harmful to the project's well-being, and all attempts at communication and conflict resolution have failed.
Such a vote is called by the Lead Maintainer, and requires two thirds of all active Core Developers (counting the Lead Maintainer, but not the Core Developer in question) to vote in favor of removal.
If approved, the Core Developer is immediately removed from the Core Developers Team, and if appropriate, the Spyder-IDE Organization.
After a period of one year, they may be eligible for membership again if nominated, following the same standard as any other Project Contributor.



## Organization

This section concerns the roles and membership within the [Spyder-IDE](https://github.com/spyder-ide) GitHub Organization and its repositories.


### Organization Owners

The Spyder-IDE Organization Owners are entrusted with stewardship of the Spyder-IDE Organization on behalf of the Lead Maintainer, Core Developers, Organization Members, Project Contributors and the Spyder Community.
For the purposes of balancing the risks of "bus factor" with security, there shall be three Owners, no more, no less.
Three shall be the number of Organization Owners, and the Owners of the Organization shall be three.
Four shalt there not be, neither shall there be two, excepting that one be added to amount to three.
Five is right out.
Such that three, being the third number, be reached, they shall comprise the Lead Maintainer, their designated successor, and the Spyder creator, Pierre Raybaut.

To ensure stability for the project, no Organization Owner may add or remove another, except by a vote of two thirds of all active Core Developers, or as provided below:

* If a new Lead Maintainer or designated successor is successfully confirmed by vote, they are added as a new Organization Owner.
* If one of the individuals whose position grants them the role of Organization Owner is recalled or voluntarily retires from their respective position, they are obligated to immediately remove themselves, or be removed, from this role.
* If a vote is called on the removal of an Organization Owner or a recall of a Organization Member whose position grants them this privilege, upon concurrence of two of the three Organization Owners, the Member shall temporarily be removed for the duration of the vote or two weeks, whichever is less, and then restored unless a two thirds majority is reached.
* If an Owner or their account are believed to be physically or mentally compromised, either on their request or with the concurrence of the other two Owners, they may be temporarily removed for a period of up to two weeks and then restored, unless two thirds of the remaining active Core Developers vote for their permanent removal.
* During any period for which there are fewer than three individuals holding the role of Organization Owner, the Governance and Guidelines repository maintainer shall be appointed a temporary, acting Organization Owner for the specific purposes of facilitating the transition, reducing bus factor, maintaining a quorum and mediating any disagreements between the remaining Owners; and will be immediately removed upon confirmation of a new Owner.

Additionally, Organization Owners have by default the "Admin" role on all Spyder-IDE Organization repositories, including `spyder` and `spyder-kernels`.
For security reasons, these should be the only individuals with the "Admin" role on the `spyder` and `spyder-kernels` repositories.


### Organization Members

Organization Members are Contributors who, due to a reasonable and appropriate need (such as having a formal relationship with the Spyder Project, or being considered or mentored for eventual nomination as a Core Developer), are added as Members of the Spyder-IDE Organization.
Such Organization Members (other than Core Developers) are added by the Lead Maintainer, with the advice and consent of the Core Developers.
They may be granted permissions of "Triage" or lower on the `spyder` or `spyder-kernels` repositories, or "Maintain" or lower on any other repository, and be added to any Team with the same permissions.
Otherwise, they retain the same rights and privileges as other Contributors, including the possibility of earning membership in the Core Developers through their sustained contributions to the Project.


### Repository Collaborators

Per-repository Collaborators are Contributors who, thanks to their record of contributions to a specific repository, to further deepen collaboration, or a specific need for their expertise, are given a Role on a particular Spyder-IDE Organization repository.
They can be added at the discretion of the Core Developer maintainers of the other repositories under the Spyder organization (aside from `spyder`/`spyder-kernels`), with the consent of the Spyder Lead Maintainer.
They may be granted any Role up to Write, or Maintain in special circumstances, for the duration of their collaboration.


## Teams

This section concerns the various Teams, comprised of Core Developers and other Organization Members, for the purposes of governance and for coordination and specialization within the Organization.


### NumFOCUS Representatives

The Core Developers will maintain a narrowly focused team to manage its interactions with NumFOCUS.
This group, the NumFOCUS Representatives, will comprise at least five Core Developers, and be responsible for managing project funding obtained through NumFOCUS.
It is expected that these funds will be spent in a manner that is consistent with the non-profit mission of NumFOCUS and the direction of the Project as determined by the Lead Maintainer and Core Developers.
The Spyder Lead Maintainer, their designated successor and the Governance and Guidelines repository maintainer will be *ex officio* NumFOCUS Representatives, with the remaining Representatives nominated by the Lead Maintainer with the advice and consent of the Core Developers.


### Code of Conduct Committee

This body, composed of at least three Core Developers, will hear, investigate, deliberate and enforce potential violations of the Spyder [Code of Conduct](https://github.com/spyder-ide/governance-and-guidelines/blob/main/code_of_conduct.md).
Its nominal members are, *ex officio*, the Spyder Lead Maintainer, their designated successor, and the Governance and Guidelines repository maintainer.
Additional members may be nominated by the Lead Maintainer and confirmed by a majority of all active Core Developers (not counting the member in question).


### Other Teams

The Lead Maintainer, consulting with the Core Developers, can create other Teams that provide leadership, guidance and coordination for specific aspects of the project.
While Team Maintainers/Leads must be Core Developers, Team members may be any Member of the Organization.
Example Teams may include, but are not limited to, Documentation, Website, and User Experience.
Additionally, the Junior Developers Team is reserved for Organization Members who are not Core Developers, and generally intended for those that are not otherwise serving in a highly specialized role (such as a UX designer, technical writer, and the like).



## Transparency

Unless specifically required, all Core Developer and Organization discussions and activities should be public and done in collaboration and discussion with the Project Contributors and Community in general.
The Core Developers will have a private Discord channel that will be used sparingly when a specific matter requires privacy.
When private communications and decisions are needed, the Core Developers will do its best to summarize those to the rest of the Community after eliding personal/private/sensitive information that should not be posted to the public internet.



## Institutional Partners and funding

The Lead Maintainer and Core Developers are the primary leadership for the project.
No outside institution, individual or legal entity has the ability to own, control, usurp or influence the project other than by participating in the Project as Contributors and Core Developers.
However, because institutions are the primary funding mechanism for the project, it is important to formally acknowledge institutional participation in the project.
These are Institutional Partners.

An Institutional Contributor is any individual Project Contributor who contributes to the project as part of their official duties at an Institutional Partner, or is otherwise funded to do so by the Institution Partner.
Likewise, an Institutional Core Developer is any Core Developer who contributes to the project as part of their official duties at an Institutional Partner, or is otherwise funded to do so by the Institution Partner.

With these definitions, an Institutional Partner is any recognized legal entity in the United States or elsewhere that employs or funds at least one Institutional Contributor or Institutional Core Developers Member.
Institutional Partners can be for-profit or non-profit entities.
Merely using Spyder Software or Services in an institutional context does not allow an entity to become an Institutional Partner.
Once an institution becomes eligible for Institutional Partnership, the Core Developers must nominate and approve the Partnership.

An Institutional Partner is free to pursue funding for their work on the Project through any legal means.
This could involve a non-profit organization raising money from private foundations and donors or a for-profit company building proprietary products and services that leverage Project Software and Services.
Funding acquired by Institutional Partners to work on the Project is called Institutional Funding.
However, no funding obtained by an Institutional Partner can override the Project Lead Maintainer and Core Developers.
If a Partner has funding to perform Spyder-related work and the Core Developers decide to not pursue that work themselves, the Partner is free to pursue it on their own.
However, in this situation, that part of the Partner's work will not be under the Spyder umbrella.

To acknowledge institutional contributions, there are several levels of Institutional Partners, with associated benefits:


**Tier 1**

An institution funding at least one Core Developer.

* Acknowledged on the Spyder website, Readme, release announcements and People list, in talks and on T-shirts.
* Ability to acknowledge their own funding sources on the Spyder website, in talks and T-shirts.
* Ability to influence the project through the participation of their funded Core Developer(s).


**Tier 2**

An institution funding at least one Spyder Organization Member or repository Collaborator.

* Acknowledged in the Spyder (org member) or individual project (repo collaborator) Readme, project release announcements (if collaborator) and People list.
* Ability to influence the project through the participation of their funded Organization Member(s)/Collaborator(s).


**Tier 3**

An institution funding at least one Spyder Contributor.

* Individual contributions acknowledged in the Releases page, Changelog, commit messages and Pull Requests.
* Ability to influence the project through the participation of their Contributor.



## Breach

Non-conformance with the terms of the governance documents shall be reported to the Core Developers, either through public (issue on the Governance and Guidelines repository) or private (Core Developer Discord) channels as deemed appropriate.
All members of the Community may report such issues, and each will be suitably investigated.
The Governance and Guidelines repository maintainer is the nominal point of contact, and has the particular responsibility to ensure any issues are investigated, both independently and those brought to their attention, and report them to the Lead Maintainer and Core Developers.
Any necessary corrective action will be discussed and collectively decided upon by the Core Developers, and implemented by the Lead Maintainer.



## Changing the governance documents

All changes to the governance documents must be submitted via GitHub Pull Request to the Project's [Governance and Guidelines GitHub repository](https://github.com/spyder-ide/governance-and-guidelines).
All Core Developers shall, and all Organization Member should, "Watch" this repository to ensure they are informed of and have the opportunity to comment such Pull Requests.
The pull request is then refined in response to public comment and review, with the goal being consensus in the community.
All Pull Requests to this repository must be reviewed and approved by, at minimum, the Spyder Lead Maintainer and the Governance and Guidelines repository maintainer (or another Core Developer, if the author is one of the aforementioned).

Pull requests that modify the Readme, repository license, this document or any of the other governance documents listed there, or add a new such document, must remain open for at least a full week (7 full days) and evaluated for whether they would substantively change the contents therein.
If the Spyder Lead Maintainer, governance repository maintainer, or any Core Developer believes that one does, then once all immediate review comments are resolved, it is announced to the Core Developers.

For such Pull Requests to be merged, at least two thirds of all active Core Developers (counting the Pull Request author, if a Core Developer) must approve it before it can be merged.
Alternatively, if a greater than one-half majority of Core Developers vote not to merge the Pull Request, it is closed without merging.
The Pull Request author should refrain from making changes to such Pull Requests during this time, as such will dismiss the approving reviews required for it to be merged, and all Core Developers will need to review again.
