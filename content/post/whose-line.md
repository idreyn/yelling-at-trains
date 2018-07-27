---
title: "Whose line is it, anyway?"
date: 2018-06-05T08:49:58-07:00
draft: false
---

Oof! A housing project — maybe a tower, some condos, or a whole new neighborhood, is in the news. Proponents are excited at the chance to add more housing (near a new transit line, no less!) that will help address the region's ballooning rent prices. Detractors are worried that the project will cause rents to skyrocket in the area, displacing the current residents. Who's right? Mathematically, at least, there's no reason they both can't be. To illustrate this I've created a little visualization below. We've just added eight new units of housing near a transit line in idyllic, uh, Trainsville. What effect do they have on housing prices? At what scales? Resize the radius of interest and see for yourself, and keep this simple demonstration in mind as you read.

<div class="density-sim-container">
    <iframe class="density-sim" src="/density-sim/build/index.html"></iframe>
</div>

In California, we've been having this conversation for a while. In January 2018, state senator Scott Weiner introduced SB 827, a bill that aimed to address the state's alarming housing shortage by legalizing the construction of higher-density housing _wherever there is a nearby transit line_, superseding local zoning codes. Had the bill passed, almost the entirety of San Francisco, along with large swathes of the greater Bay Area and Los Angeles, could have become home to eight-story apartment buildings (later reduced to five), constructed without minimum parking requirements. While the bill as written frankly never stood a chance and died a quiet death surrounded by loved ones in commitee, it highlighted a diversity in pro-housing viewpoints that we should better understand before attempting to try again.

Supporters predictably included the market-friendly YIMBY ("Yes In My Backyard") group and a whole bunch[^1] of urban planning professors. Perhaps surprsingly, there were also some vocal detractors from the left, most notably LA's chapter of the Democratic Socialists of America (DSA), who voiced their opposition in a comprehensive critique of the bill. They identified the ways in which market-oriented approaches to housing development like SB 827 at best treat the specific needs of poor and working-class communities as an afterthought, and at worst can displace these communities to make way for expensive developments. Deep in this analysis is a statement that I'd like to highlight:

> We must have a more nuanced understanding of housing markets and move past the inaccurate belief that "more supply of any kind leads to lower prices." There are different spatial scales we must consider. **Development in a particular neighborhood could marginally bring down prices across the region while sharply increasing rents and risk of displacement in the areas immediately surrounding.**

I have a sense that more awareness of this fact during conversations about the housing crisis would lead to less disagreement, or perhaps clearer agreement on what we're disagreeing on. And who's _we_ anyway? For those of you new to the sport of full-contact California housing advocacy, here's the score:

- **Center-left groups** like YIMBY focus on the housing crisis through a regional, market-oriented lens, advocating for more permittive zoning regulations and shouting down homeowners who don't want _anything_ built that might cast shade on their petunias. This group hopes to leverage supply and demand, as well as negotiation with private developers, to make housing more affordable.

- **Leftist groups** like DSA take a, well, socialist view of the problem at a local, neighborhood level, fighting for better rent control[^2], and brand new tenant protection measures like [right-to-counsel](https://ballotpedia.org/San_Francisco,_California,_Proposition_F,_City-Funded_Legal_Representation_for_Tenants_Facing_Eviction_(June_2018)). The DSA is _very_ reluctant to show support for market-driven housing development, preferring to advocate for public housing wherever possible, [though the pace of its construction locally remains absymally slow](https://www.sfchronicle.com/news/article/SF-educators-still-waiting-for-promised-teacher-10929900.php).

Both camps advocate using different tools to solve different problems at different scales, and I think they're actually using the _right_ tools for each job. My hope is that in the coming years, an SB 827-like bill that both camps are satisfied with can gain broad support _among_ housing activists, and ultimately make a big dent in a state that desparately needs to move past ownership of single-family homes.

<figure class="img">
    <img src="/images/atheists.png" alt="XKCD #774"/>
    <figcaption>
        Oof ouch owie my whole blog.
    </figcaption>
</figure>

## Here Comes the Neighborhood!

The best rapid transit plan is a good land use plan, which is to say that it’s easiest to build transit in walkable, urban places. In America, though, transit lines are often built across sprawling metropolises, running through neighborhoods full of single-family homes from downtown to the airport or the hellmall or whatever. In an effort to kickstart a walkable neighborhood in these places, dense housing and retail developments are often planned near these intermediate stations — a strategy we call _Transit Oriented Development_ or TOD. For some transit projects, TOD is a value-add; for others, it borders on being the justification for building the whole thing. Regardless, American TOD tends to look out of place in its larger context. It usually consists of apartment buildings in a modern “cookie cutter” glass and aluminum style that everyone seems to hate, with new retail catering to the kind of professional who you’d expect to live there. Because TOD usually relies on an exception to the local zoning code, it’s also built markedly taller than the surrounding blocks.

<figure class="img">
    <img src="/images/assembly-square.png" alt="A modern-looking apartment building in Assembly Square"/>
    <figcaption>
       This is Assembly Square just outside of Boston -- a few acres of dense housing that sprang out of nowhere alongside the Assembly Orange Line station in 2014. Walking around TOD like this can feel like living inside an architectural render.  <a href="https://boston.curbed.com/2017/1/12/14255580/assembly-row-somerville-guide">(source)</a>
    </figcaption>
</figure>

Even when thoughtfully integrated into an existing neighborhood, TOD tends to smell like the end of affordability in an area, much like goat yoga studios, driftwood jewelry boutiques, and a food critic gingerly dispatched by the local paper to declare the area safe and "desirable" for white people. Because of the sheer number of shiny new units that it brings, TOD can easily raise the average price of an apartment in a neighborhood. At its worst, TOD is the physical embodiement of the strawman that wantonly displaces a whole neighborhood full of "regular" people to make room for young professionals who kinda want to take the train sometimes.

The fear that new development near transit is ultimately displacing people who _need_ transit to make room for people who _like_ transit is a growing concern. [A widely-circulated LA times story from early 2018](http://www.latimes.com/opinion/op-ed/la-oe-rosenthal-transit-gentrification-metro-ridership-20180220-story.html) even linked developments along LA's Purple and Expo lines, and correlated increases in adjacent real estate, to falling ridership on Metro. The people who can actually afford to live near the train are, paradoxically, the ones least likely to make full use of it. In transit industry jargon, these are "choice riders" -- ones who consider transit an amenity in the same vein as a nearby Equinox club. They'll use it when it's convenient, but certainly don't depend on it, and will probably opt for Uber or Lyft before transferring to a bus.

{{<figure src="/images/todd.png" caption="Pictured: Todd near Los Angeles' Red Line (I'm not sorry)">}}

Transit isn't built _for_ any demographic in particular. At the same time, deploying transit in a way that is predictably going to drive people out of their homes seems to more than defeat its purpose. We want everyone to want to use transit, but we should also recognize that the marginal utility of living near a rapid transit station for someone who is going to use it every day is greater than for someone who views it as an amenity that will help them beat traffic twice a year on their way to the Big Game. Without understanding and managing the interaction between transit and displacement, we run the risk of replicating in our cities the problems that plague transit in the suburbs: low ridership causing funding cuts causing low ridership in a death spiral that limits everyone’s mobility, but disproportionately so the working class.

## A different story at a different scale

This story of gentrification has birthed a thousand SF open-mic jokes and has a _Guess Who?_ board of classic characters: the yuppie artists, garage coffee shop proprietors, luxury housing developers, and corrupt aldermen whose machinations turn a neighborhood with a century of history into a souless nowhere. But as a lens for understanding why entire metropolitan areas in San Francisco, Boston, Seattle, and New York are so expensive, it puts the cart before the horse (or, uh, the pedicab before the white guy with dreads).

These cities are adding jobs much faster than they're building housing -- [in San Francisco it's something like six new jobs for every one new unit of housing](https://www.bloomberg.com/news/articles/2017-06-23/why-can-t-they-build-more-homes-where-the-jobs-are). Simply put, there isn't a home in the city for everyone who wants to work there. Not even close [^3]. So the radius of what constitutes an acceptable commute expands, far outside the city and even past the reaches of the lengthy, if sparse, BART lines that extend through the East Bay. People working minimum-wage jobs in San Francisco (you know, where the jobs actually are) are spending [three hours one-way](https://www.nytimes.com/2017/08/17/business/economy/san-francisco-commute.html) just to get to their jobs via transit.

From this regional perspective, building more housing near transit in urban areas isn't just making room for more people; it's righting a historic wrong. American cities, San Francisco foremost among them, face displacement of people of color and the working class in part because most homeowners (and thus many landlords) are the middle-class white families who were able to purchase homes before renewed investment in cities caused real estate values to skyrocket. We no longer have the [redlining policies](https://en.wikipedia.org/wiki/Redlining) that denied home loans in certain areas to nonwhite people, but we now have homeowners' associations and neighborhood associations hell-bent on preserving the "character" of neighborhoods by keeping out dense multi-family housing that might slow the ballooning of their property values.

Zoomed out at this level, _inaction_, not development, appears as the obvious driver of displacement. When it's normal for people across all income levels travel an hour each way to work, _the_ primary amenity of a neighborhood becomes the promise of a reasonable commute. Neighborhoods along transit lines and near freeways, once avoided by those with the means to do so, become more attractive and even their old and decrepit housing stock becomes very expensive. Barring a regional or national economic collapse, the influx of people into cities will continue, and the reasonable thing to do seems to be to accomodate them, not make them fight for a fixed number of units, rent-controlled or not. This means building more housing and more transit at a pace that has all but disappeared from America's living memory.

## Building transit without tearing down communities

Neither of these stories of how development and displacement are related is _wrong_, and we need to hear and understand them both to fully grasp the extent of the problem. They describe two very different dimensions of affordability and make compelling arguments by focusing on the effects within a larger or smaller radius. At a local level, tenant protections like rent control and right-to-counsel can make an enormous difference in ensuring that the current residents of a neighborhood can continue to live there as the city changes around them. Knowing that housing prices are projected to dip in a decade or so is very cold comfort to someone who is being priced out of their own neighborhood this year because a light rail line is opening. But at the same time, _cities change and grow_, and wishing that time would pass your city by is both fruitless and a terrible curse in its own right.

### Understand the true extent of the problem!

### Build out the missing middle!

### Make a plan!


Astute and perhaps possibly very mad readers will note that I conveniently ignored the question of whether "more supply of any kind leads to lower prices"

FILTERING MY DUDE

[^1]: A "correlation" of urban planning professors? a "metropolitan statistical area"?

[^2]: The big thing to do on this front in California is repealing Costa-Hawkins (expound)

[^3]: Heartbreakingly, there actually is a vacant apartment for every homeless person in San Francisco. Unfortunately, if we seized all vacant apartments in the city, we'd quickly be back in the same situation we're in now because of induced demand; we don't _just_ need better redistribution, we need more of a very valuable resource.