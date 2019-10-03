# Contributing to {put-your-project-name}

## Welcome contributors to the project 
Admit that you are eager for contributions and so happy they found themselves here.  

## Table of Contents 
If your CONTRIBUTING.md file is long, you might consider including a table of contents with links to different headings in your document. In GitHub, each heading is given a URL by default, so you can link to that URL in the appropriate section of the Table of Contents for each heading. Do this in Markdown by wrapping the heading in [ ] and following with a parenthetical that includes the URL or header after # like [Reporting Bugs](#How_to_file_a_bug).  
## Short Links to Important Resources
   **docs**: handbook / roadmap (you'll learn more about this in the roadmapping session).  
   **bugs**: issue tracker / bug report tool.  
   **comms**: forum link, developer list, IRC/email.  
## Testing 
How to test the project, where the tests are located in your directories.  
* What plugins integrated in the Continous Integration pipeline are in place.  
* Code Coverage Quality Gate and the percent of unit tests neeed for   
* Provide local instructions to run code formatters, linters, test coverage suites with coverage reports before Pull Request.
## Environment details
How to set up the development environment. This might exist in the README.md/INSTALL.md depending on the project. If so include a link. An important part is the local build of the project. Documentation should be clear on how to build the project locally and what are the project dependencies to have a build run successfully.   
## Design decisions
Provide a place (Distribution Lists, Slack channel, Github discussions) where you keep all the design decisions made in a transparent way. If a design decision is not clear or not enough documented, provide a hint on how to start a discussion around it.  

Is important to point out what is the way of starting a conversation around a change that can be submited by a contributor and that change has an impact on Design of the application. What is needed for a contributor to figure out if is on track and the change/adition won't conflict at a latter stage when sending a Pull Request.  
There are multiple posibilities here:  
* Start the conversation at the whiteboard.   
* Have a call  
* A more formal process by opening a GitHub issue or starting a new design review thread in the tool agreed for the project.

Provide clear documentation in these area to avoid rework and increase predictibility(As a maintainer you will know that you will have to review an important change and include this in the Software Development Lifecycle).  

## How to submit changes 
Pull Request protocol, Code Review process. You might also include what response they'll get back from the team on submission, or any caveats about the speed of response. Providing a timeframe for a response in general improves collaboration. This repository provides a template for [Pull Requests](https://github.com/adobe/open-development-template/blob/master/.github/PULLREQUESTTemplate.md) that can be [configured as default template for your repository in Github](https://help.github.com/articles/creating-a-pull-request-template-for-your-repository/) and customised according to your needs. Segregation based on type can be configured to initiate a pull request that includes performance improvements, bug fixing, feature modification or documentation change.
## How to file a bug 
Bugs are problems in code, in the functionality of an application or in its UI design; you can submit them through "bug trackers" and most projects invite you to do so, so that they may "debug" with more efficiency and the input of a contributor. The process of file a bug  is mainly break into two steps: before submitting and submit a Bug Report. Guidance can be found below.

### Before Submitting a Bug Report
1. Check the **debugging guide** for the project - E.g., how to activate verbose mode. Provide link to debugging guide that is specific to your project.  
2. Check the **FAQs** for a list of common questions and problems. Provide link to FAQs 
3. Check if the issue was already reported and the status of if. Provide search examples and where issues are raised (GitHub issues, JIRA tickets).
4. Determine which component/repository the issue should be reported in.   

### How do I submit a (good) Bug Report. 
After deciding which component the bug relates to and where to raise the bug, next step will be to use a template, [ISSUE_TEMPLATE.md](https://github.com/adobe/open-development-template/blob/master/.github/ISSUE_TEMPLATE.md), that guides the reporter to help identifying faster where the problem is.


## How to request an "enhancement" 
Enhancements are features that you might like to suggest to a project, but aren't necessarily bugs/problems with the existing code; there is a "label" for enhancements in Github's Issues (where you report bugs), so you can tag issues as "enhancement," and thereby allow contributors to prioritise issues/bugs reported to the project. If you are using a different tool to capture enhancements, for example JIRA, please provide documentation on label used to do that.
## Style Guide/Coding conventions 
The aim of this section is to provide guidance on coding styles for different languages that are part of the project (You can use a default one or inherit the default one and decorate with project specifics). Besides source code style guide, style guides for writing Git commit messages, pull requests, documentation must be provided.  
* Git Commit Messages Style guide.  
* Java Style guide.  
* Python Style guide.  
* Documentation Style guide.  

If you are adopting a default style guide for example [Google Style Guide](https://github.com/google/styleguide) make it clear from the start and decorate only with the deltas if any.

## Code of Conduct 
You can make this part of CONTRIBUTING.md to set the tone for contributions. You can also make this a separate Markdown file and link to it in CONTRIBUTING.md. You can also extend this section to link to your LICENSE.md or any details for project consumers on permissions and license details you have established for building on your work.
## Recognition model 
Provide a pre-emptive "thank you" for contributing and list any recognition contributors might receive for participating in your project.
## Who is involved? 
It might be nice to have a more personal/friendly individual to attract to a project and reach out to with questions. You might list the core contributors and their preferred methods of contact here, or link to a **humans.txt** file in your root directory (same place as your CONTRIBUTING.md file), which lets people know who they are working. Here is an example of a [humans.txt](http://humanstxt.org/humans.txt) file.
## Where can I ask for help? 
A nice extension to the previous section, with links to good comms channels for anyone with questions.



