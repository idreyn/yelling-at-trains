---
title: "The carbon calculus of high-speed rail"
date: 2019-03-27T20:51:21-08:00
draft: true
hidden: true
---

For a few weeks each year, often coinciding with the latest climate accords, emergency summit, or wildfire, the United States collectively kicks around the idea of saving the planet. In early 2019 this idea is once again having a moment thanks to a group of climate activists organizing around the idea of a Green New Deal to push the economy towards carbon-neutrality. As it stands, the GND is barely the shadow of a full-fledged proposal. While it has a long way to go before it can be massaged by Congress into a set of tax breaks for mildly repentant oil companies and eventually passed into law, it's refreshing to see folks in government proposing solutions that at least acknowledge the scale of the problem.

<figure class="img">
    <img src="/images/mike-lee.png" alt="Senator Mike Lee pointing at a picture of Aquaman riding an enormous seahorse"/>
    <figcaption>
        <a href="https://twitter.com/_waleedshahid/status/1110580141493755904">Some of them, anyway
        </a>
    </figcaption>
</figure>

As usual, transportation emissions are at the forefront of the conversation -- maybe because seeing exhaust from our tailpipes is one of the few times we actually watch ourselves directly add carbon to the atmosphere, or because transportation accounts for 28.1% of the United States' energy usage. At any rate, there's a word cloud floating above the National Conversation here where the two biggest words are "green" and "transportation" and a slightly smaller one hanging under it is "high speed rail". HSR has been in and out of the news recently -- first, because [the governor of California admitted that the state doesn't have enough funds to finish their LA-to-SF system](https://sf.curbed.com/2019/2/12/18222279/governor-gavin-newsom-high-speed-rail-canceled-california) as its budget trends north of $75 billion. Second, in direct connection with the Green New Deal; a staffer hammered out in a leaked press release that the plan was to build enough high speed rail to make air travel unnecessary, which resulted in about 2,000 Mensa guys tweeting at @AOC that, actually, Hawaii is an island.

Not to give them too much credit, but the point sort of stands; the United States is too big for HSR to compete with our longer-distance domestic air routes. But at scales from a few hours' drive to perhaps NYC-Chicago, it's a tantalizing alternative to either a long drive, or a short flight buttressed by hours of airport-related purgatory. Slow-motion failure in California notwithstanding, if progressives ever manage to take control of the government again, there will eventually be proposals to allocate money towards HSR as a centerpiece of transportation climate policy. As someone who is occasionally introduced at parties as "the trains guy", I'm all over that. But as someone who wants to see GND money allocated in cost-effective ways, it gives me pause for thought. Time to dig into the emissions benefits of high speed rail.

## The part where we do math

The California High Speed Rail project is the ~~best~~ only example of a high speed rail project in the US, so I'm going to use it to get a sense of what kind of emissions benefits this kind of system has. There are good reasons to build a high-speed train that have nothing to do with the environment, but for our purposes I'm only interested in seeing how much less CO<sub>2</sub> the human race is expected to emit because of the project. There is no straightforward answer to this question because no one knows exactly how many riders the system will have. The state's estimate is around 29 million -- [some people at Berkeley think that's a little high](https://its.berkeley.edu/news/its/2010/07/01), but for argument's sake let's run with it and see how far we get. After hours of digging around in government document archives, I found [some spreadsheets](http://calhsr.com/resources/ridership-forecast/) that list ridership projections between each area of California served by CAHSR. Here I've adapted the Phase 1 spreadsheet, corresponding to segment of track from LA to SF. I changed the location names to be human-readable, and calculated the estimated CO<sub>2</sub> savings from high-speed rail, as shown below:

<iframe class="big-iframe" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTSjiFE3oIPsmnQlBeS0EXJfISqOH5f0DRoIAYd8iueA9Gua2ClxytqF_boivxscAWbf_Rd5L-hhwLI/pubhtml?widget=true&amp;headers=false" class=></iframe>

It's easy to get lost in the sauce of these numbers, so let's do a very simple baseline calculation to see what kind of order of magnitude we expect. The distance from Los Angeles to San Francisco is about 380 miles[^1]. A single mile of driving in an average car emits 0.36kg of CO<sub>2</sub>. Multiply `380 mi * 0.36 (kg / mi) * 29 million / (1000 kg / 1 metric ton)` and you get about 4 million tons of CO<sub>2</sub> diverted per year by HSR. So we expect something in that order of magnitude, though probably lower once we accounts for the fact that some cars have multiple people in them, and the actual origin-destination pairs. In fact, the all-knowing spreadsheet spits out **1.6 million tons of CO<sub>2</sub>** per year diverted from high-speed rail[^2].

Of course, operating an electric train is not carbon-free if we're burning carbon to produce the electricity. We can get a vague sense of the CO<sub>2</sub> burden of CAHSR by piecing together the following clues:

- HSR trains in China consume only (?) 3.8 kilowatt-hours per 100 passenger-km [(source)](http://en.people.cn/n3/2017/0929/c90000-9275504.html)
- I was pleasantly surprised to learn that California [only gets 38% of its electricity by burning carbon-based fuel](https://www.energy.ca.gov/almanac/electricity_data/total_system_power.html). Let's optimistically say that this number is 25% in about 10-15 years when Phase 1 is finally complete.
- The bulk of that fuel is natural gas. Producing one million _(rubs temples)_ British thermal units of energy from natural gas [burns about 53kg of CO<sub>2</sub>](https://www.eia.gov/environment/emissions/co2_vol_mass.php).

This is giving me terrible flashbacks to AP chemistry and dimensional analysis, but luckily Wolfram Alpha has only gotten better since those days, and [it tells me](https://www.wolframalpha.com/input/?i=0.25+*+29+million+passengers++*+(3.8kwh+%2F+(passenger+*+100+kilometer))+*+(380+miles)+*+(53+kg+CO2+%2F+1e6+BTU)) that all of this crunches out to about **30,000 tons of CO<sub>2</sub>** per year to run all of these trains, which is less than 2% of the total CO<sub>2</sub> diversion we calculated above. Not bad at all!

Unfortunately, we have yet to account for the emissions cost of actually building the rail link. Willing 380 miles of train into existence involves big concrete viaducts, literally blowing up mountains, and all sorts of other carbon-intensive work. It's far beyond my ability to do this kind of analysis, but luckily it's someone's job -- specifically Messrs. Jonas Westin and Per Kågeson, who produced [a paper](https://doi.org/10.1016/j.trd.2011.09.006) that modeled CAHSR fairly closely in terms of length and construction criteria. [A CityLab article about their findings is available here](https://www.citylab.com/transportation/2011/11/how-green-high-speed-rail/492/), but I have jumped the paywall for you and retrieved this somewhat grim figure:

<figure class="img">
    <img src="/images/hsr-offset.png" alt="A graph titled 'High diversion from cars and buses'. The x-axis is labeled 'Million trips required to compensate for embedded emissions each year'. The y-axis is labeled 'probability'. The graph shows a probability distribution, skewed moderately right with a mean at around 17 million."/>
</figure>

What this image tells us is that a high-speed rail system like CAHSR needs to serve around 15 million yearly passengers, and probably more, to even offset the carbon cost of its construction[^3]. That's about half of the 29 million passenger estimate! The error bars on all of these numbers are pretty big -- and I'm fortunate that I'm not being paid to write this or I'd probably have to tell you how big -- so let's just keep it simple. The ridership model predicts about 1.6 million tons of CO<sub>2</sub> diversion. We know the cost of building and running HSR will eat about half of that. I'm pretty comfortable saying that **the net carbon savings offered by CAHSR is 500,000 to 1 million tons of CO<sub>2</sub> per year**. And I'm astounded to report that my bullshitting up to this point [tracks pretty well with the number suggested for a similar system in Sweden](https://doi.org/10.1016/j.trd.2010.12.004).

## The part where we add context

500,000 tons is an incomprehensibly huge number. For my part, I've been going to the gym for a while and I'm almost certain I wouldn't be able to bench that. And yet -- [time to take a big sip of coffee and look up the United States' total CO<sub>2</sub> emissions from transportation](https://nepis.epa.gov/Exe/ZyPDF.cgi?Dockey=P100USI5.pdf).

_**1.85 billion tons?**_



Air travel is not good for the environment, but there's no viable alternative to the energy density of carbon-based jet fuel without breakthrough battery technology (or someone building a nuclear-powered plane). So long as we hurdle ourselves across the globe in pretzel-filled aluminum tubes, we're going to do so by adding carbon dioxide to the atmosphere for the forseeable future. Thus, air travel receives lots of attention every time we collectively consider saving our planet for a few weeks. But should it?

Airplanes are to the atmosphere what hookah is to your lungs, and finding out what a single cross-country flight does to your carbon footprint is like being told that you just smoked the equivalent of like a hundred cigarettes on your trip through the back room. That makes air travel an 

Listen, I love trains. Occasionally, and to my great chagrin, I am introduced at parties as "the trains guy".

It was once said that nuclear power in America would be "too cheap to meter" -- that power plants going online would quickly blanket the country in abundant, carbon-free electricity. Today, we've fallen far short of that world, and the United States gets around 8.5% of its energy from nuclear fission, compared to about 28% from natural gas.

The point to stress here is not that high-speed rail is bad. I actually think trains are really good and in fact I run a little blog about them. But a serious rail network is

 To address our carbon appetite in this category, the GND proposal suggests:

1. zero-emission vehicle infrastructure and manufacturing
2. clean, affordable, and accessible public transit
3. **high-speed rail**

While there are lots of benefits of high-speed rail unrelated to the carbon savings, I was curious how it stands up as a carbon-mitigation investment, specifically. After all, even a Green New Deal would be spending a finite amount of money, and it makes sense to choose investments that:

- Are actually effective in reducing our carbon emissions
- Accrue benefits sooner rather than later
- Enjoy popular support

The first point is sort of self-evident -- this is not a political game, no matter how often it seems to be; at the end of the day we actually do need to level off and then reduce our carbon emissions, or face irreversible damage to the biosphere and trillions of dollars in lost economic productivity. The second is both practical and political; we want to start seeing results soon, both to avoid triggering cascading natural disasters and to generate continued support for environmental programs. The third point _is_ political; all else being equal, it pays to pick the carbon mitigation strategies that contribute to quality of life in more than one way -- otherwise the No Hot Showers For Anyone Party would be taking Congress by storm.

The other galaxy-brained point that I want to make here is simply that the United States is extremely big, which affects our living and travel patterns at many scales. From the regularity of cross-country airline travel to the massive sprawl of many of our cities, the embiggenment of this nation has given us lots of room to spread out, and thus lots of miles to travel in the course of our lives.

[^1]: Coincidentally it's the same in the opposite direction as well.

[^2]: This model doesn't account for the 2% of trips including an "OTHER" destination that I wasn't really able to guess a travel distance for, so the number might be, roughly speaking, about 2% higher. It _also_ doesn't account for the "last leg" of trips involving Sacramento and San Diego, which in this model don't have their own stations yet, so we lose some savings back to car (or ideally, bus) travel to reach these final destinations until the HSR segments connecting these cities directly come online.

[^3]: Over the next 50 years.