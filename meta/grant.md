# cat butt

`#ssbc-grants`

## what are we going to do?

we (@mikey and @gregkan of [Root Systems](https://rootsystems.nz)) will develop an app to play [Telephone Pictionary](https://creightoncreation.wordpress.com/2013/07/28/telephone-pictionary-art-a-great-party-game-with-or-without-drinking/) (also known as [Eat Poop You Cat](http://www.annarbor.com/entertainment/eat-poop-you-cat-telestrations-review/) on Scuttlebutt.

not just a buttload of fun, the app would be the first game to represent and embody the philosophy and paradigms of Scuttlebutt and Solarpunk. we hope it can act as a significant cultural touchstone and asset for the community, as well as a bit of a teaser and welcoming gesture for those beginning to explore the Scuttleverse.

### what is Telephone Pictionary?

we played Telephone Pictionary a heap over our retreat last week - it's an incredibly simple and elegant social game to play with friends. prepare to have your creativity and imagination enjoyably and painlessly invoked.

Telephone Pictionary is game which combines:

- "Telephone": you pass a phrase around a circle of people to see how it changes with each lossy transmission
- "Pictionary": you draw a phrase and try to get people to guess the phrase

1. every player starts with a stack of papers equal to the number of players
1. each player writes a word or phrase on the top of their stack
1. next, everyone passes their stack (as a single unit) either clockwise or counter-clockwise
1. then, on receiving someone else's word/phrase, you draw your interpretation of that word/phrase
1. with your drawing on top, pass your stack to the next person
1. then, on receiving someone eles's drawing, you move that paper to the back of the stack, and write your interpretation of the drawing, as you wish!
1. repeat the drawing -> writing -> drawing -> writing stages until you receive your stack (whether it's a drawing or phrase depends on whether your group is odd or even)
1. last, take turns sharing your stacks, have a laugh on how the original word or phrase was transformed or not over time!

### how will this benefit the Scuttlebutt community?

#### embodying Scuttlebutt's philosophical and operational paradigms

since the game involves passing private messages around until their culmination in an ultimate reveal, it could stand as an accessible way to both communicate and embody the fundamental paradigms that underlie Scuttlebutt.

gossip drives this game, a chain of dissemination and transformation. interpretation, the possibility of multiple truths, and their convergence and divergence all contribute to the ensuing ecstatic hilarity and also the occasional somber moment of reflection.

the game is entirely dependent on social and collaborative behaviour. the nature of the game is such that individualistic competition is incoherent, and joy is found between and across the individuals - that is, as a group! no matter how good or how terrible you think you are individually as an artist or wordsmith, you are guaranteed to enjoy your output, especially in the context of everyone else's.

#### a best practice example app for Scuttlebutt

by choosing to develop a simple and clearly scoped game for Scuttlebutt, we can prioritize _app development quality_, which we can feed back into the ecosystem as a best practice example app with friendly documentation and clear code.

#### team learning

[Root Systems](https://rootsystems.nz) is a team of full-stack JavaScript app developers.

when thinking at our retreat about what grant we could propose, we struggled to see our team (except for Mikey) being able to make low-level protocol improvements, or write documentation in areas we didn't already have experience in.

## how are we going to spend our 1 month of work?

Greg will play the lead developer, Mikey will play the technical coach.

at the end of the grant, we plan to deliver a desktop app that allows a group of people to play a game of Telephone Pictionary using Scuttlebutt.

to reduce our scope (and choose our battles wisely!), we will try to reinvent as few wheels as possible, instead using popular tools (like Electron and React) that are most comfortable for us.

### roadmap (draft)

1. design: wireframes
1. design: message schemas
1. design: acceptance tests
1. dev: scaffold stack
1. dev: start a game
1. dev: pass first word or phrase
1. dev: pass subsequent drawing
1. dev: take turns until cycle completes
1. dev: share at the end
1. docs: how we use ssb messages
1. docs: how we use `patchcore`
1. docs: how we use `flume`
1. docs: project retrospective

## why are we motivated to do this?

we are motivated to do this because we want to share our skills with Scuttlebutt!

Greg is keen to learn how to build apps on Scuttlebutt.

Mikey is keen to learn how to support app developers on Scuttlebutt.
