# Think Again

This started out as a list of random ideas mostly copied from various Slack and Discord discussions I was having at the time.

I wanted to record said list in a public place like a blog post so that others could also draw from it but I don't blog on my [personal site](https://chopfitzroy.online/) and given I wanted this to be more of a _living document_ as opposed to a snapshot in time I decided a dedicated site would be better.

With all that in mind what is _Think Again_? If you had to give it a name I guess it's a manifesto in the sense that it is a call for change or at the very least a call for us (and our industry) to see reason.

### Premise

Over the last few years we've seen explosive growth in LLM usage and capabilities, many industries have folded these new tools into their workflows / offerings but none quite as agressively as the tech industry.

LLM's are no doubt useful and this document doesn't exist to try and convince you otherwise, in fact most arguments in this document assume that 100% of the time an LLM can generate code as good or better than a human and yet there are still compelling arguments to be made.

This document posits that the discourse surrounding the use of LLM's in software engineering is fundamentally flawed in the sense that almost all arguments are presented as though LLM's provide a net positive impact in terms of velocity / output at little to no cost outside of the tokens themselves.

The reason this argument is false or at least misleading is it that it fails to ever factor in **understanding** and by understanding we mean the ability for an engineer to reason about the software at a deep level. When we talk about understanding we are not talking about high level abstractions or architectural diagrams we are talking about the _in the weeds_ parts of your software that actually perform logic and deliver results.

### Why write code?

If the above argument is entirely predicated on needing to understand the software we work with surely we can achieve that understanding without writing code?

I see this argument presented somewhat frequently and I think it's totally valid, unfortunately in my own experience I've not found a better mechanism for gaining a deep understanding of the problem space and minutiae without writing the code myself. It just so happens the explicit nature of authoring code is often a brilliant way to calcify ones own understanding.

Supplementary to this the individuals I have often seen touting this argument (some of whom I've worked with) in practice have shown a moderate to severe lack of understanding when any real pressure is applied. I'm not saying that my own experience is indicitive of the entire industry but it has certainly solidified my view.

### Common arguments against

- We don't need to understand? - If so how to we reduce entropy?
- I understand the code at a high level - We don't ship high level concepts to the user we ship bytes and we better know exactly what they are doing not what the _should_ be doing
- LLM's don't care about tech debt? - Are you willing to bet your entire product on their being no upper bound to the complexity they can handle?
- The models will keep getting better? - Will they?
- Who's going to be there when the shit hits the fan - **I think this one is a logical fallacy**

### Common arguments for (with proof)

- Link studies
- Do you want to be hiring your skills from a 3rd party?
- The fuzzy feeling, trust instead of validating, uninformed choices and falling back to recommended
- If we know there is a _ramp up_ period when hiring senior engineers and we don't expect them to be a real _force multiplier_ until they have an understanding of the system then how do we expect these engineers to ever provide real value if we keep them stuck at day zero.

### Can we still value?

- LLM's are execellent at lots of parts of the SDLC I would just argue code generation is not one of those parts
- Duplicating existing / similar logic we've recently authored (appropriate time for us to review)
- Invalidate, challenge, review

### What about bottlenecks?

I don't really think code was ever the bottleneck despite what some people say.

[Friction = focus & focus = product](https://thoughts.hmmz.org/2026-05-31.html)

### Is it ego?

- [Weird takes](https://x.com/ryanflorence/status/2102849480760721664)
- Mourning our craft (should we?)

### Where to next?

- Creators
- Communities
- Workflow changes
