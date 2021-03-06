# About This Site

## Delete All

For years before its current incarnation, my website followed an archetype of many portfolios: a grid of thumbnails with project titles. Every time I did something that I wanted to share, I'd find myself hiding embarrassing old projects, shuffling things around, and adding whatever was new to the top. The site looked clean, but I never really liked it. In fact I _hated_ it for making me feel like I always had to be chasing a tighter edit.

![](http://caseyagollan.com/content/about/old-site.png)

As luck would have it, my website which I hated [got hacked](https://twitter.com/caseyg/status/209773035539013633)  so that it was shuttling everyone to a shady Russian scam. Between my building dissatisfaction with the site and my discovery that the Russian bug had inserted itself into 6561 different PHP files on my server, I found the strength to hit <code>Delete All</code> and start again from scratch.

The latest version of this site is built on pretty much the same software as the boring old version, but in starting over I made a lot of conceptual decisions that add up to a vastly different site. 

## From Projects to Things _and_ Things in Things in Things

My biggest frustration with the old site was the threshold I had set for myself of "projects". _Does all this work add up to a project? Does it have a thumbnail image? A title?_ I found myself wanting to share lots of writing and notes, but the old site treated these things like crap. I experimented with a taxonomy of "projects", "experiments", and "notes" (which would allow me to visually weight how things are displayed) but it still felt constricting, so I eliminated the term "projects" completely in favor of...nothing. In the absence of a word, I'll use the terribly and wonderfully ambiguous "things".

A "thing" is not a "project". Every thing has a set of standardized meta information: title, date, excerpt, tags, description, and images or videos. All something needs to be considered a thing is at least one of those fields. And for most things, these fields are enough to present it in full. But in cases where they aren't, each thing can also contain any kind of content within itself. For example, the Systems essay is a thing, so it has [a page describing it](http://caseyagollan.com/systems/), but it also contains [the original webpage](http://caseyagollan.com/systems/read/) that the essay was published on within it. And that webpage can have its own revisions within _it_. (I always planned to revise the Systems essay, but now I have a publishing framework that will let me keep old versions online as well.) Nesting content within the catalog card for each thing and having the ability to contain versions or other sub-content affords not only the public hosting of revisions, but the possibility of "forking" projects. The latest version of a thing's content doesn't have to take precedence, every thing can simultaneously harbor alternate endings.

## Yes to Everything

So here we are. The old, arbitrary project structure has been run out of town, giving home to all kinds of nascent expressions, and a move has been made from a structure that relied on a series of tight, self-conscious, ephemeral selections of work to something more akin to a database, which favors inclusiveness, permanence, and the act of revision. But it's not yet time to celebrate.

Things are a mess. In this database coexists a single page of notes from yesterday, a long piece of writing from two years ago, and the first black and white photographs I took eight years ago. The system reports that there are @siblings_count pages on this site. That's a lot to ask anyone to process. Too much, considering that the subject of this site is _solely me_.

The traditional method of dealing with this glut of one's own history is to prune away it until there's an inoffensive amount left. But I like the idea of cataloging _all_ my embarrasing old shit along with what's new. Partly because every time I've ever tried to  find out about where somebody comes from online, going further than a few years back returns nothing but severed ends and erasures. 

Going back and describing everything I've done is a slow process that makes me embarrased and confused. Like when you're playing snake and your tail gets so long that you can't move without bumping into yourself. But the move to build my own catalogue raisonné is an intentional one. My desire to tease out networks of thought is, at this point, stronger than my fear of bumping into past versions of myself. I've had an idea brewing for a few years about jumping through a body of work along trains of thought that run through an entire lifetime, rather than navigating along a chronological track. 

## Fighting Streams (Reverse-Chronology is Boring)

This database couldn't possibly contain too much. Because of that, it leaves no clear path for myself or someone with a only a small degree of interest in what is going on here and not that much time to figure it out. To combat this glut, I created four different ways to dig in.

- <a href="/graph" >Graph</a>: Grab and throw things and ideas around to grok their connectedness. Might crash your computer.
- <a href="/archive">Archive</a>: Utilities for sorting and searching.
- <strike><a href="javascript:void(0);">Infinite-Scroll</a>: An escape hatch for those who want to sit back and not think too hard about heavy-handed organizational concepts.</strike> (Soon.)
- <strike><a href="javascript:void(0);">Narratives</a>: Written and illustrated arcs.</strike> (Soon.)

What you're first greeted with when you load this site is not a list or a grid, but a [Graph](/graph). Every thing on this site is tagged with ideas, places, and people, which tie it (in this case literally) to other things. Instead of priviledging what's _new_, the graph reveals centrality and fringes. It's not the simplest way to look at things, but it evokes most viscerally the idea that everything is connected. I find [force-directed graphs](http://en.wikipedia.org/wiki/Force-based_algorithms_(graph_drawing)) fascinating because they breathe a simulation of physics into data, giving information an appearance that is almost biological. Look how far we have come in terms of navigation: from a stolid grid to a teeming petri dish.

![](http://caseyagollan.com/content/about/graph.png)

Hovering over things will highlight related ideas.

![](http://caseyagollan.com/content/about/graph-thing.png)

Which allows you to wander, just by moving your mouse, from project to idea to project to idea.

![](http://caseyagollan.com/content/about/graph-tag.png)

The second way of looking at things is called the [Archive](/archive): a more descriptive, sortable view that (unlike the graph) is capable of displaying chronology, but still emphasizes threads and connectedness.

![](http://caseyagollan.com/content/about/archive.png)

Hovering over the tags at the bottom of each thing's card will preview a link to any related things. Clicking tags will bring forward all the projects along this thread and allow you to scroll along its course.

![](http://caseyagollan.com/content/about/archive-tag.png)

You can also search ideas or navigate them like a list. Here is an isolated selection of projects tagged "sexy", with a thread guiding you down the page towards earlier sexy things.

![](http://caseyagollan.com/content/about/archive-search-tag.png)

<img src="http://caseyagollan.com/content/about/underconstruction.gif" style="float:left;margin-right:10px;margin-bottom:5px;">

Two of the four ways I've designed in my head are ones that I'm not finished building yet. (If I had decided to wait until they were complete I'd probably never release this site at all.) Anyway, these four views are only a few of the experiments I can imagine running on my embarrasing, noisy personal database.

The third view is a concession to streams: an infinitely scrolling page where the newest thing in the database loads first and you can just keep scrolling until you reach the oldest thing. No fidgety controls or taxonomies or navigation. No clicking required.

The fourth view is called Narratives. One possible narrative could be an attempt at explaining an arc in thinking about and making things related to a tagged idea like photography. However, a narrative need not be based on the tags on this site, it could be somebody's point of view. The only requirement is that it should function as a form of navigation into the things on this site. Narratives could take the form of writing, images, transcluding parts of projects, videos, talking, or having somebody else write or talk about it. Most narratives will probably not have endings.

## No Analytics

A final, important conceptual decigsion is to stop collecting analytics on my personal sites entirely. I decided to get rid of analytics after installing [Ghostery](http://hostery.com) and seeing how many sites include upwards of five or ten tracking scripts. When I visit a website and see that Ghostery has nothing to report, it feels like an electric shock of not-giving-a-fuck! There's something a little bit useless and stifling about think of my personal site in terms of numbers. I wasn't really doing anything with the numbers except worrying about them a little. I will miss seeing referrers (who is linking to my website) but I will not miss wondering, in the back of my head, why nobody is visiting my website.

My dream personal website statistics application might collect specific kinds of information. It would ask users if they want to identify themselves with a name and their homepage. It would show them their _own_ tracks across my site as I'm collecting them, and they could leave comments on their trek. Maybe that's a stupid idea. But as far as I know this type of explicit, friendly collection of visitor information doesn't yet exist.

Typekit may embed a kind of analytics for their own purposes but it's not something I have access to.

## Git and Github

Building this site is my first attempt in earnest at using [Git](http://git-scm.com). I will never not use it again! Git changed the way I work, and it also provides a lot of interesting public-facing features.

- You can browse [the source code for this entire website at Github](https://github.com/caseyg/caseyagollan.com). 

- You can see a detailed log of changes to this site by looking at the [commit history](https://github.com/caseyg/caseyagollan.com/commits/master).

- You can browse every version of every single file on this site and [compare revisions](https://github.com/caseyg/caseyagollan.com/commit/21b598146d7480cc98419bfbb2f6bdb304b3b73b#diff-5).

- You can see my [plans for new features and progress squashing bugs](https://github.com/caseyg/caseyagollan.com/issues)

- You can fork this site (make a copy of the entire codebase) and use it as a template for your own site or change a few words and images to make a full-featured parody in five minutes. 

- If you know how to do something better than I do (which is likely) you can submit a pull-request on Github, then I can merge your code into this site with one click.

## Stacey

This site is built with [Stacey](http://staceyapp.com), a content management system built by [Anthony Kolber](http://aestheticallyloyal.com/), that is so wonderfully simple I have not changed my mind about using it for all this site's various incarnations since 2010.

Even though I wanted to treat this iteration of the site more like a database than ever before, the biggest reason I like Stacey is that it uses no database or backend interface. A filesystem _is_ a kind of database. This means that instead of logging in to a web interface (like with Wordpress or Indexhibit) to add new projects or update existing ones, I just throw text files, images, and other media into [neatly organized folders](https://github.com/caseyg/caseyagollan.com/tree/master/content). Stacey slurps up everything in these folders and runs it through [templates](https://github.com/caseyg/caseyagollan.com/tree/master/templates) to spit out a website. Since Stacey's content structure runs off a familiar-old filesystem, nesting of folders makes complex ideas like sub-content and sub-content revisions possible to understand, manage, and execute in a really simple way.

![](http://caseyagollan.com/content/about/finder.png)

I don't like using most web interfaces because I start to obsess over how bloated, ugly, and distracting they are. With Stacey I can just use any text editor. Because my content and templates are just files in folders, I don't feel locked into a particular system. The big databases spun up by sites run on a CMS like Wordpress make me feel like I have no exit (or, a painful one).

## Javascript

This site also represents my first real attempt at writing Javascript. [The file](https://github.com/caseyg/caseyagollan.com/blob/master/public/docs/js/sneezeburg.js) is named after [my dog](https://www.facebook.com/sneezeburg) because he is cute but also ugly. That's a metaphor for something. I am embarrassed by this code. It works (KIND OF) and I want to get better at it over time.

The [Graph](http://caseyagollan.com/graph) is powered by [D3.js](http://d3js.org) by [Mike Bostock](http://bost.ocks.org/mike/). In trying to make an interactive force-directed graph I also dragged myself through experiments with [Arbor.js](http://arborjs.org) by [Christian Swinehart](http://samizdat.cc) whose work I very much admire, [Raphael](http://raphaeljs.com), and [Kinetic.js](http://www.kineticjs.com) before landing on D3.

The [Archive](http://caseyagollan.com/archive) relies on [Isotope](http://isotope.metafizzy.co) by [David Desandro](desandro.com).

## Other Tools

Most of the code was written in [SublimeText](http://www.sublimetext.com) by Jon Skinner with [Solarized](http://ethanschoonover.com/solarized) syntax highlighting designed by Ethan Schoonover. I had [Codekit](http://incident57.com/codekit/) by Bryan Jones running in the background to compile SCSS into CSS, and minify both CSS and JS as I worked. 

## Typography

Fonts are served from [Typekit](https://typekit.com/colophons/tun0rbf). Display text and links are set in Dagny by Örjan Nordling and Göran Söderström, and body text is set in Calluna by Jos Buivenga.

## Fragments of Ideas

- Will I run into a hairball problem with the graph? It's already apparent on small screens that too many nodes are hard to visualize.
- I'd like the try other configurations of the Graph. Dorian Taylor has written down some [wonderful ideas about information architecture and graph theory](http://doriantaylor.com/navigation-by-shibboleth) that I'd like to explore.
- How far back can I go with what is archive on this site? The earliest work on this site is some photography that might've been made at age 13. Should I include a book I made in second grade? Is that obnoxious? Irrelevant? When did I start _working_? When do I get to retire?