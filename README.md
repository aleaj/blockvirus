# BLOCKVIRUS
Blockvirus group's repository for EUvsVIRUS hackathon.
In here, you will find the progress made by the team BLOCKVIRUS during the PanEuropean Hackathon EUvsVIRUS, which aims to give real solutions to problems which Covid-19 pandemia's has induced during the last months all over the globe.

## Blockchain as a tool for beating the virus
Our target is to monitorize the production chain of some of the most valuable devices for healthcare during the pandemia (i.e. facemasks). Using state-of-the-art blockchain algorithms and implementing an online interface we will manage to register each step of the production of this objects preventing factories from outside of the EU community of submitting defective packs to each country gonvernment.

## How to contribute

### Where to start

**Step 1:** Each team member
[forks](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
the *central repository* (this one) to make their own *personal repository*.

**Step 2:** Contribute!

### Contribution workflow

Every member of the team commits changes locally and pushes them to
their personal repository.  Whenever they finish a logically
independent subsection of their work, they submit a [pull
request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
to the team repository, which is merged by the team head.  The team
head submits a pull request to the central repository whenever the
team hits any minor milestone: interface built, hash, blocks structure done,etc.

You don't have to send pull requests after every single commit.  Team
members should send a pull request to the team repository after about
a day of work.


Within the team, it is best to avoid multiple people modifying the
same parts of the same file at once.  Such concurrent modifications
usually lead to merge conflicts which may be tricky to resolve.
Multiple people may work on the same files at the same time
seamlessly, provided that they modify *different* parts of those
files.

Commit often and keep your commits small and localised.  This will
reduce the risk of merge conflicts and will allow you to have a
finer-grained history.

### Git workflow

#### Checking out

Start by checking out your personal repository using a command similar
to this one:

```
git checkout git@github.com:[your-username]/covid-p-models.git
```

You will have to
[generate](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
and
[upload](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)
SSH keys in order to use such a link.  Note that you can just open the
`~/.ssh/id_rsa.pub` with a text editor and copy and paste the public
key by hand, without relying on `xclip`.

#### Committing

A commit corresponds to a logical block of your work which you can
describe with a short sentence.  Commit often and keep the
descriptions clear.  This will help you and your teammates understand
and debug your work.  The simplest way to commit all your local
changes is the following command:

```
git commit -a -m "Helpful commit message."
```

#### Pushing and pull requests

Pushing is the operation by which the commits you added to a branch
locally get into the corresponding branch in your personal repository.
When you push to a branch, you can [create a pull
request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
from that branch to the team repository.

The whole team should review the pull requests of the members to make
sure everyone stays in sync with the team's current objectives.

Whenever appropriate, the team head submits a pull request to the
central repository.  The teachers will review and merge the pull
request, which may also be reviewed by the members of the team.

#### GUIs and porcelains

You can of course use one of the very [many graphical user
interfaces](https://git-scm.com/downloads/guis) to Git and/or GitHub.

If you like GNU Emacs, you may consider using
[Magit](https://magit.vc/).

### Resources

1. [To Git or Not to
   Git](https://www.ibisc.univ-evry.fr/~sivanov/content/courses/togit/togit.pdf)
   — An overly simplified explanation of some of the concepts behind
   Git.
2. [The Git Book](https://git-scm.com/book/en/v2) — If you don't have
   much experience with Git, I highly recommend that you glance
   through the first 6 chapters of this document.  The basic concepts
   of Git are very simple, even if somewhat numerous, but a surprising
   number of "simplified" explanations get them wrong.
3. [Hello World](https://guides.github.com/activities/hello-world/) —
   A hugely simplified explanation of how to work with GitHub.
4. [Generating a new SSH key and adding it to the
   ssh-agent](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
   — Note that you don't actually have to add the key to ssh-agent,
   but it's probably a good idea.
5. [Adding a new SSH key to your GitHub
   account](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)
   — Note that you can just open `~/.ssh/id_rsa.pub` with a text
   editor and copy and paste the public key by hand, without relying
   on `xclip`.
6. [About Pull
   Requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
   — A detailed presentation of different operations related to pull
   requests: creating, reviewing, merging, etc.
   
One important thing to remember: Git is **not** GitHub.  GitHub is a
Web resource based on Git and extending it with tons of new
functionality.  Git on the other hand is a separate, stand-alone tool,
which doesn't even need to be connected to a platform like GitHub.