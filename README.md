[![View Now](img/viewnow.png)](http://5minfork.com/nikmd23/oss0to60/)
___

# Running OSS Projects: From Zero to Sixty 
> Glimpse, an open source web application diagnostics tool, went from a rough back-of-a-napkin idea to a project with tens of thousands of users and developer media attention within a period of eight weeks. Join Glimpse’s co-founder, Nik Molnar, for an honestly raw tale of the pains and lessons learned that arose managing an open source project. Along the way, Nik will cover the tools and techniques that have proven successful over the past two years developing Glimpse, focusing on technical challenges and best practices for community management, communications and open source/life balance.This session is suitable for founders, maintainers, contributors and all users of open source software and aims to spark conversation around the best way to foster open source and open source etiquette.

## Outline

### Introduction
- Who I am - quick introduction to who I am, what I do and my background.
- How I started in OSS - overview of the Glimpse story and the ensuing onslaught after the Hanselbump
  - Video from Channel 9
  - Pictures from Mix
- Introduction to [Tuckman's Stages of Group Development](http://en.wikipedia.org/wiki/Tuckman%27s_stages_of_group_development)
  - Forming
  - Storming
  - Norming
  - Performing
  - [Icons](http://4.bp.blogspot.com/-ihTg3P3EfmE/TcmrBAwknxI/AAAAAAAAAAk/pgc4TZXcVik/s1600/Untitled.jpg) and [Instructional Chart](http://www.the-happy-manager.com/wp-content/uploads/tuckmangroupstagesmodel1.png)
  - OSS is special because the team is constantly churning - so there are always people in each of these stages.

#### 1 Forming

##### 1.1 Project Setup
- Misson statement/readme.md that expresses the goals of the project and what it will/won't do
- Developer guidelines
- Demo/screenshots!
- *Forkability* - the ease of which a developer *could* fork the project which also makes it easy for them to grab the code, build it and get started
 - Keep as many dependencies in source control/package restore as possible
 - Single command build process
 - Developer documentation
 - Forkability helps to ensure distributed leadership

##### 1.2 Selecting a License
- Proper Licenses from [OSI](http://opensource.org/) vs [Creative Commons](http://creativecommons.org/)
  - [tl;dr Legal](http://www.tldrlegal.com/) provides great tools for selecting and understanding.
  - There is also [simple selection flowchart](http://i.stack.imgur.com/igJ6X.png) vs ["funny" selection flowchart](http://cl.ly/5nAo)
  - Phil Haack's Developers Guide to Copyright Law [Part 1](http://haacked.com/archive/2006/01/24/TheDevelopersGuideToCopyrightLaw-Part1.aspx), [Part 2](http://haacked.com/archive/2006/01/24/DevelopersGuideToOpenSourceSoftwareLicensing.aspx) & [Part 3](http://haacked.com/archive/2006/01/26/WhoOwnstheCopyrightforAnOpenSourceProject.aspx)
  - <span style="background-color:red; color: white; font-weight: bold;">How do CLA's fit in?</span>
 
##### 1.3 Selecting a Governance Model
- [Meritocratic Governance Model](http://www.oss-watch.ac.uk/resources/meritocraticGovernanceModel) or [benevolent dictator](http://www.oss-watch.ac.uk/resources/benevolentdictatorgovernancemodel).
  - *It is no surprise, therefore, that meritocratic project management committees and benevolent dictators both exercise their decision making power through loyalty rather than legalities. They all know that members are free to take the code and create alternative projects. In fact, this ability to fork is very important to the health of open source communities. This is because it ensures that those involved in project governance strive to make the right decisions for the community, rather than for a single individual or company.*
  - [YUI as an example](https://github.com/yui/yui3/wiki/Contributor-Model)
  
#### 2 Storming

##### 2.1 Communication
- **Incoming**: Forums, Mailing Lists and Issue Tracker
- **Outgoing**: Blog and social media
- **Internal**: HipChat, Trello and Skype
- Avoid private/internal communications

##### 2.2 OSS/Life Balance
- Cute puppy syndrome from [@fat](https://github.com/fat)'s [video](http://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0CDAQtwIwAA&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DUIDb6VBO9os&ei=N8WbUfzCMvOz4APonICAAw&usg=AFQjCNEjRH7wE1xfxuZUPgHJbiaDpvdRNg&sig2=AfxZDLkpVzEYk1OeC5U0jg&bvm=bv.46865395,d.dmg&cad=rja)

##### 2.3 Dealing w/ $$
- Mix offer & why we really did Glimpse

##### 2.4 Nom de plume
- **My story of having issues with Anthony** - Even happy/nice emails have turned bad because of past carelessness. 
- the only thing anyone knows about you on the Internet comes from what you write, or
what others write about you. You may be brilliant, perceptive, and charismatic in person—but if your
emails are rambling and unstructured, people will assume that's the real you
- [On the Internet, nobody knows your a dog](http://en.wikipedia.org/wiki/On_the_Internet,_nobody_knows_you%27re_a_dog)
  - Your avatar and handle are your face - try to be consistent
  - User proper grammar, spelling and punctuation
  - Consider subject/title lines carefully
  - Use a diagram if it will help! ([AsciiFlow](http://www.asciiflow.com/) & [WebSequenceDiagrams](http://www.websequencediagrams.com/))
  - Provide context! Use a link to another thread or an issue . Make it easy for the reader
  - Edit twice for anything larger than a paragraph
  - Watch your tone
  - [Don't feed the trolls](http://www.stubbornella.org/content/2012/05/31/dont-feed-the-trolls/) by Nicole Sullivan
  - Avoid bike shedding and holy wars

#### 3 Norming

##### 3.1 Automate Everything
- Including community management!
  - CI/GitHub integration
  - StyleCop
  - Documentation, leveraging the wiki?

##### 3.2 Community Management
- <span style="background-color:red; color: white; font-weight: bold;">Double check Bacon's book. Fogel's book seems a bit more practical.</span>
- Understand the motivations of your community.
  - [Why Hackers Do What
They Do: Understanding Motivation and Effort in Free/Open Source Software Projects on FLOSShub](http://flosshub.org/sites/flosshub.org/files/lakhaniwolf.pdf)
- Treat Every User as a Potential Volunteer
- Meeting In Person

#### 4 Performing

##### 4.1 Sponsorship
- TeamCity at CodeBetter
- RedGate
- JetBrains
- MyGet
- GitHub
- Atlassian

##### 4.2 Create Opportunity
- [Jump In](http://nikcodes.com/2013/05/10/new-contributor-jump-in/)
- Automate standards enforcement 
- Thank contributors as loudly as possible

### Conclusion

#### Not running a project?
- Pay it forward. Can't contribute to project X? Give to project Y.
- Requirements
  1. Motivation to share
  2. Ability to collaborate

#### Resources
- [Producing OSS by Karl Fogel](http://producingoss.com/) *(plus [2nd Edition Kickstarter](http://www.kickstarter.com/projects/kfogel/updating-producing-open-source-software-for-2nd-ed)!)*
- [The Art of Community by Jono Bacon](http://www.artofcommunityonline.org/)
- [Understanding Open Source & Free Software Licensing by Andrew St. Laurent](http://oreilly.com/openbook/osfreesoft/book/index.html)
- [The Cathedral and the Bazaar by  Eric Raymond](http://en.wikipedia.org/wiki/The_Cathedral_and_the_Bazaar)

## Random Notes

### Quotes
- **Raymond's Linus's Law:** *"Given enough eyeballs, all bugs are shallow."*
- **Torvald's Linus's Law:** *"Every motivation that makes a man do something can be classified under 'survival', 'social life' and 'entertainment'.*
- **Brook's Law:** *"Adding manpower to a late software project makes it later."*
- **Henry Ford:** *"Coming together is a beginning; keeping together is progress; working together is success."*
- **Metcalfe's Law:** *"the value of a network grows by the square of the size of the network"*
- **[Parkinson's Law of Triviality](https://en.wikipedia.org/wiki/Parkinson%27s_law_of_triviality):** *"the amount of noise generated by a change is inversely proportional to the complexity of the change"*. a.k.a "Bike shed". [Full article at bikeshed.com](http://bikeshed.com/)

### Ideas
- Cathedral and the Bazaar
- Using semver.org (and semantic release notes?)
- The [pull request hack](http://felixge.de/2013/03/11/the-pull-request-hack.html)?