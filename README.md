# BLOCKVIRUS
Blockvirus group's repository for EUvsVIRUS hackathon.
In here, you will find the progress made by the team BLOCKVIRUS during the PanEuropean Hackathon EUvsVIRUS, which aims to give real solutions to problems which Covid-19 pandemia's has induced during the last months all over the globe.

## Who are we?
We are a group of five undergraduate students in Biomedical engineering, Physics and Graphical design based in Spain. During the present quarentine we want to help society by creating this potential application we describe in this repository. 

![App logo.](/index.jpeg)

## Defectuous medical material and devices brought from China by Fake providers
In these days, many of us have seen in the Press and mass media how different EU governments such us the Spanish or the Finnish one have bought unuseful medical supplies that did not passed the European quality controls, loosing a very precious time during the process of buy and a vast amount of money in it.
Here you can see some of the press records on this problem:
	https://www.bbc.com/news/world-europe-52092395
	https://www.theguardian.com/world/2020/mar/27/coronavirus-test-kits-withdrawn-spain-poor-accuracy-rate
	https://www.elmundo.es/television/medios/2020/04/22/5ea0af58fc6c83d03e8b45a3.html
	https://www.businessinsider.com/coroanvirus-holland-recalls-over-half-a-million-masks-imported-from-china-2020-3?IR=T
	https://yle.fi/uutiset/3-11313408
	https://www.vice.com/en_us/article/7kzae9/european-countries-are-throwing-out-rubbish-chinese-made-masks-and-coronavirus-tests
	http://www.dailyfinland.fi/health/15415/Sub-standard-masks-withdrawn-following-healthcare-workers-illness

![Press screenshot](/press.jpeg)

## Blockchain as a tool for beating the virus
Our target is to monitorize the production chain of some of the most valuable devices for healthcare during the pandemia (i.e. facemasks). Using state-of-the-art blockchain algorithms and implementing an online interface we will manage to register each step of the production of this objects preventing factories from outside of the EU community of submitting defective packs to each country gonvernment.
The idea behind it is that it is impossible to get something from where there is nothing ( in Spain there is a proverb that enounces: "De donde no hay no se puede sacar."). Providers and intermediate distributors will not have the possibility to commit fraud on what they are selling because the customer will know with just scanning a QRcode-label which has it been the track of the product in every moment of its manufacture.
The architecture of our system is simple. We are building a decentralized network constituted by independent nodes (each step of the process) which are able to upload information about every single step of the process. These uploads are called blocks and are appended to a bigger chain. 
By giving each block the information of the previous blocks but not of the parallel processes we can keep the privacy of the entire network and the relationships graph of the factories and laboratories.

We are currently working in an html web interface for sellers, customers and distributors. In addition, we are investigating on the actual implementation of the system between China and de EU community solving market and law problems.

## What have we done during the Hackathon's weekend?
After giving shape to our idea, we started to look for previous research done on this problem. We found an IBM code for a blockchain network, some implementations of this technology in the groceries' business and also in medical tools i.e. scalpels and surgery's devices.
Here is the IBM repository from where we have taken the skelethon of our code.
	https://developer.ibm.com/technologies/blockchain/tutorials/develop-a-blockchain-application-from-scratch-in-python/
Here are some of the developers we have found that are currently working or have worked in the traceability problem of medical supplies:
	https://www.technifor.com/markets-and-materials/markets/medical/traceability-of-medical-devices
	www.fda.gov/medical-devices/postmarket-requirements-devices/medical-device-tracking

Even U.S. Food and Drugs administration has begged for a traceability solution during this crisis, a way of demonstrating that the quality of the devices bought is higher than a standard limit.

Other developers are working on the same idea in the U.S. market.
	https://cointelegraph.com/news/blockchain-to-authenticate-coronavirus-response-kn95-face-masks-from-china

## Which is the impact of our solution?
Using our system would endow the sellers' products of a Quality hallmark beyond European Quality tests (which non-EU products do not have to pass). Now, when a government orders millions of facemasks, for example, will know for sure that they are completely functional and not defectuous which will benefit in saving time spent in finding the stock, money paid to fake distributors and repercussion in mass media that gives a bad image to the Ministery representers.
What's more, fake distributors won't be able to sell their stockpile and commit fraud. We are helping to create a more lawful market.

![Woman using a quirurjical facemask](/mask.jpg)

## What do we need to carry out our project in real world
From now onwards, the gap between our prototype and a final version that could be implemented in the current market does not seem very wide. We need advise on international law, factories and market methods to sell our idea to each link of the production chain. Also, for a final version of the app, a review on cibersecurity hash algorithms needs to be made. Our product has to be secure and procure the clients the privacy the deserve.

## It does not stop after Covid's crisis
As it has been remarked in one of the previous paragraphs, the traceability problem is up to date in many different market fields. Particularly in the medical market it is not widely implemented. So our tool gives a practical solution to be implemented in the close future. 
Investors will see there are a lot of opportunities that will give profits to this idea.

## Contact information
In order to contact us you can comment in our Devpost webpage: http://devpost.com/software/blockvirus.
We are currently participating in EUvsVIRUS Paneuropean hackathon.


##




#### Use of the GitHub repository:

**Step 1:** Each team member
[forks](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
the *central repository* (this one) to make their own *personal repository*.

**Step 2:** Contribute!

#### Contribution workflow

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

#### Git workflow

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

#### Resources

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
