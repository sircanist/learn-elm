# learn `elm`

> This tutorial is still a "***Work-in-Progress***" ...
> please _help_ us by reading through the draft
and raising any issues you find: https://github.com/dwyl/learn-elm/issues

## Why?

> It's _difficult_ to _introduce_ elm to someone
who has _never_ heard of it before without sounding "_evangelical_" ... we've tried our best to be "_objective_", if you spot anything
unclear or unexplained, please open an issue: https://github.com/dwyl/learn-elm/issues

Most of us are _already comfortable_ with `JavaScript`
and it is _still_ the
[_**most popular programming language**_](https://stackoverflow.com/research/developer-survey-2016#technology)
whereas `elm-lang` is not _even_ on the [_radar_](https://stackoverflow.com/research/developer-survey-2016)
... so _**why**_ should we even _consider_ it?

The _reason_ you should be taking `elm` _seriously_ is _**NOT**_ the "_standard_" (_valid_) tech-based arguments:

+ "_**Pure**_" _functional style_ means there are fewer (_often zero_) ["_side effects_"]()
+ _**Fewer language features**_ [**_lowers_ cognitive load**](https://blog.prototypr.io/design-principles-for-reducing-cognitive-load-84e82ca61abd) when you're reading (_other people's_) code.
+ **_Much_ less to learn** than comparable "Stacks" e.g:
  + **React** + Redux + Flow + Immutable + Babel + all the other setup-code...
  + **Angular** + Typescript + Babel + ReactiveX + etc. (_bottom line is: elm is `less` to learn_!)
+ _**much faster**_ than React.js or Angular 2 in _all_ "[***benchmarks***](http://elm-lang.org/blog/blazing-fast-html-round-two)"
+ **Built-in ["_Time Travelling_" Debugger](https://www.youtube.com/watch?v=DSjbTC-hvqQ&feature=youtu.be&list=PLglJM3BYAMPH2zuz1nbKHQyeawE4SN0Cd&t=1633)**
 that lets you record and replay actions in a user session (_thus **eliminating** the need for manually writing Selenium/Nightwatch tests!_)
+ _**helpful/friendly compiler**_ that _tells you **exactly**_
what is wrong _before_ you attempt to view your app in the browser/device.
+ Evan surveyed the _existing_ web programming languages for his
University thesis and Elm is the `result` of that study (_borrows ideas from several places and assembles them into a cohesive beautiful package much how Apple made the original iPhone..._)

The the _reason_ we [@**dwyl**](https://twitter.com/dwylhq) are _exploring_ the `elm` _ecosystem_ is because
it has:
+ _thriving **community** where everyone is welcome_
+ _clear **leadership** from nice + smart people and_
+ _a shared **mission** to built the **best** graphical user interfaces for the web!_

these are a _few_ of [our _favourite_ things](https://youtu.be/0IagRZBvLtw).


> @rtfeldman put it best in his [**6 Months of Elm in Production** talk](https://youtu.be/R2FtMbb-nLs?t=47m36s) (_which we **highly recommend** watching!_)<br />
"_If you take **two products** and **compare** them on **feature-checklists** <br />
that gets you a **very inaccurate picture**
of what it's going to be like to actually **use them**_."

![6-months-of-elm-comparison](https://cloud.githubusercontent.com/assets/194400/20147838/be5d2746-a6a1-11e6-91af-5149c5bf345b.jpg)



## What?

### `Elm` is a programming language for creating web browser-based graphical user interfaces. Elm is `purely functional`, and is developed with `emphasis` on `usability`, `performance`, and `robustness`. It advertises "`no runtime exceptions` in practice," made possible by the Elm compiler's `static type` checking.

> It's _difficult_ to _overstate_ how _game-changing_ `elm`,
the `elm-architecture` and `elm-platform` are to web development right now! The fact that Dan Abramov was "_inspired_" by Elm (architecture and debugger) for Redux and React Hot-Reloader
respectively, should tell you that there's "_something_" here worth exploring ...

### Isn't "Functional Programming" _Difficult_...?

If you `feel` like _**F**unctional **P**rogramming_ is "_complicated_" you aren't _alone_,
it's a _perfectly normal_ sentiment:

> I _tried_ functional programming in JavaScript before, it was _confusing_...

All we can say to that is:

[![dont-panic](https://cloud.githubusercontent.com/assets/194400/20135968/74ed05d6-a66a-11e6-9f30-f50f911053e6.png)](
  https://en.wikipedia.org/wiki/Phrases_from_The_Hitchhiker%27s_Guide_to_the_Galaxy#Don.27t_Panic)

_Trust_ us, the non-mathematician people (_without a Computer Science
or "Engineering" background_) <br />
_initially_ `felt` Functional Programming
was a _steep_ learning curve, <br />
_because_ it's _quite_ different from what we were _used_ to
(_procedural/imperative/mutable_...)

We `found` that the elm language is actually quite small <br />
and when we break it down there are only a handful of concepts <br />
we need to _understand_ before we can start reading/writing code.

> **Tip**: if you want to _understand_ the core concepts,
jump to the [Language](#) section below.

## Who?

If you haven't felt the _pain_ of trying to debug/maintain/extend
code you did not _originally write_, or have not worked
on a sufficiently large app to `feel` the
"_fix one thing breaks two other features_" ["_whack-a-mole_"](https://youtu.be/GVJL9oXgsAA),
you _might not_ not see the _benefit_ of the `elm` ecosystem ...

But we _urge_ you to consider the list in the "Why?" section (_above_)
and if _any_ of those items appeals to you, <br />
give elm ***5 minutes*** of your
time _**today**_ to _try_ the "_**Quick-Start**" below_!


## How?

The best place to start is with the "_Official Guide_": http://guide.elm-lang.org/get_started.html <br />
we have _condensed_ the steps into the **5-minute** instructions below:

### Pre-requisites

+ A **Computer** with:
  + **Node.js _Installed_** (_if you don't already have node get it here_: https://nodejs.org/en/download/ )
  + **Text Editor** (_any will do but we recommend_: https://atom.io/ _because it has good Elm syntax/plugin support_)
+ Internet Access (_just so you can install elm_)
+ Some **JavaScript/Node.js Knowledge** (_ideally you have built a basic Node/JS app before ... but no "major" experience required_)

### Quick-Start (_5 Mins_)

#### 1. Clone this repository

On your localhost:

```sh
git clone https://github.com/dwyl/learn-elm.git && cd learn-eml
```


#### 2. Install

```sh
npm install
```
Yes, install it _globally_ because it's installing the `elm-compiler` and `elm-platform`
which you will _want_ to keep up-to-date. also avoid using [`sudo`](http://stackoverflow.com/questions/16151018/npm-throws-error-without-sudo)




### In-depth Step-by-Step Tutorial (_60mins_)

The _best_ place to start your elm journey is with the "_Official Guide_"
http://guide.elm-lang.org/ which is available on Evan's GitHub at: https://github.com/evancz/guide.elm-lang.org

> At the time of writing, the _entire_ "_Official_" guide to Elm (GitBook)
(_written by the creator of elm and improved by the community_) is ***111 pages***:
https://www.gitbook.com/book/evancz/an-introduction-to-elm/details
which means it's readable in a couple of hours. \


## Reading

+ How to use Elm at work: http://elm-lang.org/blog/how-to-use-elm-at-work
(_or work for DWYL where you're actively encouraged to use it!_)
+ JavaScript interoperability: https://guide.elm-lang.org/interop/javascript.html
+ How to add Elm to _existing_ JS codebase: http://tech.noredink.com/post/126978281075/walkthrough-introducing-elm-to-a-js-web-app
+ How Elm made our work better (_success story_):
http://futurice.com/blog/elm-in-the-real-world

### Promising but incomplete:
+ Learn You an `Elm` http://learnyouanelm.github.io/ (_lots of "Todo" items and last updated 2 months ago_)
