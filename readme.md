# Simulacrum Presentation

## Introduction

Most of you already know me, but for the ones that do not, or have forgotten, as I always do. I am Robert-Jan, I study Art History with a love for Digital Humanities and programming. Just before the holiday Frederike asked me whether I could technologically improve the website so that it would run better on phones and would be better maintainable. I accepted the proposition, as it is very much connected to the reason why I combine these two different fields. I believe humanities can learn a lot from tech and the same goes the other way around. It would also help me to professionalize my processes and to provide me with something presentable if done well. Yet, as always happens with digital products, it did not end there. When we talked it through it became apparent that Simulacrum would get a new design and would like that to be connected to the website. This made it a full blown assignment and the presentation last week was the starting shot. 

## Process

### Different fields of web development

Before I show you what I currently have I want to make clear that web development is not first and foremost technological. Most of it is loaded with values, it is not objective. Seemingly technical decisions could just as easy be done differently to an entirely different result. There are also many processes surrounding it like strategizing on different levels, project management and collaboration, testing and maintenance and of course the design and building itself. It is important to realize that a website is a means to an end, not an end in itself. Today I mostly want to talk to you about that. What goals are to be achieved with the website, what needs to be considered for a proper strategy, and how that translates to actual features and design.

### Project management models

I would also like to impress upon you that websites are never really done, nor are they ever really ‘stable’ or ‘dependable’. A good example of this are our friends Kanvas, whose site is already offline for a good month or more. Next to that development assignments often fail because of a lack of communication and the ability to define the assignment. Just take a look at the IT failures in the government. To address this problem sequential development, the style of development where everything is negotiated upfront and eventually a product is delivered, is often dropped in favor of a iterative or agile development model. In this model very small and always deployable versions or iterations are made. These are then tested and evaluated in collaboration with the client. This model acknowledges that sites are never done and prevents that a lot of work is done while the product does not even come close to what is desired. 

## Product - Version 0.0.1

Currently I have made a low fidelity deployment of WordPress with a Simulacrum theme. By low fidelity I mean that a lot of stuff is not done. What I did look into is first and foremost a lot of technological stuff which I will not bother you with. Secondly I did quite a bit of User Experience Design (UX) like navigation and responsiveness. Thirdly and connected to the UX part I did content strategizing. Wrapping my head around this really cost me a lot of time and I made quite a few mistakes in the process. 

### Design-driven vs Content-driven

To explain this, while I had started by dropping many easily changed and yet time consuming design features, I had still taken largely a design driven approach. My starting point was the paper design. I started to realize why this is considered horrible in the world of web development. By focussing on the design the content had to bend to it. Sometimes the content was cramped into spaces that were much too small. Even worse the content itself did not get any thought. It should be the tech and design that bends to the content and the goal that is set, not the other way around. So I started to focus on the goals and content first. What those goals should be however confused the hell out of me. Scientific publishing online seems to be an entirely different thing than main stream web development, but I will get to that later on.

### Live iteration: URL’s and passwords

The current iteration is enough however to see what potential lies in the system. Take a look around it while I will continue talking, its live at …. The login to the control interface is admin/admin. I will go into the specific views a bit later into the presentation

## Goals and content strategy

Lets talk a bit more about strategy. I have the feeling that the desire to build a website arose more or less in the form of ‘we cannot ignore the web!’. A web presence was somehow felt as needed. Thus it was probably decided that a little blog, some news, and also contact and some redactional information should be on it. In my current assignment it is that content is that should be carried over to the new site. Yet I would question this content to some extend. Why specifically these items, and how does that content connect to your audiences? To take that even one step further, how does it connect to Simulacrums overal content strategy or even its business model? 

### Audience

Lets first get a clearer picture of your audiences. I would say that there are three main categories of visitors that Simulacrum wants to address. Each of these has their own set of goals and desired features. Firstly there are the writers and people with a business interest. These people want your strategic goals, the contact information and want to know whom is behind the publication. The writers specifically will need to know editorial information on how to submit articles and what the requirements are. Then there is the second group of people, the readers, whom are interested in the actual content and might become subscribers. These might include students, faculty members or the wider art or art historic community. These want to use or consume Simulacrums content and perhaps visit an event. Thirdly, and easily forgotten, there is Simulacrum itself. You will probably be the most fervent users of your own system, and it will need to be tailored to your needs too. 

### Audience and Digital 

The previous site tried to cater to the first two of these audiences at the same time, while not providing enough to satisfy either. A lot of information that would be of interest to business contacts and writers is missing and at the same time there is not much content for readers to consume. I would like to argue that it might be wise to split the site up into two parts. One for readers and one for writers or other business interests. The third group, Simulacrum itself, is catered by automatically through employing WordPress content management system. Although even there many improvements are possible. 

## Views

Lets go into the views in a bit more detail.

### The reader

To dive into the view provided to readers, we have to explore how Simulacrums paper content strategy can find expression into the site. Right now the content that is being produced for the online blog is thematic and periodical, just like the magazine. There is no content, aside from the news, that is not attached to an issue. If this is so, it seems logical to find a way to attach the content to the issues in some way. So instead of opting for a normal continuous post flow, I attached all the posts to their issues, and present those to the readers. The current issue is a prominent position, and the list goes down a few issues. Older issues can be found on the archival page. There is also a business aspect to this. The content online should confront readers with the fact that this it is expensive to create and subscriptions are well appreciated. I like the gift model of content dissemination; where full content is offered at the cost of a moralizing message up front. Every post has got a message on top reminding people of the possibility to subscribe. As I do not want to get into member registration the presence is small and innocuous, but its there for people to see. 

### Writer / Business interest

To dive into the view for writers / business interests, there are several things that I believe the website should address. A nice thing to start with it author documentation. Many scientific magazines have an elaborate documentation on how content should be delivered, the Rijksmuseum Bulletin has eight pages of demands, and you probably have something similar. We could streamline this in the web interface, along with providing a way to submit. That could be a simple mail address or something more elaborate. Secondly I think its important to state again what Simulacrums scientific process really is about. How is the peer review done? Even if it is done by students, people should be able to decide on their own what its authority is. Thirdly it might be interesting to present the upcoming issue as a call for papers. Fourth, there is of course the Simulacrum strategy and goals. Last but not the least, the people involved should get a place. Also because of its nature as a student magazine where changes in editors happen quickly, it might also be nice to provide previous editors a place there too. As a side note I also display the news over as it is relevant to both groups. 

### Editorial

The big advantage of WordPress is that the administrative interface is largely self explanatory. There are quite a bit of additions that we could make to it though. Digital infrastructure could play a larger part in the editorial workflow for instance. A good illustration of what could be is the OJS editorial workflow. While this system is a complete menace technologically, they did think quite well about the role a digital system could play in this. For now I will not go into this much further, I will get back to this topic at the end of the presentation. Secondly from a UX and business point of view we should also consider using measurement tools to see what content is consumed and base decisions on it accordingly. 

## Planning - next steps

At the start of the presentation I hit the topic of iterative or agile development. I have no illusions about the current product. Many features are still missing. The design is far from optimal yet. While I am not absolutely horrible at it, I am dependent on designers for assets. That means that I need them for proper icons, fonts and the like. I really want to talk to them a bit more about that. However talking to you about the actual goals and content strategy seemed sensible to do first. I have a nice list of things I still want to add though, and that is what iterative development is all about. Small versions that are always deployed, tested and discussed. Instead of sequential development it is a much more transparant and collaborative process. 

To that end I want to show you a tool that is quite important for iterative development. Its called git and a popular hosting platform for it is Github. Git is a version control system, and allows people to share files and collaborate properly. This project already contains 42.000 files without me doing much of anything to get at that insane number. You can imagine sharing a few edits in a few files can become a mess rather quickly. Especially if you work in a team when someone else has also made a few edits in the same or other files. You do not need to know all the details, the sugar of git comes at the cost of a steep learning curve. You can imagine it as Dropbox on steroids. All you need to know is that the work is stored in the organization ‘simulacrum-amsterdam’. You can find this presentation there too. Also the documentation and links to the staging environment are there. Next to that I use the collaborative environment to plan my work, reflect upon it and to discuss it. Doing this close to the actual files help to keep the discussion concrete.

Setting a final date has already proven harder for me than I expected. I noticed there are a lot of unexpected corners that cost quite a bit of time to deal with. Strategizing about how the product should be shaped is definitely not the least of them, as it is very different in character to the things I have done before. I have to be honest, depending on how far we take this setting a specific delivery date might be problematic. What we can do however is set a next meeting and discuss the state of the project then. 

## Discussion / Feedback

1) The first question I struggled with is how far we should take Simulacrums scientific identity. To start I would like to say that not even the Amsterdam University Press handles its own online publishing. It might be an illusion to think that we can so properly. Many systems that authenticate content are simply really expensive, might be beyond my ability to provide for and is definitely beyond Simulacrums ability to manage properly. A thing like Google Scholar optimization for instance might be possible; but there is significant extra work involved. Getting our hands on Digital Object Identifiers however is certainly out of the question. 

It might even mean changing of content management system. To keep up scientific appearances I will be bloating the WordPress datamodel to do things it was not optimized for. Yet WordPress is simple to use and easily maintained. If we are going for the real thing on the other hand, then it might be interesting to take a look at Open Journal Systems. This system is specialized at journal publishing. It also has a really well thought out editorial workflow. However its community is nearly non-existent next to WordPress, and this finds translation in the product. Yet here I would like to point out again that keeping such a site running properly was not even a task that the AUP fancied.

2) What do you people think of the translation of the content strategy to the website? Are the choices I have made in structuring the content appropriate to the audiences? Are the audiences I suggested correct for that matter? -> Do you have a document containing the paper strategy now?

3) What do you guys think of the current design? Is it going in the right direction? (even though many things are still absent, like typography)

4) What features do you miss that are not already in the issue list?

