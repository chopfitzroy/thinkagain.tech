# Think Again

This started out as a list of random ideas mostly copied from various Slack and Discord discussions I was having at the time.

I wanted to record said list in a public place like a blog post so that others could also draw from it but I don't blog on my [personal site](https://chopfitzroy.online/) and given I wanted this to be more of a _living document_ as opposed to a snapshot in time I decided a dedicated site would be better.

With all that in mind what the fuck is this? If you had to give it a name I guess it's a manifesto in the sense that it is a call for change or at the very least a call for us (and our industry) to see reason.

### Understanding software

Over the last few years we've seen explosive growth in LLM usage and capabilities, many industries have folded these new tools into their workflows / offerings but none quite as agressively as the tech industry. LLM's are no doubt useful and this document doesn't exist to try and convince you otherwise.

This document posits that the discourse surrounding the use of LLM's in software engineering is fundamentally flawed in the sense that almost all arguments are presented as though LLM's provide a net positive impact in terms of velocity / output at little to no cost outside of the tokens themselves.

The reason this argument is false or at least misleading is it that it fails to ever factor in **understanding** or **complexity**.

By understanding we mean the ability for an engineer to reason about the software at a deep level. When we talk about understanding we are not talking about high level abstractions or architectural diagrams we are talking about the _in the weeds_ parts of your software that actually perform logic and deliver results.

By complexity we mean the ability to reason about a piece of software of a long time horizon, in other words what are the long term impacts of LLM assisted code _after_ it's been written and deployed.

### Writing software

If the above argument is largely predicated on engineers needing to understand the software we work with surely we can achieve that understanding without writing code?

I see this argument presented somewhat frequently and I think it's valid, unfortunately in my own experience I've not found a better mechanism for gaining a deep understanding of the problem space and minutiae than writing code. It just so happens the explicit nature of authoring code is often a brilliant way to calcify ones own understanding.

Supplementary to this the individuals I have often seen touting this argument (some of whom I've worked with) in practice have shown a moderate to severe lack of understanding of code they have not authored themselves. I'm not saying that my own experience is indicitive of the entire industry but it has certainly solidified my view.

### Mainting software

- [Dex on refactoring/abstraction as part of training data](https://x.com/dexhorthy/status/2080697380379427275)
- [Steve Yegge on the complexity ceiling and LLMs](https://x.com/Steve_Yegge/status/2094947586373505122)

### Ego and software

- [Weird takes](https://x.com/ryanflorence/status/2102849480760721664)
- Mourning our craft (should we?)
- LLM's don't care about tech debt? - Are you willing to bet your entire product on their being no upper bound to the complexity they can handle?

### Common arguments against (FOLD IN TO ABOVE SECTIONS)

- We don't need to understand? - If so how to we reduce entropy?
- I understand the code at a high level - We don't ship high level concepts to the user we ship bytes and we better know exactly what they are doing not what the _should_ be doing
- The models will keep getting better? - Will they?
- Who's going to be there when the shit hits the fan - **I think this one is a logical fallacy**
- Code as the bottleneck - think this is about framing ([Friction = focus & focus = product](https://thoughts.hmmz.org/2026-05-31.html))

### Common arguments for (with proof) (FOLD IN TO ABOVE SECTIONS)

- Link studies
- Do you want to be hiring your skills from a 3rd party?
- If we know there is a _ramp up_ period when hiring senior engineers and we don't expect them to be a real _force multiplier_ until they have an understanding of the system then how do we expect these engineers to ever provide real value if we keep them stuck at day zero.

### So what value do LLM's offer

It's no secret that LLM's are terrific at finding exploits and bugs, a core contributor to Postgres recently published [Postgres 19 is late, and it's AI's fault](https://rhaas.blogspot.com/2026/10/postgres-19-is-late-and-its-ais-fault.html) which talks about how many bugs the team have been able to surface ahead of release thanks to LLM's.

I truly believe LLM's are **far better at breaking that building** and that we would be far better off leveraging their effectively unmatched ability to uncover vulnerabilities to improve the software development life-cycle as opposed to using them to generate swathes of code.

Invalidate, challenge, review - talk about the ability for an engineer to only truly be able to reason about suggested changes/improvements if the engineer already understands the underlying implementation - otherwise we just end up going with the _recommended_ option.

### Nuance and grey areas

- Duplicating existing / similar logic we've recently authored (appropriate time for us to review)



