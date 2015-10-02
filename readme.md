# Simulacrum Presentation

## Introduction

Most of you already know me, but for the ones that do not, or have forgotten, as I always do. I am Robert-Jan, I study Art History with a love voor Digital Humanities and programming. Just before the vacation Frederike asked me wether I could technologically improve the website so that it would run better on phones and maintenance would be easier. I accepted the proposition, as it is very much connected to the reason why I combine the two different fields. I believe humanities can learn a lot from tech and the same goes the other way around. For myself it would help me professionalize my processes and provide  me with something presentable if done well. Yet, as always happens with digital products, it did not end there. When we talked it trough it became apparent that Simulacrum would get a new design and you would like that to be connected to the website. This made it a full blown assignment and the presentation last week was the starting shot. 

## Process

Before I show you what I currently have I want to make clear that web development is not first and foremost technological. Most of it is loaded with values, it is ’waarde-betrokken’. Seemingly technical decisions could just as easy be done differently to an entirely different result. There are also many processes surrounding it like strategizing on different levels, project management and collaboration, testing and maintenance and of course the design and building itself. It is important to realize that a website is a means to an end, not an end in itself. Today I mostly want to talk to you about that. What goals are to be achieved with the website, what needs to be considered for a proper strategy, and how that translates to actual features and design.

I would also like to impress upon you that websites are never really done, nor are they ever really ‘stable’ or ‘dependable’. A good example of this are our friends Kanvas, whose site is already offline for a good month or more. Next to that development assignments often fail because of a lack of communication and the ability to define the assignment. Just take a look at the IT failures in the government. To address this problem sequential development, the style of development where everything is negotiated upfront and eventually a product is delivered, is often dropped in favor of a iterative or agile development model. In this model very small and always deployable versions or iterations are made. These are then tested and evaluated in collaboration with the client. This model acknowledges that sites are never done and prevents that a lot of work is done while the product does not even come close to what is desired. 

## Product - Version 0.0.1

Currently I have made a low fidelity deployment of Wordpress with a Simulacrum theme. By low fidelity I mean that a lot of stuff is not done. What I did look into is first and foremost a lot of technological stuff I will not bother you with. Secondly I did quite a bit of UX-design like navigation and responsiveness. Thirdly and connected to the UX-part I did some content strategizing. This was the thing that cost me the most time, and I made mistakes several times. 

To explain this, while I had started by dropping many easily changed and yet time consuming design features, I had still taken largely a design driven approach. My starting point was the paper design. I started to realize why this is considered horrible in the world of web development. By focussing on the design the content had to bend to it. Sometimes the content was cramped into spaces that were much too small. Even worse the content itself did not get any thought. It should be the tech and design that bends to the content and the goal that is set, not the other way around. So I started to focus on the goals and content first; which I will go into soon.

The current iteration is enough however to see what potential there is in this system I believe. Take a look around it while I will continue talking, its live at …. The login to the control interface is admin/admin. I will go into the specific views a bit later into the presentation

## Goals and content strategy

Lets talk a bit more about strategy. I have the feeling that the desire to build a website arose more or less in the form of ‘we cannot ignore the web!’. A web presence was somehow felt as needed. Thus it was probably decided that a little blog, some news, and also contact and some redactional information should be on it. In my current assignment it is that content is that should be carried over to the new site. Yet I would question this content to some extend. Why specifically these items, and how does that content connect to your audiences? To take that even one step further, how does it connect to Simulacrums overal content strategy or even its business model? 

### Audience

Lets first get a clearer picture of your audiences. I would say that there are three main categories of visitors that Simulacrum wants to address. Each of these has their own set of goals and desired features. Firstly there are the writers and people with a business interest. These people want your strategic goals, the contact information and want to know whom is behind the publication. The writers specifically will need to know editorial information on how to submit articles and what the requirements are. Then there is the second group of people, the readers, whom are interested in the actual content and might become subscribers. These might include students, faculty members or the wider art or art historic community. These want to use or consume Simulacrums content and perhaps visit an event. Thirdly, and easily forgotten, there is Simulacrum itself. You will probably be the most fervent users of your own system, and it will need to be tailored to your needs too. 

### Audience and Digital 

With my current assignment I was a bit in conflict I noticed. The previous site tried to cater to the first two of these audiences at the same time, while not providing enough to satisfy either. A lot of information that would be of interest to business contacts and writers is missing and at the same time there is not much content for readers to consume and it positioned in a camped manner. I would like to argue that it might be wise to split the site up into two parts. One for readers and one for writers or other business interests. The third group, Simulacrum itself, is catered by automatically through employing Wordpress content management system. Although even there many improvements are possible. 

## Views

Lets go into the views in a bit more detail.

### The reader

To dive into the view provided to readers, we have to explore how Simulacrums paper content strategy can find expression into the site. Right now the content that is being produced for the online blog is thematic and periodical, just like the magazine. There is no content, aside from the news, that is not attached to an issue. If this is so, it seems logical to find a way to attach the content to the issues in some way. So instead of opting for a normal continuous post flow, I attached all the posts to their issues, and present those to the readers. The current issue is a prominent position, and the list goes down a few issues. Older issues can be found on the archival page. There is also a business aspect to this. The content online should confront readers with the fact that this it is expensive to create and subscriptions are well appreciated. I like the gift model of content dissemination; where full content is offered at the cost of a moralizing message up front. Every post has got a message up top reminding people of the possibility of subscribing. As I do not want to get into member registration the presence is small and innocuous, but its there for people to see. 

What I still have to find a solution for is how to deal with footnotes and the like. As Simulacrum aims to be scientific it should try to follow academic conventions as much as possible. What those conventions are on the web is up for debate however. The Open Access movement has some experience in the matter, these guys try to free academic publishing from evil corporations like Reed / Elsevier. I must honestly say, I am still new to the business. There are quite some problems to consider. For instance how do you cite digital objects? As page numbers are irrelevant, how do you narrow your citation down, paragraphs? Next, how does one ensure that the digital object that the reader reads is actually the same as the one the citing author reads? As articles can always be changed online, versioning is a real problem. Thirdly there are serious problems for archival. Libraries can easily store paper, digital objects is another matter however. Last but not least there are the legal issues; do the licenses allow to syndicate or for individuals to share content? There are good solutions for all these problems, but it will need to be thought about thoroughly. Especially if Simulacrum wants to go all in with it in the future. For now I have opted to keep it rather simple. Everything is just plain text or HTML in the post view. 

### Writer / Business interest

To dive into the view for writers / business interests, there are several thing that I believe the website should address. A nice thing to start with it author documentation. Many scientific magazines have an elaborate documentation on how content should be delivered, the Rijksmuseum Bulletin has eight pages of demands, and you probably have something similar. We could streamline this in the web interface, along with providing a way to submit. That could be a simple mail address or something more elaborate. Secondly I think its important to state again what Simulacrums scientific process really is about. How is the peer review done? Even if it is done by students, people should be able to decide on their own what its authority is. Thirdly it might be interesting to present the upcoming issue as a call for papers. Fourth, there is of course the Simulacrum strategy and goals. Last but not the least, the people involved should get a place. Also because of its nature as a student magazine where changes in editors happen quickly, it might also be nice to provide previous editors a place there too. As a side note I also display the news over as it is relevant to both groups. 

### Editorial

The big advantage of Wordpress is that the administrative interface is largely self explanatory. There are quite a bit of additions that we could make to it though. Digital infrastructure could play a larger part in the editorial workflow for instance. A good illustration of what could be is the OJS editorial workflow. While this system is complete menace technically, they did think quite well about this and the role a digital system could play in this. Secondly from a UX and business point of view we should also consider using measurement tools to see what content is consumed and base decisions on it accordingly. 

## Planning

Please not that I am exploring as I go just as you guys are. You guys might not know what could be build, but neither do I. I might have a year of programming skills, but knowing how to set up online academic publishing properly is another thing altogether. So right now I am just teasing your and my own imagination. I want to present what can actually be decided upon without making it too technical. 

At the start of the presentation I hit the topic of iterative or agile development. I have no illusions about the current product. Many features are still missing. The design is also far from optimal yet, I really want to talk to designers a bit more about that. However talking to you about the actual goals and content strategy seemed sensible to do first. I have a nice list of things I still want to add though, and that is what iterative development is all about. Small versions that are always deployed, tested and discussed. Instead of sequential development it is a much more transparant and collaborative process.

To that end I want to show you a tool that is quite important for iterative development. Its called git and a popular hosting platform for it is github.com. Git is a version control system, and allows people to share files and collaborate properly. This project already contains 42.000 files without me doing much of anything to get at that insane number. You can imagine sharing a few edits in a few files can become a mess rather quickly. Especially if you work in a team when someone else has also made a few edits in the same or other files. You do not need to how the fine print to how it works, the sugar of git comes at the cost of a steep learning curve. You can look at it a dropbox on steroids. All you need to know is that the work is stored there in the organization simulacrum-amsterdam. You can find this presentation there too. Also the documentation and links to the staging environment are there. Next to that I use the collaborative environment to plan my work, reflect upon it and to discuss it. Doing this close to the actual files help to keep the discussion concrete. 

## Discussion / Feedback

1) The first question I struggled with is how far we should take Simulacrums scientific identity. Going full in means that at some points we will have to sacrifice a bit of design an UX. To give a little illustration of this is how the magazine First Monday presents is articles. They address all the issues concerned with in online academic publishing within a single view. These include:

Simulacrum already addresses these:
- Author information
- References
- Footnotes

But online there are also these to consider:
- Abstracts
- Navigation
- Editorial information
- Licensing -> Think Creative Commons

2) Translation of the content strategy to the website. Are we in agreement as to the audiences and the choices I have made as to structure in which the content will be presented?

3) What do you guys think of the current design? (even though typography is still absent)

4) What kind of feature do you want added, that are not already in the issue list?




