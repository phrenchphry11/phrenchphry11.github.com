---
layout: post
title: Seven Reasons Engineers Hate Their Managers in the Age of AI
comments: true
excerpt: AI has changed a lot in our day-to-day as EMs and ICs.  Here are seven reasons engineers are losing trust in their managers right now, but also the case for hope.
---

### 1. Information-gathering is becoming more siloed

When I first joined Fieldwire, I joined as an engineering manager who had no previous experience contributing to Fieldwire's codebase.  I was a blank slate.  No historical knowledge of product decisions, no context on tech debt that hung around, no sense of tech design plans that were implemented or scrapped.  And for me, the best way to learn more was to ask around.  Sometimes I'd ask people to point me to documentation, RFCs, or old JIRA tickets, but sometimes I'd just ask people to talk me through it directly.  It'd mean we'd have an extra-long 1-1, a nice coffee walk, or an extra team huddle.

But now, with AI and our handy dandy Confluence MCP, it's easier to just talk to Claude all day.  I'm thrilled I can bug my devs less and I can just talk to Claude, right?  I can ask Claude a half-baked question, and it can pull out years of context around old RFCs, tech debt projects, and product specs.  It's more efficient, right?

But as we've onboarded new engineering leaders at Fieldwire, I've noticed a more troubling side-effect here.  While once the hard work of EMs and staff devs was to talk to people, get historical knowledge, and build consensus, it's often mostly done with Claude now.  Two years ago, if another staff eng was doing research for a big initiative, I'd probably have known, because we'd all have been asking around about it.  But now, we're all sitting inside our own Claude silos.  We ask Claude a bunch of questions, get pretty good answers, and are able to churn out pretty polished design diagrams, RFCs, and documentation.  But often it comes at the loss of the middle part - the friction of reconciling conflicting answers from the devs we're working with, the exercise of excavating historical context that isn't sitting in confluence, and the act of building coalitions before churning out a polished document.  

Sure, we're able to churn out pretty good design docs now, but we're doing it without the messy coalition-building, historical digging, and collaboration that makes these docs even more robust.  And for ICs, that means less opportunity to bring their insights and opinions to org leaders.


### 2. Deadlines are more arbitrary

I'd like to think I'm the type of manager who pushes back when someone sets unrealistic goals for my team.  As an IC, I know the feeling when an exec tells me "coding up an A/B test for this signup flow should only take a week" because he made a few PRs on that part of the codebase a couple years ago. I don't want people on my teams to feel that. 

That said, AI has supercharged the setting of arbitrary productivity goals.  I've heard (and, honestly, seen) all too many horror stories of an exec who vibe codes a super slick prototype on a weekend, shows it to the product org, and uses that prototype as proof that it shouldn't be too difficult to ship a fully-fledged product in just a couple sprints.  But this often doesn't include the work of wrangling messy third-party SDKs, understanding business edge cases, setting up good reporting and analytics frameworks, and all the other software development things.

Sure, a vibe-coded prototype can often prove out something tangible, and it can speed up early development decisions, but without consulting the devs who will be involved, it increases the trust gap between engineers and their managers.

### 3. Metrics are used in ambiguous ways

As a self-professed metrics-obsessed engineer, I love to measure all things dev-experience, but I know to take these all with a grain of salt.  I like to keep track of how long PRs stay in review, but I know some PRs take longer than others to review.  I measure the size and rate of change of my bug backlogs, but I know our team has seasons of driving down bugs and also pushing out features quickly.

But suddenly, teams have these new metrics dashboards popping up.  AI made it easy to count lines of code, PR volume, token usage, and AI-generated code accepted.  Some teams are more heavily measuring the things AI inflates. I know I'm not alone in resenting being graded on gameable numbers.

### 4. AI rewards context switching

AI rewards context switching.  By way of example, a top dev on my team currently has 2 RFCs open, a backend PR open, as well as separate iOS and Android PRs in the works.  Claude is great at cruising through these different workstreams, and this dev's commit numbers this month are through the roof.

The problem?  Engineering managers are fundamentally supposed to be GOOD at context switching.  An EM's day is typically a mix of team meetings, 1-1s, PRs reviews, checking in on random Slack DMs, doing roadmap planning.  For me, that's a skill that I had to develop.  Took a year or two, but I think I'm pretty good at context switching now.  For ICs? I'm not so sure.  Code reviews are more critical than ever, and good code review requires flow and focus.  Often, reviewing code is inherently harder than writing it, because you have to reverse-engineer someone else's thoughts. If an engineer is constantly context switching, their mental model of the codebase is fragmented.  

And I worry this will deepen the problem.  EMs are used to context switching, AI supercharges IC-level context switching.  EMs can easily capitalize on an IC's fragmented attention by jamming in more planning meetings, sprint ceremonies, all while losing sight of the most important thing to protect: an IC's focus.

### 5. Performance expectations are subtly changing

We've heard a lot about the collapsing of R&D roles in software orgs now.  PMs can vibe code prototypes, and engineers can free up their time to help make product decisions.  It feels like everyone's mental model of a "good" engineer is changing.  Now, a good engineer is someone who can code, but can also be flexible, jump in with product enhancements, be willing to try new ideas, technology, or product areas.  

That said, how many EMs and engineering orgs are actually updating their career ladders to reflect that?  How many interview loops are changed to test IC engineers on their product sense?  Folks say "taste" is the differentiator of strong people in engineering organizations, but how often are we making that explicit in our organizational expectations?

### 6. We're shipping more hype-driven features

The AI hype is real.  Every earnings call, every press release, it's AI.  As an engineering manager, I know I'm not alone in unsuccessfully pushing back on the value of another AI-enabled product just so we can say "AI" on the next press release, all while critical bugs go unaddressed.

And to be fair, execs often have good reason to need to ship these things, and I often don't have full context or backstory.  But, how do we as eng leaders both share the AI narrative to the eng org in a compelling way, but at the same time thread the needle of allowing IC-level pushback when it's constructive?

### 7. There's the existential disrespect

There's this constantly simmering threat now of AI replacing all our jobs.  It's simmering underneath everything I just wrote about.  It's the fear that managers view engineers as nothing more than a cost center.  It's the existential disrespect.

Each time an exec aggressively pushes AI, says "coding was never the hard part," or proudly shows off their vibe-coded project, it makes us feel devalued.  It makes the years of late nights in the college computer science lab, cramming to finish a project, banging our heads against walls to solve bugs, and trying to comb through messy documentation all feel like it was for nothing.

It's not the AI tools that engineers hate, it's the way engineers are treated like replaceable cogs in the very expensive software engineering wheel.  And, yeah, there's no doubt the profession is changing.  But it's not changing fast enough to fully replace all our engineers.  So as managers, we have to respect our engineers enough to keep them engaged and aboard our mission of building software to the best of our abilities, since software engineering as a profession isn't going away anytime soon.


### There's hope?

My hope is engineers with supportive managers and organizations are having the best year of their careers.  My hope (and belief) is the tools coming out are turning up the volume of what engineers are capable of, not devaluing them.
