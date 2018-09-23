---
title: "The Optimist's Guide to the Caltrain"
date: 2018-07-30T08:15:01-07:00
draft: false
---

I have something of a love/hate relationship with my current home in the Bay Area, and in particular the Caltrain, the commuter rail line that carries XX,000 passengers daily between San Francisco and Silicon Valley. As the only extant rail link between these two great symbols of man's hubris, the system is an indispensable alternative to the 101 freeway, which during the morning is a soup of Google shuttle buses and too-clever-by-half Teslas algorithmically jockeying for open lanes. I take Caltrain on my absurd 35-mile commute from San Francisco to Mountain View, and while I probably enjoy the experience of just being on a train more than the average person, I mostly now see it as both a growing source of back pain and as as mere shadow of what I hope the service can become. This post is the story of how the Bay Area might just accidentally invent the most modern and comfortable regional rail service in America, transforming Silicon Valley into a more urban, livable place in the process -- and what you, esteemed Caltrain rider, can help do to make that happen.

I'm writing this from a standing-room-only Caltrain car _jam packed_ with people dumped off at Milbrae, the lone transfer point between the Caltrain and BART. Though it operates on a geographic scale similar to BART which features relatively frequent all-day service and has subway-style cars, Caltrain is a commuter system through and through, with large comfortable seats and most of its service concentrated within peak commuting hours. Complaining about Caltrain is the national pastime of the country Silicon Valley will be when California accidentally votes to secede _and_ split itself into five states in 2020, but the experience of riding it is pretty pleasant, and its shortcomings are most apparent in aspects where it's become a victim of its own success.

<figure class="img">
    <img src="/images/caltrain-worth-it.png" alt="An image from the CalMod website that says: Change is coming; the future is worth it."/>
    <figcaption>
        Caltrain is feeling some kind of way about their new electric fleet, due to start service in 2022.
    </figcaption>
</figure>

Ridership on Caltrain has more than doubled in the past ten years, and as standing-room-only becomes the norm at peak hours, its weary, twentieth-century bones are starting to show. The trains are powered by diesel locomotives which are actually sometimes mistaken for small earthquakes by new employees at my office near the tracks -- loud, lurching, and slow to accelerate. The line has XX _grade crossings_ where it interacts with traffic at street level. And unlike BART, it doesn't have level boarding platforms, which means that you have to ascend stairs to get on the trains. All of these things limit the speed of the trains and the number that can be run per hour, capping the number of people -- and the kinds of trips -- that the system is useful for. Thankfully, Caltrain is about to undergo a series of major upgrades, which I'm going to break down in this post. Some of them are bought and paid for, some are in various stages of planning, and some are contingent on California High Speed Rail (CASHR) due to open service between SF and LA roughly when we start prepending years with "stardate".

<figure class="img">
    <img src="/images/picard.png" alt="Jean-Luc Picard in Star Trek: TNG."/>
    <figcaption>
        "Stardate 4254.7: Slack was down again and we got delayed at Millbrae, so I listened to an audiobook for five minutes and then started an argument about Kubernetes on Hacker News."
    </figcaption>
</figure>

The relationships between these improvements are sometimes complicated; my hope is that if you stick with me here, you'll leave better understanding what each kind of improvement to rail service means in human terms, how they work together, and why they matter. If you're a Caltrain commuter, and reading this on the Caltrain, whoa, meta, come say hi! I take the 8:45 from 4th and King and try to get a second-floor window seat.

With that, let's jump into the "big one" for Caltrain: fleet electrification.

## Danger! High Voltage!

If you're looking to blow an entire afternoon, you should check out the whole subgenre of YouTube videos of electric car owners (including [Electric Car Owner Number One](https://www.theonion.com/literally-no-one-calls-me-that-or-has-ever-called-me-t-1819592848)) demonstrating how their cars' induction motors blow the zero-to-sixty of traditional internal combustion engines out of the water. This neat (and probably dangerous) quirk of EVs turns out to be the primary benefit of electric _trains_ over their diesel-guzzling brethren. Faster acceleration means it's possible for trains to spend more time at their maximum allowed speed, which is particularly important when you make as many stops -- XX! -- as your local Caltrain does. [While it's possible that electricty was known to the ancient Persians](https://en.wikipedia.org/wiki/Baghdad_Battery), American commuter railways have with relatively few exceptions failed to catch on to this mysterious phenomenon as a means of train propulsion. In Caltrain's case, buying electric trains from Europe required a special waiver from the Federal Railroad Administration since running these lighter, less crash-resistant trains on tracks shared with freight rail is considered dangerous by the federal government (hold that thought). But we did it! 96 Stadler KISS Electric Multiple Unit (EMU) cars are bought and paid for, with the option to buy another 96 later (uh, could you hold that thought too? thanks).

The downside of theses EMUs is that, surprisingly, they don't have as much seating capacity as any of the existing Caltrain cars. These bad boys are individually self-propelling, so quite a bit of interior space in each car previously available for seating is used for electrical traction components. Oh no, right? Well, the boys in the lab tell me there are two solutions available to you to solve this problem: run more trains and, ah, (shuffling paper) run longer trains. With the arrival of the new trains, Caltrain will begin running six trains per hour per direction instead of five, which will more or less obviate the seat deficit. But this underscores an important point: electrification on its own is not a solution to Caltrain's capacity constraint.

## Positive train control

Remember that thought I told you to hold? No, the other one, about the FRA waiver. Great, so abouuut that -- there's a condition to that waiver I didn't tell you about. Bear with me here: the problem with trains is that they're big, and once they start moving, they're hard to stop. So -- and I know that this might seem controversial, but again, bear with me -- we don't want them to crash into each other. Just like

- Oh god something about PTC
- Full fare integration with BART

And before we dive into the technical details, let's keep in mind why any of this should matter to the 99% of people who don't normally get a kick out of reading about their commute on their commute. For better or worse, the peninsula stretching from San Francisco to San Jose is one of the wealthiest and most economically productive places in the world. No one planned for this, but the advent of the semiconductor occured during a time when it seemed reasonable, even utopian, to build sprawling corporate campuses accessible primarily by freeway travel. The alienating, insular ethos of consumer technology, increasingly exported into our daily lives by the likes of Uber and Facebook, seems to reflect the built environment of the Valley itself. Living here day to day, I am often struck by how unsustainable it all seems -- the fantastic opulence and technical expertise siloed up in towers of sheer indifference towards solving the basic problems of housing and transportation in the communities used as a substrate. Anything that can make this place feel more connected, accessible, equitable -- more like a _place_ -- to me increasingly seems like an investment in not just the Bay Area, but everywhere that lies in the long shadows of Apple and Google's walled gardens.

Jesus, I need another coffee. Anyway, we were talking about trains, right?

[^1]: Please bring this solution to the MTA to receive your "Genius Grant".