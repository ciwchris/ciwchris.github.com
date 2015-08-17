{:title "Software metaphors"
 :layout :post
 :tags  ["craftsmanship", "gardening"]
}


In Steve McConnell's book
[Code Complete](http://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670/ref=sr_1_1?ie=UTF8&qid=1439786849)
he discusses several metaphors used for software development. He begins by listing a variety of
metaphors from various people dating back to 1981. He then goes on to discuss four in detail.

### Penmanship

This metaphor states that software development is like writing a causal letter, you write it from
start to finish. There isn't formal planning and you figure out what to say as you go. Steve says
this process may work for an individual developer, but it doesn't scale. Software is not usually a
single person activity and unlike a letter you can change software after it has been shipped. The
Fred Brooks quote "Plan to throw one away; you will, anyhow." is a product of this metaphor. Steve
states this in not practical in most scenarios because of the expense in software development.

I find myself agreeing with Steve, although I believe the quote can also be helpful. It would be
unpractical to complete a project, throw it away and start from scratch; but prototypes can be
created, spikes can occur, time can be spent at various stages of the project to go back and rework
areas. Much will be learned from these activities, as well as from the development path. It would be
wise to incorporate these lessons into the final product. Much like a rough draft, you do not throw
everything out, but you spend time going back and rewording, restructuring and removing pieces as
well as adding new content. Additionally you spend research time before you begin writing the paper,
putting outlines together, etc. In this way writing a paper, not a letter, is closer to software
development. Additionally, in today's world authors can easily collaborate on a papers, even using
a version control system to manage changes.

### Farming

This metaphor states software development is like planting seeds and growing a crop. The idea is to
take small steps in order to minimize obstacles. Steve stays the incremental part of the metaphor is
helpful but overall it is not a good metaphor to use. It is hard to extend beyond doing things a
little bit at a time. It leads to the thought that you do not have direct control over how the
software is developed: you plant, wait and then harvest.

I agree this is probably not the best metaphor, however the software gardening metaphor, discussed
below, is the metaphor I currently identify most with. Farming does prompt the view, whether correct
or not, of planting and then waiting, letting the crop take its course. Gardening, however, prompts
a view of a much more active role in the process.

### Oyster Farming

Accretion, slowing adding on to something, is this primary thrust of this metaphor, just as an
oyster does when making a pearl. Similarly, you should learn to add to your software project a
little at a time, incremental and iterative are words used to describe this process, which sounds
a lot like agile practices; although Steve likens it to different software development phases such
as designing, building and testing. In agile, this slow accretion can leads teams to creating a MVP,
minimally viable product, and slowing adding on to it the features which bring value.

This does improve the farming metaphor in the way Steve discusses, but seems to be even less
extensible and relateable, and so is only useful in the single aspect discussed by Steve.

### Construction

Steve states the image of building software is more useful than writing or growing software because
it provides more detailed guidance. How a structure is built depends on what is being built, whether
small and simple or big and complex, which is also true of software projects. He discusses
architecting software, similar to creating blueprints. As you build others inspect the
structure, similar to code reviews. In both cases labor is the expensive portion and therefore good
design is important, so time is not wasted. He also states you will use prefabricated parts, similar
to libraries, but if the part is important with unique constraints you may custom make it. In both
cases the order of the project is important. A building doesn't have to be completing planned, like
what color to paint the walls. Structural changes in construction will cost a lot more, similar to
software.

### Software engineer

Closely related to the Construction metaphor is the title software engineer.
[Wikipedia states](https://en.wikipedia.org/wiki/Software_engineering#History):

> The discipline of software engineering was created to address poor quality of software, get
 projects exceeding time and budget under control, and ensure that software is built
 systematically, rigorously, measurably, on time, on budget, and within specification. Engineering
 already addresses all these issues, hence the same principles used in engineering can be applied
 to software. 

Similarities can be seen between the description Steve draws from the Construction metaphor and the
description of a software engineer. The title of software engineer is disputed. The
[Wikipedia article contains a section on Criticisms](https://en.wikipedia.org/wiki/Software_engineering#Criticism)
in which Dijkstra is quoted as stating:

> As economics is known as "The Miserable Science", software engineering should be known as "The
 Doomed Discipline", doomed because it cannot even approach its goal since its goal is
 self-contradictory. Software engineering, of course, presents itself as another worthy cause, but
 that is eyewash: if you carefully read its literature and analyse what its devotees actually do,
 you will discover that software engineering has accepted as its charter "How to program if you
 cannot."

Chris Aitchison expresses similar views in his blog article:
[You are not a software engineer](http://www.chrisaitchison.com/2011/05/03/you-are-not-a-software-engineer/).
He begins by stating:

> You are not a Software Engineer. You do not build skyscrapers. You do not build bridges.

And concludes with:

> The engineering metaphor has had its time in the sun, and maybe it even used to be accurate, but now
 it really only serves to help non-technical people have unrealistic expectations about how software
 gets built.

In its place he argues for the metaphor of a software gardener. When gardening you are unable to
plan exactly what it will look like, how many flowers will be blooming in a year, you can not make
it grow faster with more gardeners. You can only grow what your environment supports. Gardens
continue to grow, they are never finished. You do not need a license to grow a garden.

Patroklos Papapetrou has continued to push the metaphor. At NDC he presented on the topic: 
[The Art of Software Gardening](https://vimeo.com/131189624). After watching his presentation I'm inclined
to agree that the metaphor of software gardener is more appropriate. In the projects I've been a
part of, and from what I read about other projects, the conclusion I've come to is that the
typical software development project does not possess the rigor of engineering or construction, but
is closer in alignment to the creation of and caring for of a garden.
