# Process

1. [Why Document It?](#why-document-it)
    1. [Continuous Improvement](#continuous-improvement)
    2. [Faster Onboarding](#faster-onboarding)
    3. [Exert Less Energy](#exert-less-energy)
2. [What To Document?](#what-to-document)
3. [How To Document It?](#how-to-document-it)
4. [Example Process Documentation](#example-process-documentation)
5. [References](#references)

# Why Document It?

## Continuous Improvement

[Documentation begets improvement][document-agency]. Once you write down a process,
you'll quickly see if/where it needs work and what needs to be in place to help
your team be more effective and efficient.

## Faster Onboarding

By making explicit the social rituals, activities, and resources that
collectively comprise how the team and project get work done, we can [onboard
teammates quickly and efficiently so they can start getting work done right
away][better-docs]. This also lowers the barrier to entry to involve oneself in
the project.

## Exert Less Energy

While documenting something does require up-front time and effort, on a long enough
timeline our team [exerts less mental energy][better-docs] when common questions
are answered via documentation.

# What To Document?

The core question to answer is "how do we do work?" There are usually several
aspects to this question that can be answered, but it is worth thinking about
what are the _most_ valuable answers. Start small. A good rule of thumb is document
the questions that newcomers typically ask often. [Slow is okay. Steadily is
imperative][document-agency]. The environment changes and thus the process(es) need
to change, and your team can't approach this with a one-and-done mentality. Pay
extra attention to questions and feedback brought up by "outsiders" - having
less context is helpful when identifying barriers to entry and involvement, and
the whole point in documenting our processes is to make it easy for others to
get involved.

There are certain more definitive aspects of a software project that absolutely
should be documented:

- Where is the issue tracker?
- How does one run the tests? Is there continuous integration or deployment?
- What is the branching and merging (revision control) strategies and
    conventions employed in the project?
- Are there coding conventions? These are worth calling out, or even better,
    worth automating as part of your tests.

Consider documenting the following aspects of your project and team's workflow:

- Does the team meet regularly (like dailies or biweeklies)? Are there rules around
    these meetings (is it based on Scrum or Agile)?
- Are code reviews done?
- How often are releases made? Is there a regular cadence? Is there a specific
    release process?
- As was brought up in [Governance](Governance.md), how does the team
    communicate? Using what channels? If multiple channels are used, what is the
    definitive source of truth for conversations?

# How To Document It?

Process documentation of all shapes and sizes exist. Larger projects tend to
have enshrined more rules, but some projects try to keep it as light as
possible. Larger projects tend to have dedicated web pages or documents, whereas
smaller ones might describe their process directly in their project `README.md`
or, if it is a bit more involved, in their `CONTRIBUTING.md`.

# Example Process Documentation

1. Adobe's Open Source Office provides a [starter repo with templates for many
   relevant documents][starter-repo], such as `CONTRIBUTING.md` and issue and
   pull request templates (relevant for GitHub).
2. [Adobe's Spectrum Engineering Team has a Developer Doc][spectrum-docs]
   covering many of these points.
3. The bottom part of [Jenkins' Project Governance document][jenkins-governance]
   has a "How we develop code" section.
4. [Thoughtbot's Playbook][thoughtbot-playbook] is a fantastic example. It
   starts with a light overview but goes very deep into each area.
5. [GitLab's Runbooks][gitlab-runbooks] are a great example of process
   documentation - not for running a project, but for responding to an outage.
   As part of every outage retrospective, those involved reflect on what was
   helpful and what was lacking in the Runbook, and that feedback in turn is
   used to [continuously improve](#continuous-improvement) the runbooks.

# References

1. [How to Document Processes to Scale Your Agency Faster][document-agency]
2. [Building Better Documentation][better-docs]

[document-agency]: https://blog.hubspot.com/agency/document-agency-processes
[better-docs]: https://www.atlassian.com/software/confluence/documentation
[starter-repo]: https://git.corp.adobe.com/OpenSourceAdvisoryBoard/starter-repo
[spectrum-docs]: https://wiki.corp.adobe.com/display/AdobeDesign/Developer+Docs
[jenkins-governance]: https://jenkins.io/project/governance
[thoughtbot-playbook]: https://thoughtbot.com/playbook
[gitlab-runbooks]: https://gitlab.com/gitlab-com/runbooks
