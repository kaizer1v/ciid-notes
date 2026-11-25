# Intro to Programming / Creative coding

* Dennis Paul - https://www.ciid.dk/community/dennis-paul (Munich, Germany)
* Jose of course

- Dennis is a German, from Munich. Loves nerd t-shirts. Loves cycling and hates 'mobile' stands on his bike(cycle).
- Dennis also had an exhibition called 'Backroom' - exhibited sounds

🤗 Excited about this week

**What is my relationship with programming?**
- Interesting question
- I have used it to quite an extent - a lot of python and javascript
- python for running processes, data crunching ()
- data visualisation (d3), react
- Almost every attempt to solve any problems was by programming it

Really excited about doing this from a very fresh perspective

> 2 is the oddest prime
> 

-----

# Day 01

**Exercise 01**

- on the centre of an A4 sheet
- draw vertices for 3 by 3 grid (there should be 3 x 3 dots)
- let's name these dots using coordinates (x, y) - where x is row (left to right) & y is column (top to bottom)
- so, (1, 1) is top left dot & (3, 3) is bottom right dot
- draw the 2 diagonals crossing through the mid-point
- connect the same sided corner dots with an arch so (1, 1) arch connects to (1, 3) & (1, 3) connects to (3, 3) and so on...
- this should look like a flower
- connect the remaining mid-point dots in the shape of a diamond (tilted square) - inside the flower
- and now for the inner diamond, connect the adjacent vertices with an bulging arch, such that the arch passes through the outer vertex for each

We spoke about what "creative coding" is. The idea of the output not necessarily being solving a problem. We shared a lot of work from various people (see reference section)

In many ways, in creative coding, you focus on the 'system' that generates the outcome rather than the outcome directly

We installed and played around with processing

-----

# Day 02

We looked at some ways of 'interacting' using programming. Essentially, the interface by default that a program gives us are mouse and keyboard related. For example, `mouseClick` or `onMouseClick`, `mouseMove` etc. These are interfaces that allow you to interact with the program. Similary, there are keyboard functions as well as touch methods. Playing with these is a fun way to make the sketch more fun. The other thing that javascript specifically enables us to do with interacting is, to leverage HTML inputs as well - which means, you can use input types like text, option selection or even range dragger etc. and use these to manipulate the program

It prompted me to think about doing creative coding in a different way. 

Some of the functions that we explored are `map`, mouse events as well as `random`
- map
- random
- constants: frameCount, frameRate, width, height
- 2D primitives: circle, rect, line, arc, triangle
- colour related: background, fill
- events: mouseMove, mouseX, mouseDragged, mouseMove etc.
- beginShape, endShape, vertex
- make your emoticon (my face)
- Question: Why bezier has 3 vertices

made a face, added animation on events

-----

# Day 06 (W2)

The brief this week is something I can think about as a portfolio piece. An installation, a screenbased, a performance etc. something that I can continue to work on later as well. The main idea of this brief is to focus on the program mainly, although the output expectation is not a processing sketch.

```
we ask you to produce a project that is SMALL ( as in WEIRD / CUTE / ABSURD / DADA / DIRTY / NAÏVE / QUEER / NON-NORMAL or simply situated in the very SPECIFIC ). engage with *computation* in a way you find suiting for *you*. move away from the *normal* modes of presentation and interaction ( e.g computer keyboard, laptop screen ). you may use anything at your disposal e.g: sensors, machines, screens, projectors, dogs, fellow students, fruits, smallness, simplicity, context. think about it over the weekend and present your idea on monday. plan *small* and iterate. *trust the process*. ♥ the computer.
```

**Thoughts on this**
- something that a dog
- show us something what a computer means, beyond the screen
- try negotiating challenges a computer provides (don't forget we are 'designers')
- something that is iterative in nature
- simplicity is often hard to achieve (SMALL, humble)

rotate a screen, tiny tiny screen (siftables), multiple CTR monitors, TV monitors (think matrix). Just project on deep uneven surfaces - only to be seeing from point of view. use lights. screens are generally designed to be.


## Working on the Brief (Nelson, Siddhant)

**Brainstorming**

- interactive projection mapping
- measure of success
- computer vision
- media pipe, openCV
- filters, 
- data -> projection -> 

- fun, humourous, challenging of making it interesting
- artsy: 
- <Nelson> takeaway: I want to do something simple (takes simplicity of it and extrapolate it)
- <Vivek> takeaway: Extrapolate simplicity
- <Siddhant> takeaway: let the people experience

1. projection
2. body movement
3. game
4. *fun/funny
5. 🚨 constraint: no physical computing

**what all can I do with my body?**
- projection body of the dancing to do funny poses and dancing
- gets progressively harder (harder to make poses)
- game aspect: people do this simultaneously eg: chicken dance vs bharatnatyam pose

- karate. projection of again body poses
- make two people do that
- the act of doing it in person is fun/funny

- rock/paper/scissor on projection with the computer
- game aspect: its a game in itself, progressively 'harder to predict' 
- *not really funny (_per se_)

- face exercise: make face gestures to translate / simulate other game
- using face as a medium to move a car towards finishline
- 

- translating sound into a visual
- singing / voice to make visual art
- *not a game _per se_

- translating voice pitch for them to make them play a game
- shout loud to go faster vs deep voice to go slower
- game: just an obstacle course (eg: make the ball reach the finish line)

- blow harder on the mic to make the ball move
- game: for ball to reach the finish line (obstacle course)
- 

- digital swim: swim in a pool of fishes, use body movement to move fishes away
- game: make all the fishes get into the fishnet 🥹
- 

- dodge ball: move your body to avoid getting hit by a cannon
- game: obstacle course type, long you go you win


MODEL

<interaction> - face/hands/voice/body
<game> - obstacle course/guess-quiz/puzzle/improv

* [mediapipe](https://google-ai-edge.github.io/mediapipe-samples-web/#/vision/image_classifier)
* 

# Day 07 (W2)

- Microexcursions on umfeld by dennis p paul (https://www.dennisppaul.de/collection/selected-works/) & his projects
  -> https://umfeld.dennisppaul.de/ & [codeberg like github but opensourced + german](https://codeberg.org/dennisppaul)
- Umfeld is a library for processing
- writing stuff on 'C' and openFrameworks
- he writes and documents his [notes](https://notepad.hfk-bremen.de/R5PdnowRR3Wa0mJoTS2jzA?edit)
- umfeld is an opensource project and is a homebrew plugin (for opensource mac stuff)
- Jose spoke about OSC - open sound control prototol for device-to-device communication...

# Day 08 (W2)

- `Keystone` is a processing library for doing projection mapping

# Day 09 (W2)

- Documenting work is super important (*please click photos of people testing)

Enhancements
- sounds
- graphics + directions
- reduce to 3 lives in dodgeball

# Day 10 (W2) - Final Day

- AI changes a lot of things, we had to figure out how it would function and then define the form of interactions (esp with gestures)
- We looked in to gestures as the primary 

-----

# Fun To Do

- Make somethings, has synthesiser access (graphic stuff), ask Jose & Dennis about this
- Try to teach people, share information, guide others
- Maybe I can do some additional stuff like, finish an online series of work on p5js + Danielshiffman
- Explore all the main functions in p5js and then just use combinations of them to create art

- explore how to write an app for homebrew
- how to write a processing library?!
- wtf is c-make (for "building" apps) and how it works
- wtf are shaders and how they work
- wtf is processing vs p5 vs openframeworks
- how-tf does vscode works, can I write some plugins for myself?
- hack macos and write custom shortcuts / commands and ifttt stuff
- check 

# References

- https://docs.google.com/document/d/1BBSDAW-NRDfONFXtQ037S3bQrBgcIdCHcxOHLijpO-M/edit?tab=t.0#heading=h.9flud76ec1uf
- A book "The Craftsman" by Richard Sennett
- Zach Lieberman = the creator of OpenFrameworks & pioneer of creative coder
- School of poetic computation (check that out)
- Joshua Davis : praystation.com
- manolo gamboa naon https://www.katevassgalerie.com/manoloide
- casey reas
- http://code-poems.com/
- Daniel Shiffman of course 👌
- casey reas + ben fry -- processing: a programming handbook for visual designers and artists (2007)
- daniel shiffman -- learning processing (2009)
- daniel shiffman -- the nature of code (2013)
- demoscene - sub culture on writing 
- [Programming design systems](https://programmingdesignsystems.com/shape/procedural-shapes/index.html#procedural-shapes-qYPzCLg) - a reference from coding train's [video on customShapes](https://www.youtube.com/watch?v=76fiD5DvzeQ)
- Also a brilliant library that can be used [with p5](https://verse.works/) also [p5.brush](https://github.com/acamposuribe/p5.brush)


# Notes / My Thoughts

I loved the first intro exercise, where people were paired (or sequential) and the human had to act as a computer. It was about providing clear instructions to someone 

Creative coding can be a method of defining the visual and then using those algorithms to the attach it to 'data' would be a very cool thing

I played around with p5 and learnt about
1. generating in a grid / circular (PI) pattern
2. randomising variables while generating, like fill, strokes, positions, sizes etc.
3. make custom shapes

To explore
1. motion
2. smooth generators, rather than random generators (use noise)
3. make game/interactive stuff
4. text/glyphs/typography
5. just ascii art
6. just pixel art

While the first week was something that felt a little bit of a refresher, feeling lazy and slow without using AI was also a thing. Everyone was using an AI.

On being a designer and working with briefs. Briefs are something that are precise and clear, sometimes, they act as constraints - an inner possiblity that everyone would product similar things. Its also an invitiation to question it, re-write it, get a sense of it's attitude. It's successful, if you make up ending something that matters to you. You can also take it at face value vs you can question it.

> what is 'creative coding'?

projection mapping

- Generally did push me to think beyond the problem/solving space, really trying to be 'creative' and play a role that I haven't played before.

- spike solution: timebox and do quick prototyping with programming

## Learnings
- keep brainstorming very visual
- solve with the bare-minimum things first. break the problems into smaller and managable pieces and make it work for minimal resources. which means, solve and visualise, act it out in a way that it starts to reveal unplanned, unthought-of, unforeseen points.
- think about affordances, interactions, intro to IxD stuff
- using AI might not 'help me connect' me to the end product? how closely/far-away is the creator connected to AI generated product.

<write>
**Different approach of designing in the real world**
- in the real world, there's a piece of technology that is interesting and then finding ways to applying to interactive form of or a applying it to a different domain that didn't have that technology
- 

<write>
AI definitely has helped me be more of the 'designer' and worry less about the 'technical' feasibilties of it. Although, there's a degree to which I get to work with the tech side of things, I still decide the library, the approach, be more specific about the functions to write and then let AI do the nitty-gritty stuff. This definitely gives me the autonomy & control of the implementation approach + mainly the "design" of the product along with how it'll function. I also get to spend more time on the research

In this approach, I almost have a fine-tuned model that specifically to do specific tasks

- But the question is 'who owns this product'. There was product manager, a bunch of software developers, a few designers, a few marketing & sales folks etc. did only the developers owned the product?

- Another analogy, metaphor of command-line/terminal -> desktop with a UI. We have been abstracting the hard stuff to make it easier. So for someone who didn't know 

- One more analogy, walking vs taking a cab vs driving. Walking is manual, but lets you smell the flowers, go slow, enjoy, take photos vs cab is just getting from here to there. It's gotten a choice

- break it to really small stuff and then even if you are using AI, do it in chunks so that the problems are still isolated. 

- Even before AI, I personally always believed coding as a way to achieve harmony and is part of design, at least for digital products. In essence, it is equivalent to the clay a potter plays with, the wood for worker who crafts with or a construction material an architect designs with.

ref: https://www.jonkolko.com/writing/notes/9

- Write about micro excursions as a thing-todo, within academia + even within design teams. it would be nice for everyone within the team to do a micro-excursion to learn about others and a way to teach the skills one has to others. Something that we did at SAP.

-----

# Summary

**In a nutshell:** Creative coding is about designing the *system* that generates an outcome. Keep it small, iterate, and treat code as a material, the way a potter treats clay.

## Week 1: the basics
- **Human as computer:** drawing from written instructions showed how clear instructions need to be.
- **Processing / p5:** primitives, colour, custom shapes (`beginShape`, `vertex`, `endShape`), `map`, `random` and constants such as `frameCount`.
- **Interaction:** mouse, keyboard and touch events, plus HTML inputs (text, select, range) to control a sketch.
- **Practice:** an animated face, grid and circular patterns, randomised fills, strokes, positions and sizes.

## Week 2: a small, weird project
- **Brief:** make something small, specific and computational, away from the normal laptop and keyboard.
- **Team takeaways:** extrapolate simplicity and let people experience it. Constraint: no physical computing.
- **Ideation model:** *interaction* (face, hands, voice, body) × *game* (obstacle course, quiz, puzzle, improv).
- **Direction:** projection, body movement and play, including a dodgeball game, with gestures as the primary interaction.
- **Tools met:** MediaPipe, OpenCV, Keystone (projection mapping), Umfeld, openFrameworks, OSC (Open Sound Control).

## Key learnings
- Keep brainstorming visual, and act ideas out to reveal what you didn't foresee.
- Solve the bare minimum first; break problems into small, manageable pieces.
- **Spike solutions:** timebox quick prototypes in code.
- A brief is both a constraint and an invitation to question and rewrite it. It succeeds if you end up making something that matters to you.
- Document the work, especially people testing it.

## On AI and authorship
- AI lets me be more of a designer: I choose the library, approach and functions, and it does the nitty-gritty.
- It may also weaken my connection to the final product. Who owns it?
- **Analogies:** terminal → desktop UI (abstraction), and walking vs driving vs taking a cab (each is a choice).
- If using AI, work in small chunks so problems stay isolated.

## To pursue
- **Explore:** motion, noise over pure randomness, games, typography, ASCII and pixel art, shaders, CMake, writing a Processing library, VS Code plugins.
- **Write:** designing from a technology outwards, AI and ownership, and micro-excursions as a team practice.

## Loose ends
- *Why does bezier have 3 vertices?* `bezierVertex` takes two control points and an end point; the start is the previous vertex.
- Day 10 doesn't record the final outcome or how people responded.
