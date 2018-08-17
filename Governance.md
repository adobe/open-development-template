# Governance

Governance is the process of decision making and defines the social rules of interaction.

1. [Why Document It?](#why-document-it)
2. [How To Document It?](#how-to-document-it)
3. [Example Governance Models](#example-governance-models)
    1. [Hierarchical](#hierarchical)
    2. [Majority Rule](#majority-rule)
    3. [Consensus](#consensus)
        1. [Benevolent Dictatorship](#benevolent-dictatorship)
        2. [Meritocracy](#meritocracy)
4. [References](#references)

# Why Document It?

We need governance to [keep order and prevent conflict][os-governance-models-why].
Conflict may arise for a variety of reasons, [three of which][os-governance-models-conflict]
are identified here:

1. **Competition** - for gain. In business we are constantly searching for a
   competitive advantage. This may manifest itself in a software project through
   unfair usage. We can mitigate this through [**thoughtful licensing**](Licensing.md).
2. **Diffidence** - for safety. Be it because of a lack of self-confidence or due to
   a [hostile working environment][five-keys-successful-teams], project contributors
   might keep their ideas, concerns, or arguments to themselves and not share them
   with the team. Long term this may lead to conflict. We can mitigate this by
   **employing a decision making process and rules of interaction that are egalitarian**.
3. **Glory** - for reputation. Everyone yearns to be recognized for the work they
   do but this can lead to conflict if individuals chase glory at the cost of
   team member relationships. We can mitigate this by **ensuring peer recognition
   is formalized in our rules of interaction**.

By making a project's decision making process and rules of interaction explicit
and egalitarian, we [encourage involvement, ensure project
continuity][software-management] as [members change][social-infrastructure] and
[high performance by creating a psychologically safe working environment that is
structured and clear][five-keys-successful-teams] (thus reducing diffidence). By
embedding recognition in our social rules of interaction (in, for example, our
[team/project processes](Process.md)) we can help dampen glory-seeking behaviours.

# How To Document It?

Be it through a project or team website, a separate document revisioned along
with code, or a wiki page, all of these are great ways of formalizing a
governance model. You can think of this document as your [project's
constitution][consensus-democracy] to borrow a concept from democractic forms
of government.

It's important that this information be accessible and
discoverable so ensuring it is linked-to from a project's `README.md` or website
is key.

Some key aspects of governance that one should cover are:

- **Communication**. What is the primary form of communication? Which medium
    should be considered the source of truth for discussions?
- **Roles and Responsibilities**. What work are we responsible for? How do we
    divide the work amongst ourselves? Furthermore, how do people attain and
    hand off the roles and responsibilities?
- **Decision Making**. Ensure to make explicit the different kinds of decisions
    the team needs to make about the project, whether these require different kinds
    of approvals, and the process through which approvals are made. Making clear
    when the team votes on issues vs. seeks consensus (and whether the consensus
    is [lazy][lazy-consensus] or not) is helpful here.

Don't worry about being complete or exact. Start somewhere, and work with your
team to expand it naturally. [A good way to start is to base the document on questions
newcomers most often ask][consensus-democracy].

# Example Governance Models

A governance model is a social decision making framework. Many such frameworks
exist. The following are a few common ones, their pros and cons, and examples of
how to enshrine them in your project.

## Hierarchical

Hierarchical governance is based on a command-and-control tree-like structure
that enables decision making through deferment and delegation up and down the
hierarchy. Ultimately, the leader at the top of the hierarchy may override any
decision made lower in the hierarchy. The leader may also delegate decisions
down the hierarchy. This is a common governance and organizational structure for
most corporations.

Adobe uses a **decision making framework** called [DACI][daci], which stands for
Driver, Approver, Contributor and Informed. This framework also clearly states
the **roles and responsibilities**.

|Pros|Cons|
|---|---|
|Fast|Encourages competition and pandering|
|Clear responsibility and accountability|Not egalitarian|
|Explicit structure|Many views unheard|
||Lack of understanding or acceptance of decision|
||Little commitment to carry out decisions|
||[Slow to change][heirarchy-network]|

### Hierarchical Documentation Examples

- An organizational chart can clarify the overall structure and delegation patterns
    that exist in the team.
    - Along with an org chart, it is helpful to make explicit whom is
        responsible for what, i.e. the **roles and responsibilities**.
- Atlassian offers a [DACI playbook][daci-playbook] that details how to go about
    formalizing a DACI hierarchical structure. Confluence has a [DACI
    Template][daci-template] you can use (also available in [pdf][daci-pdf]).

## Majority Rule

For those living in a democractic country this governance model should feel
very familiar. Differences that cannot be resolved by seeking consensus are
simply put to a vote.

|Pros|Cons|
|---|---|
|Familiar|There are always winners and losers and losers tend to leave|
|Works with any size group|Competition and attacks between factions|
|Fast|Political|
||Losers uncommitted|

### Majority Rule Documentation Examples

- Ensure your project and team communication channels are documented, and be
    sure to highlight and make clear the particular rules around voting, such
    as:
    - How voting is initiated
    - How much time must pass before voting closes
    - The majority rule specifics (e.g. simple majority or 2/3 majority)
    - The [Apache Software Foundation uses voting][apache-voting] for specific
        issues.

## Consensus

[Consensus means an agreement that everyone is willing to live
with][consensus-democracy]. A common way this works is that seeking consensus is
what is done most of the time, but [we can always fall
back][consensus-democracy] to [voting](#majority-rule) if consensus cannot be reached.

|Pros|Cons|
|---|---|
|Solutions are collaborative|Slow|
|Conflict is obvious|Frustrating|
|Minority opinions are valued|Requires good listening|
|Promotes solidarity; everyone is a winner|Requires cooperation|
|Minimizes domination|Veto power is absolute|
|Broad acceptance and commitment of decisions||

Two common forms of consensus decision making models are described below.

### Benevolent Dictatorship

A single leader figure whose goal is facilitation between those involved. Questions
of access, permissions or process are completely up to the dictator. The community
is free to fork i.e. "if you don’t like it, you can (take the code and) leave!"

|Pros|Cons|
|---|---|
|Simple|As neutral or egalitarian as the dictator|
|Efficient|Single point of failure|
||[Being a benevolent dictator is hard][good-bd] (requires diplomacy and strong social and technical skills)|

To **make decisions**, the benevolent dictator recognizes others (leaders), listens
to leaders, drives consensus between leaders and breaks deadlocks.

The dictator assigns **roles, responsibilities and delegates** work between them
and their leaders. It is common for the dictator to give autonomy to smaller provinces
(modules) and appoint governors (maintainers / code "owners").

#### Benevolent Dictatorship Documentation Examples

- The [Benevolent Dictatorship Example Governance Model][bd-example] is based on
    the success of the [Linux Kernel project][linux-kernel] and its dictator, [Linus
    Torvalds][linus].

### Meritocracy

[Merit earns authority, and (in theory) anyone can earn merit][meritocracy]. Facilitating
contributions earns merit. A meritocracy of one is a [benevolent
dictatorship](#benevolent-dictatorship).

|Pros|Cons|
|---|---|
|Flat (less politics)|Merit is subjective|
|Efficient|Can devolve into oligarchy|

**Decision making** is leaderless and is done by action ("send a patch"). Actions
are reversible ("that last change really broke stuff, let's revert"). [Lazy consensus
is still consensus][lazy-consensus]. It generally includes a change review process;
[commit-then-review][ctr] is a form of [lazy consensus][lazy-consensus] and tends
to be faster than the alternative of the more-stringent [review-then-commit][rtc].

There are no defined **leaders** or **roles** - everyone (with merit) commits,
everyone is responsible for everything! Over time, projects and teams may develop
roles and responsibilities organically.

#### Meritocracy Documentation Examples

- The [Apache Software Foundation's How It Works][asf-how-it-works] document is
    the de-facto example. It is worth highlighting its sections on
    [structure](http://www.apache.org/foundation/how-it-works.html#structure),
    [roles](http://www.apache.org/foundation/how-it-works.html#roles),
    [communication](http://www.apache.org/foundation/how-it-works.html#communication),
    and [decision
    making](http://www.apache.org/foundation/how-it-works.html#decision-making).
    - The [Apache Forrest Guidelines][forrest-guidelines] are a good
        project-specific example implementation of the Apache Software
        Foundation's more abstract document. Notable sections include [Roles and
        responsibilities](http://forrest.apache.org/guidelines.html#roles), the
        various forms of [decision
        making](http://forrest.apache.org/guidelines.html#decision) the project
        employs and [communication
        channels](http://forrest.apache.org/guidelines.html#communication) used.
- The [Meritocracy Example Governance Model][meritocracy-example] goes into
    further detail as to what such a document should include.
- The Jenkins project has a [Project Governance Document][jenkins-governance].

# References

1. [Open Source Governance Models][os-governance-models]
2. [The five keys to a successful Google team][five-keys-successful-teams]
3. [Lazy Consensus][lazy-consensus] by the Apache OpenOffice Team
4. [Writing and using a software management plan][software-management] by the
   Software Sustainability Institute
5. [Meritocracy][meritocracy] by the Apache Software Foundation
6. [Social Infrastructure of Successful Software
   Projects][social-infrastructure]
7. [Writing Social and Political Infrastructure Down][writing-it-all-down]
8. [Consensus-Based Democracy][consensus-democracy]
9. [Successful Decision Making with DACI][daci] from Inside Adobe
10. [Heirarchy and Network: Two Structures, One Organization][heirarchy-network]

[os-governance-models]: https://www.slideshare.net/outercurve/2013-0508-governance-models
[os-governance-models-why]: https://www.slideshare.net/outercurve/2013-0508-governance-models/10
[os-governance-models-conflict]: https://www.slideshare.net/outercurve/2013-0508-governance-models/8
[five-keys-successful-teams]: https://rework.withgoogle.com/blog/five-keys-to-a-successful-google-team
[social-infrastructure]: https://producingoss.com/html-chunk/social-infrastructure.html
[good-bd]: https://producingoss.com/html-chunk/benevolent-dictator.html
[consensus-democracy]: https://producingoss.com/html-chunk/consensus-democracy.html
[writing-it-all-down]: https://producingoss.com/html-chunk/written-rules.html
[lazy-consensus]: https://openoffice.apache.org/docs/governance/lazyConsensus.html
[ctr]: http://www.apache.org/foundation/glossary.html#CommitThenReview
[rtc]: http://www.apache.org/foundation/glossary.html#ReviewThenCommit
[apache-voting]: http://apache.org/foundation/voting.html
[software-management]: https://www.software.ac.uk/resources/guides/software-management-plans
[meritocracy]: http://www.apache.org/foundation/how-it-works.html#meritocracy
[meritocracy-example]: http://oss-watch.ac.uk/resources/meritocraticgovernancemodel
[forrest-guidelines]: http://forrest.apache.org/guidelines.html
[asf-how-it-works]: http://www.apache.org/foundation/how-it-works.html
[bd-example]: http://oss-watch.ac.uk/resources/benevolentdictatorgovernancemodel
[linux-kernel]: http://www.kernel.org
[linus]: http://en.wikipedia.org/wiki/Linus_Torvalds
[daci]: https://inside.corp.adobe.com/content/dam/learning-and-development/documents/career/Successful-Decision-Making.pdf
[daci-playbook]: https://www.atlassian.com/team-playbook/plays/daci
[daci-template]: https://marketplace.atlassian.com/plugins/atlassian-playbook-daci-decision/cloud/overview
[daci-pdf]: https://www.atlassian.com/dam/jcr:f6b56375-3d78-496a-857e-ca47e89816ce/DACI-Decision-template.pdf
[heirarchy-network]: https://hbr.org/2011/05/two-structures-one-organizatio
[jenkins-governance]: https://jenkins.io/project/governance
