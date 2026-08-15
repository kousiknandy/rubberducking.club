---
layout: page
permalink: /about/
title: About
description: Why capable engineers lose system design rounds on a technicality of their own making, and the five rules a deliberately unhelpful duck holds itself to.
---

## Where this came from

I've watched a lot of capable engineers walk into system design rounds and lose on a technicality of their own making.

Not through ignorance. They'd done the reading, they knew the components, they could recite the CAP theorem with the weary air of someone who has recited it before. What sank them was single-tracking: choosing a design early, becoming fond of it, and spending the rest of the hour protecting it from the interviewer rather than pressure-testing it out loud. When the trade-off question finally arrived — *what happens when this region goes down?* — they defended instead of thinking. Defence looks identical to rigidity from the other side of the table, and rigidity is the one thing that round is specifically built to detect.

The odd part is that most of them knew the answer. They just hadn't practised finding it in front of anybody.

## Why the existing option doesn't fix it

Paid mock interviews exist and some are excellent. They also cost real money and are deliberately adversarial, which produces a predictable outcome: people save them for when they feel prepared.

Nobody feels prepared. So the booking slides by a week, then a fortnight, and the first genuine adversarial system design conversation of their life happens at a company they actually wanted to work for. The expensive thing gets rationed into uselessness, and the free thing — a stranger who'll let you flail harmlessly for forty-five minutes — doesn't exist.

That's the gap. It isn't a market gap, it's a stakes gap.

## The method, such as it is

The rule I hold myself to is that I never supply the conflict. I only point at where it already is.

- **Interrupt rarely.** Perhaps every ten minutes. Constant questioning turns into an interrogation, and you start performing for me instead of thinking.
- **Ask about the thing you said quickly.** Every design contains one sentence delivered faster and quieter than the rest. That sentence is load-bearing and you know it.
- **Never accept "obviously".** Especially not as a step. Particularly not as a step you're clearly relieved to have got past.
- **Advocate for the devil even when the devil is losing.** Correct answers get the same raised eyebrow as wrong ones. You must not be able to read your score off my face — that's not available on Thursday either.
- **Refuse to be the expert.** The moment I start explaining, you stop reasoning and start taking notes. Notes are useless to you. You cannot read notes aloud in an interview.

The intended outcome is that you talk yourself out of a bad decision, or into a good one you can now defend in a sentence. Either way it was yours, which means it'll still be there under pressure. Advice evaporates the moment somebody frowns at it.

## The pretentious bit

The domain says *maieutic* because that's the actual name for this, and I'd rather use the real word once than a management-consultancy synonym forever.

Socrates claimed he taught nobody anything — that he had no knowledge to transmit and his entire method was to ask questions until the other person delivered the idea themselves. He called it midwifery. *Maieutic* is the adjective.

The practical content of that flourish: an answer you were handed is something you have to trust, whereas an answer you were walked into is something you understand — you know which assumptions it rests on, because you're the one who said them out loud and heard how they sounded. In a system design round, that difference is the whole difference. You will be asked to justify your design by somebody whose job is to look unconvinced. You can only justify what you actually derived.

Also, "rubberducking.club" was available, which weighed on the decision more than I'd like to admit.

<!-- TODO(kousik): two or three sentences on who you are — what you build, how many of these
     rounds you've sat on the interviewer's side of. This is the one place on the site where
     credibility matters, because "trust me to play dumb correctly" is a real claim. Keep it
     dry; the page is already doing enough talking. -->

## The state of the club

One duck. Deliberately unfunded, ungraded, and unscaled. It exists to find out whether anybody wants it, and if nobody does that's a perfectly respectable result that cost a weekend and a domain name.

If you want a go, [say so]({{ '/contact/' | relative_url }}).
