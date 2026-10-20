# Expertise Isn't Learning
### WiDS AlumNight 2026 — Keynote Script Outline (draft)
*~30 minutes. After-dinner keynote. Audience: data science majors and alums.*
*Built from the WCCCE 2026 talk ("Everything I Know About Teaching I Learned at Puzzled Pint"), re-aimed at learners instead of teachers.*
*Placeholders marked **[ACTIVITY]** are presenter-led.*

---

> **Current structure lives in `slides.qmd`** (speaker notes included). The talk is now three parts:
> 1. **Joy in Community.** Jotto, Puzzled Pint, the study, expertise vs. learning.
> 2. **Everyone Holds a Piece.** Euler: you have to collaborate to find all the critical information. The tutor objection, *the* answer vs. a response, transactive memory.
> 3. **Diversity of Voice.** The colour cube (leave out green and you only get purple), the space of ideas, Woolley's collective intelligence (social sensitivity, turn-taking, proportion of women), the alum poll, what the tutor is for, the close.
>
> The sections below are the earlier draft, kept for the longer notes.

## 0. The argument in one breath

There's good evidence now that you learn physics faster from a well-designed AI tutor than in a classroom. I believe it. But that study measured **expertise**: what you can do on a test next week. **Learning** is something else. Learning is communication: making meaning with other minds that push back, need things from you, and change because you were there. Expertise can be delivered. Learning has to happen *between* people.

**What changes from WCCCE:**
- The WCCCE audience was *teachers*: "here's how to build a room worth being in." This audience is *learners and former learners*: "here's why the room is worth being in, and what you lose when you leave it."
- Drop the five-step methodology, the activity list, and the attendance confession as a full section. Keep both games (Jotto, Euler), the community research, and the closing line (rewritten).
- New spine: **take the Harvard study seriously, then read it like a data scientist.** This room respects the numbers, so don't wave them away. Question the response variable.
- The two games do different jobs. **Jotto** opens the talk. **Euler** comes right after the expertise/learning distinction, as live evidence for it.

---

## 0b. Before you begin

**To do:**
- [ ] Print the Euler cards (double-sided, long-edge flip, several sets) and cut them out
- [ ] Buy a balloon and draw a graph on it
- [ ] Bring the physical RGB cube prop

**Bring / set up:**
- **Euler printouts:** `euler_graph_cards_24_6up_duplex.pdf` (24 cards, 6 per page, 8 pages, print double-sided). Numbers on one side, graph on the other. Print enough sets for one card per seat (or per pair); duplicates across tables are fine. Leave them face down at place settings, or hand them out at §5.
- **Balloon** for the outer face. Draw a graph on it with a Sharpie beforehand.
- Tablet for someone to write the conjecture
- Jotto word grid and decision tree slides (reuse `jotto_tree.svg` from wccce2026)

---

## 1. Opening — Jotto  *(~7 min)*

**[ACTIVITY: Jotto]**

No preamble. Word grid on screen (same 16 words as WCCCE).

> "You're the Wordle master and I'm going to guess your word. Pick one of these, and make sure the whole room knows it and agrees. I'll leave the organizing to you. I'm stepping out. You have 45 seconds."

*Come back in at the back of the room. Everyone turns around. Play from the decision tree slide; first guess NOR.*

::: notes
Getting a whole banquet hall to agree on one word in 45 seconds is harder than doing it in a lecture room. That's fine. Whatever chaos happens is material: they had to communicate to produce a single answer, and nobody told them how. If it falls apart, give them another 30 seconds and say so out loud.
:::

**Walk to the front.**

> "That's a decision tree. Every one of you has built one. So: is this a good tree?"

*With WCCCE teachers this was a rhetorical aside. This room will actually answer: depth, balance, information gain. Let one or two people say it. Enjoy that they know.*

> "It's deliberately bad. I don't split well. You all knew that in about three seconds."

*Then the welcome: who you are, how glad you are to see alums back. And the hinge:*

> "Notice what you just did. Before I could run my algorithm, two hundred people had to agree on one word, with no instructions and no leader. That part wasn't on the slide. Hold on to it."

---

## 2. A study I believe  *(~4 min)*

> "I want to tell you about a study, and I want to be fair to it, because I think it's good work."

**Kestin et al. (2025), *Scientific Reports*.** Harvard intro physics (PS2), Fall 2023. Randomized crossover: 194 students, each did one lesson with a custom AI tutor at home and one in an active-learning classroom, in consecutive weeks (surface tension, fluid flow).

*One slide, three numbers:*
- **Learning gains more than doubled** with the AI tutor (median post-test 4.5 vs 3.5 from a pre-test of 2.75; effect size 0.73–1.3 SD)
- **In less time:** median 49 minutes vs a 60-minute class
- Students reported **more engagement and more motivation** with the tutor

And the comparison class wasn't a bad lecture. It was active learning, by people who are very good at it.

> "So if you're a student in this room and you've been quietly thinking 'I learn better on my own with the AI,' here's a paper that agrees with you."

*Pause. Let them feel agreed with.*

::: notes
Don't strawman this. The audience is numerate, and if you dismiss the study they'll stop trusting the rest of the talk. Concede everything it actually shows.
:::

---

## 3. ~~Read it like a data scientist~~ — CUT from the deck (we make our own case instead)

> "But you're data scientists. So the first question isn't 'is the effect real.' It's 'what's the response variable?'"

What was measured: a short post-test on the content of that lesson, given right after it. First exposure. In the authors' own words, the "understanding, applying, and analyzing" levels of Bloom's taxonomy. They say it may not extend to "complex synthesis or higher-order critical thinking."

> "That's a real thing, and it's worth measuring. It's how fast you can acquire a piece of expertise. On that metric, the tutor wins. I'm not going to argue."

> "But every person in this room knows what happens when you mistake the metric for the thing you care about."

*(Goodhart. No citation needed for this crowd; they've lived it.)*

The authors know this too. Their recommendation is to use the tutor for first exposure *before* class, so the room can be used for "advanced problem solving, project-based learning, and group work." And: "an AI tutor should not replace in-person teaching."

> "Even the paper that says the tutor wins says: don't stay home."

---

## 4. Expertise isn't learning  *(~4 min)*

*This is the centre of the talk. Slow down.*

> "Here's the distinction I want to leave you with."

**Expertise** is a stock: what you know, what you can do. It can be transferred, tested, and, it turns out, delivered very efficiently by a patient machine.

**Learning** is a process, and it's a communicative one. It's what happens when your understanding meets someone else's and one of them has to change.

- **Vygotsky:** every idea shows up twice in development. First *between* people, then *inside* one person. The conversation comes first.
- **Sfard (2008), *Thinking as Communicating*:** thinking *is* communication, the conversation you have with yourself that you learned by having it with others.
- **Learning by explaining:** you find out what you don't understand when you try to say it to someone who doesn't nod. (Chi on self-explanation; Fiorella & Mayer on learning by teaching.)

> "That's a claim. Let me show you instead."

---

## 5. The graph exercise  *(~7 min)*

**[ACTIVITY: Euler's Formula]**

*Cards out, numbers side up (the A / B / C slide).*

> "Ignore the picture, it's for something else. You've got three numbers. There's one rule that holds for every card in this room. Find it."

*60–90 seconds. Tables will start talking to each other without being asked. Let them. Get a conjecture onto the tablet: A + C = B + 2, or whatever order the labels landed in.*

> "Now flip it over. Which number is which?"

> "Check against your neighbour's card. And the next table's."

*Someone will undercount faces by one. **Balloon:** hold up the graph drawn on it. On a sphere every region is enclosed, including the "outside." Then get vertices, edges, faces written up.*

**V − E + F = 2.**

> "You couldn't have checked that alone. One card is one data point. Your neighbour's card was data you couldn't generate yourself. And the outer face? Someone at your table said it out loud before you saw it. The room was the instrument."

**Now the objection, said out loud:** "The tutor talks back. Isn't that communication too?"

> "It talks back. But it doesn't need anything from you. It has no stake in whether you're right. It isn't confused in a way you could help with. It won't remember tomorrow that you were the one who saw the outer face."

Communication with a human goes both ways: you're a resource for them as much as they are for you.

**The answer vs. a response.** The other side is what *you* owe. You don't have to be nice to a machine, and you don't owe it careful listening. It arrives with the authority of the textbook. A person has no automatic credibility, so you have to listen carefully and weigh what they say, and be decent to them while you do. Their nuance is what improves the shared idea. (The person who said "the outside counts as a face" wasn't a textbook.) Careful listening is a deeply human skill, and it's the strongest predictor of collective intelligence.

The research name for what just happened:
- **Collective intelligence** (Woolley et al., 2010, *Science*): groups have a measurable intelligence that isn't predicted by their smartest member. The strongest predictor is how well members read each other. That's a communication skill.
- **Transactive memory** (Wegner): groups learn who knows what and split the thinking. The group becomes the cognitive system.

> "None of that shows up on a post-test about surface tension. All of it just happened at your table."

---

## 6. Data science is a communication job  *(~4 min)*

*Turn to the alums.*

> "Alums: raise your hand if the hardest part of your job last month was technical."

*Some hands. Fewer than the students expect.*

> "Keep your hand up if the hard part was actually figuring out what question someone was asking. Or telling someone their data couldn't answer it. Or getting three teams to agree on what a column means."

*Let the students look around the room.*

> "That's Jotto. A room full of people who have to agree on one thing before anybody's algorithm can run."

No tutor can pass that test, because it's a different kind of problem. The question isn't sitting there waiting to be answered. It gets built, between people who each hold part of it.

> "Every workplace is a group project. We're practicing."

::: notes
If there's an alum you know well, consider asking them beforehand for a one-sentence story: the moment they realized the job was mostly people. Calling on them by name makes the room real.
:::

---

## 7. What the tutor is for  *(~2 min)*

*Don't end anti-AI. This audience uses these tools every day, and so do you.*

> "So use the tutor. Seriously. Use it to get the expertise faster. That's what the paper says it's good for, and I believe it."

> "Then take that expertise somewhere it can turn into learning: a room, a table, a study group, a code review, a stakeholder meeting. Expertise is the ticket in. It isn't the thing."

**To students:** you're someone else's data. When you're not in the room, everyone is slightly less capable, including you.

**To alums:** you're the community of practice these students are trying to join. Lave & Wenger: novices move from the edge to the centre by doing real work alongside people who are further in. Tonight, that's you.

---

## 8. Closing  *(~1 min)*

*Callback to the cards.*

> "A tutor can make you an expert.
> Only other people can make you a learner.
> You found that formula because the person next to you had a different card."

*(Alternate, kept from WCCCE: "A tutoring system answers your question. A teacher opens the gap that makes you realize you had a question in you all along.")*

---

## Open questions

- **Length:** ~33 min with both games. If the slot is 20, shorten §4 to two sentences (the Euler exercise makes the argument anyway) and cut §6 down to the hand-raise.
- **Room size:** Jotto consensus across a whole banquet hall might take longer than 45 seconds. Fallback: each table picks a word and one table is chosen at random.
- **Title:** "Expertise Isn't Learning" is a placeholder. Other options: "The Response Variable," "You Are Someone Else's Data."
- **Slides:** reuse the WCCCE Quarto/reveal setup (`theme.scss`, Jotto and A/B/C slides)?

---

## References

- Kestin, G., Miller, K., Klales, A., Milbourne, T., & Ponti, G. (2025). AI tutoring outperforms in-class active learning: an RCT introducing a novel research-based design in an authentic educational setting. *Scientific Reports*, 15, 17458. https://doi.org/10.1038/s41598-025-97652-6 · full text: https://pmc.ncbi.nlm.nih.gov/articles/PMC12179260/
- Vygotsky, L. S. (1978). *Mind in Society*. Harvard University Press.
- Sfard, A. (2008). *Thinking as Communicating: Human Development, the Growth of Discourses, and Mathematizing*. Cambridge University Press.
- Chi, M. T. H., et al. (1994). Eliciting self-explanations improves understanding. *Cognitive Science*, 18(3), 439–477.
- Fiorella, L., & Mayer, R. E. (2013). The relative benefits of learning by teaching and teaching expectancy. *Contemporary Educational Psychology*, 38(4), 281–288.
- Woolley, A. W., Chabris, C. F., Pentland, A., Hashmi, N., & Malone, T. W. (2010). Evidence for a collective intelligence factor in the performance of human groups. *Science*, 330(6004), 686–688.
- Wegner, D. M. (1987). Transactive memory: A contemporary analysis of the group mind. In *Theories of Group Behavior*. Springer.
- Lave, J., & Wenger, E. (1991). *Situated Learning: Legitimate Peripheral Participation*. Cambridge University Press.
