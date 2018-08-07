# Introduction to GitHub for non-coders 

Blockchain software is almost always open source, many projects follow
principles of [commons based peer
production](https://en.wikipedia.org/wiki/Commons-based_peer_production). 

GitHub is often where the primary commons for a blockchain project can be found,
it is a platform where work on the software is coordinated, where the code is
stored, shared, discussed and edited.

In some ways, participation in the production process is permissionless. The
code itself is open, anyone can copy it, make some changes, and offer those
changes back to the community. The type of offerings a community is likely to
accept, and the method of making those decisions, varies between projects.

GitHub presents very few barriers to contributing to projects beyond signing up
for a user account. Some projects welcome certain kinds of contribution from
non-coders through GitHub.

This post gives a basic introduction to GitHub and outlines a few examples of
ways to contribute to Decred, a cryptocurrency project, on GitHub.

This post is itself available directly from GitHub, and I would be happy to
consider pull requests that improve it.

### git and GitHub

[git](https://en.wikipedia.org/wiki/Git) is a version control system for
coordinating and sharing work on computer files. People using git to work on a
project keep local copies of the code and push changes to centralized
repositories to share them. [GitHub](http://github.com) provides hosting for
these repositories and a layer of extra features like Issues and Pull Requests. 

## GitHub

GitHub’s [own tutorials](https://guides.github.com/activities/hello-world/) are
quite good, if you want to understand it properly I suggest reading or working
through them. 

**Repositories** (or repos) are collections of documents (usually code files).
**Commits** are sets of edits to those files. The owner of a repository decides
who has permission to push commits directly to the files, but it is trivially
easy to create a **Fork** (copy) of GitHub repositories, which you then have
full control over.

A **Pull Request** (or PR) is a request to merge a set of changes from one
**branch** to another. Typically some one (or group) has been working on a
particular aspect in a branch they started for that purpose, when it’s ready
they make a Pull Request to merge it back into the main version of the software
(that users download). A Pull Request can be from another branch inside the same
repository, or from a branch of a forked repository that is maintained
independently — i.e. Pull Requests can come from people who do not have commit
access on the main repository. 

Pull Requests are reviewed by someone with commit access for the target
repository (a **maintainer**) — they can be discussed and accepted (**merged**),
iterated, or rejected.

## How to contribute to a blockchain project on GitHub without writing code — a worked example

[This](https://github.com/xaur/decred-news/) is an example of a repository that
is open for contributions. It is for writing monthly editions of a Decred
newsletter, and is maintained by a member of the Decred community (@bee on
Slack).

Each month, @bee invites feedback on the new version by pasting a link to the
latest draft in the #writers_room channel on [Decred’s bridged communications
platforms](https://decred.org/community/) (Slack, Matrix, IRC, etc.).

![](https://cdn-images-1.medium.com/max/1000/1*qAy5MyOgvJfEkxC3AZZHdw.png)

Anyone who is aware of something relevant to Decred that’s not already covered,
or who spots a typo, can suggest edits using the button highlighted above. This
opens the file for editing. This file is written in markdown (.md), which is
probably familiar and quite easy to read. Here’s a useful [markdown
cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

![](https://cdn-images-1.medium.com/max/1000/1*UgBAtoU0-XGZwJ0Sys53Qg.png)

If you scroll down and click the green buttons you’ll follow a path through
“Propose file change” (which commits the change to your freshly created fork of
the original repository), and on to “Create Pull Request”, which invites the
repository’s maintainer to incorporate them.

![](https://cdn-images-1.medium.com/max/1000/1*KVQtlAQfFaS7Z55eD8mvjw.png)

In general, people probably won’t appreciate one-word Pull Requests, and it may
be better to [bundle a set of changes together in a
PR](https://github.com/xaur/decred-news/pull/29). There’s a space to describe
the PR. When it’s reviewed or someone leaves a comment you should by default
receive an email notification.

Pull Requests that are merged become part of the repository’s product, in this
case the repository is published along with versions on
[reddit](https://old.reddit.com/r/decred/comments/8woriv/decred_journal_june_2018/)
and [medium](https://medium.com/decred/decred-journal-june-2018-b489ccb83b12).

### Other ways to contribute through GitHub

All of the [Decred.org documentation](https://docs.decred.org/) is stored in
markdown files in the [dcrdocs
repository](https://github.com/decred/dcrdocs/tree/master/docs), Pull Requests
there can change the content of the project’s documentation directly.
Repositories for documentation, or Improvement Proposals (as used by projects
like [Bitcoin](https://github.com/bitcoin/bips),
[Ethereum](https://github.com/ethereum/EIPs) and
[Decred](https://github.com/decred/dcps) to discuss and develop changes to the
protocol), are usually quite restrictive in terms of the kind of PRs that are
acceptable.

Decred has a variety of other repositories on GitHub where one might make a
useful contribution. There are a set of sub-projects within the [Decred
organization on GitHub](https://github.com/decred), and more beyond this. For
example the [Raedah Group](https://github.com/raedahgroup) has assets for video
production on GitHub
([scripts](https://github.com/raedahgroup/video-production/blob/master/decredPoS/decredPoS_script.md)
and
[storyboards](https://github.com/raedahgroup/video-production/blob/master/decredPoS/decredPoS_storyboard.md))
which are open to community feedback and suggestions.

Repositories are all maintained by different people/groups, who will have
different ideas about the kind of input that’s useful. The maintainers of these
repositories invariably have a presence on the project’s bridged communication
channels so it is probably best to participate in the discussion there before
jumping into Pull Requests. 

**Issues** are also a flexible and widely used way of collecting certain kinds
of information. For Decred’s repositories most of the issues could be
categorized as bug reports or feature requests, discussion tends to happen in
the bridged communications channels. With feature requests, for anything major
people would typically raise an idea in the bridged communications channels
before adding an Issue, but issues reporting unknown bugs are always welcome. 

![](https://cdn-images-1.medium.com/max/1000/1*8nwyThlx0osSRt5Q82j_Mw.png)
<span class="figcaption_hack">Issues page for Politeia (8th August 2018)</span>

Issues and Pull Requests are part of the workflow for a project, by reading them
you can see what’s going on. By writing them, you can contribute to that
workflow in certain ways, but it’s a good to first understand how these tools
are being used in the repository you’re interested in, so that you can make
contributions which are more likely to be useful.

The barriers to interacting with the workflow of your favorite cryptocurrency
project are social. GitHub makes it easy to contribute. The barriers to making
useful contributions are about finding places and ways in which do to this that
are recognized as useful by the repositories’ maintainers.

I’ve described the GitHub web GUI because that’s the easiest way to get started,
but it’s also quite easy to install software that stores repositories locally
and pushes locally stored commits online as requested. This would be the more
conventional way of using git and GitHub.

### Getting paid for contributions

It seems common enough for people who contribute to cryptocurrency projects to
be rewarded in that currency. The source(s) of these rewards vary from project
to project, perhaps a founder or foundation with ample reserves, or donations
from the community more broadly. The projects that interest me have an
autonomous source of such funding, usually a portion of the block reward.

Decred is one of these projects, I have also [written about
Dash](https://medium.com/@richardred/observations-of-the-dash-treasury-dao-c94231b2b5c4).
In Decred’s case the process of becoming a paid contributor is [social and
informal](https://medium.com/decred/how-to-get-hired-as-a-decred-contractor-e1435842df10),
but it is presently being elucidated and will become more formalized soon
through [Politeia proposals](http://proposals.decred.org). The [project
fund](https://explorer.dcrdata.org/address/Dcur2mcGjmENx4DhNqDctW5wJCVyT3Qeqkx)
is there to fund work which adds value to the project and furthers [its
aims](https://github.com/decred/dcrdocs/blob/master/docs/getting-started/constitution.md).
In general work that is regarded as doing so by stakeholders should be
compensated, provided Politeia is working well.

## git to work

git, and GitHub, can be used to collaborate on documents other than code. This
article concludes by considering some pros and cons of git(hub) as compared to
alternative tools for collaborative writing, chiefly the ubiquitous Google Docs.

There is a steeper learning curve with GitHub than Google docs, as Gdocs has a
more familiar WYSIWIG  approach. Direct editing in a shared Gdoc is like
collaboration between contributors who all have commit access to a repository —
Suggest Mode in Gdocs is equivalent to Pull Requests. Gdocs handles edits or
suggestions on an individual basis, whereas with git(hub) the tendency is to
group these into larger commits and pull requests. 

Gdocs focuses attention on a common live version of the document, it chunks
edits into versions on the back-end and these historical versions can be
browsed. GitHub represents the history of a document more clearly, presenting
details of who submitted and approved sets of changes up-front, and tending
towards distributed storage of the documents’ histories.

GitHub’s approach is arguably better when dealing with documents where the
detail matters, and changes should only be made with the consensus of
contributors — as it affords every contributor or watcher greater opportunity to
review the history of edits. I would guess that it also scales better with
larger numbers of participants, but I haven’t seen it used by particularly large
groups for collaborative writing.

In the context of work on blockchain projects it is worth noting that git is
more decentralized and confers greater censorship resistance. Google Docs and
GitHub are both centralized services, and it is within the service provider’s
power to shut down accounts and documents/repositories. git is decentralized,
its users store local copies of the documents and their histories. GitHub is
just a convenient place to push changes to, where they can be retrieved and
discussed by other participants, although it does add useful features like
Issues and Pull Requests to the workflow. Users of GitHub are however likely in
a better position to recover from censorship than users of Google Docs, with
local storage of files being the norm and open source alternatives like
[GitLab](https://about.gitlab.com/) already available. 

A project on GitHub is also more accessible to someone who doesn’t want to set
up user accounts with Google or Microsoft, they can push their commits to some
other location they control to be retrieved by other contributors directly.
