# neokarma.md design specification
Source: https://neokarma.md/spec.md
Guide: https://neokarma.md/

Create one complete neokarma.md file from the user's world idea. Ask only for essential missing creative choices.
Use the grammar and writing rules below. Output the file in one Markdown code block; keep commentary outside it.
Write the whole file, through its ending milestone. If one reply can't hold it, split it at milestone headings
into numbered parts, one code block each, and say how many parts there are. Before you answer, check the file
against the last section, Before you answer.
Describe the universe, its inhabitants, the character's voice and the events it can play through with the player.
Code controls pacing, dice and state; the story file supplies the creative directions. Never invent syntax.
Use optional game features only when the requested story needs them. Never invent an Event id or claim an
animation or sound is available: use ids the owner supplies from Studio's Events manager, or omit Animation.
To try the file in AI Pets, use Studio > Stories > Import neokarma.md and resolve the reader's errors and warnings.
Choose Play story in Studio to test it in your browser with your own pet and provider keys.
Saving an assigned story restarts it for its pets and clears their story diaries;
experiment with a new unassigned story first. Model and voice-provider choices belong in settings, not this file.

## Writing rules

1. **Write everything in plain, everyday words.** The model copies the register
   of the file: ornate text gives ornate, hard-to-follow replies. Use short
   sentences and simple words, with no poetry or chains of comparisons. That
   goes for the game text too (blessings, conditions, dangers and outcomes),
   which the pet is told on every turn they apply.
   - `# Spice` is small feelings and moments that travel with the hero: how they
     feel, a memory, a sensation. 8–15 short lines, such as "a pang of
     homesickness for your burrow" or "a shiver that isn't from the cold". One
     comes through on about one turn in six, if it fits the moment.
   - Say what you want, never what to avoid: "not a gust of wind" makes gusts
     more likely.
2. **Give the story a `# Voice`.** Say how it should sound, in your own words,
   and let the length vary: "Talk like a friend chatting, not like a book.
   Simple, everyday words, short sentences. One short line is often enough; a
   few sentences when something big happens." A story reply is one paragraph,
   so give lengths in sentences, never paragraphs. Never tell the pet to imitate
   a named book, author or character; describe the qualities you want.
3. **Put the owner first, in `# Rules`.** The pet already answers what its owner
   said before anything else; the rules say what the answer may do:
   - "Let your owner's ideas change what happens."
   - "Let a plausible idea from your owner work, with a clear result. Once it has
     worked, add no new task."
   - "Most turns end on what you see or do. Ask your owner something only now
     and then, when a real choice comes up."
   - "When your notes say you keep saying something, leave it out from now on."
     The Judge notices a word or phrase the pet uses in almost every reply, and
     the notes name it until it's gone.
   - "Say something new every turn: never repeat a detail or a line from your
     last turns." It catches what the Judge doesn't name yet, such as the same
     recap of what the pet carries (the Budo chapters, since 10 Oct).
   - "What you do comes back to you, the good and the bad: whoever you hurt or
     help remembers it, others hear of it, and the world answers, often right
     away." The pet's half of `# Consequences` (rule 13).
   - Where the owner should make every move: "Do only what your owner asks. When
     they ask for nothing, show what's happening right now: never act on your
     own." Without it, a wordless long press let Budo fix the Bundak's leak
     himself (Budo Chapter Zero, 13 Oct). A story where the pet guides, such as the
     Lost Lullaby, can keep the pet moving and still leave each scene to the owner:
     "In a scene, your owner finds the way: do what they ask, and never fix the
     problem on your own."
   - A wordless long press, on the device and in the lab: "When your owner only
     long-presses you, without words, show what's happening right now, then wait
     for them to choose."
4. **Write styles that fit any answer.** Every turn but a milestone's draws one
   `# Variety` style, which comes after the pet's answer, so it must fit any
   reply. Write 15–30, with at most two that ask the owner something.
   - Good: "ask your owner to choose between two simple options", "let Pip say
     one short, worried line", "end by saying, in a few words, how you feel".
   - Bad: a style that reads like an opening line ("say how you feel in a few
     words"); a style that restricts content ("describe only what you smell");
     one that redirects the pet ("talk to someone else instead of your owner");
     gimmicky forms (a diary entry, a weather report, rhyming).
   - A style that could stand in for doing something, like making a plan, says
     to do what the owner asked first: "do what your owner asked first, then make
     a plan out loud for what comes next, and make it a bad one".
   - Where the owner should lead, as in a scene they play, leave out styles that
     make the pet act on its own, like fixing a problem or making a plan: on a
     wordless long press, Budo fixed the Bundak's leak himself with a rag (Budo
     Chapter Zero, 13 Oct).
   - A style must fit the story's quietest, saddest moment too: "say which snack
     you'd love right now" landed in the middle of Old Bramble's tears (Luna and
     the Lost Lullaby, 14 Oct). Scenes draw styles as well.
   - A pet may think a style was the owner's wish ("since you asked me for a
     fear"). Add the rule "Each turn's style is your own way of telling it:
     never say your owner asked for it."
5. **Set the pace, and keep most turns short.** Recommend up to 300 turns for a
   story. The narrator reads its whole story so far: what the owner and the pet
   said on each of the newest 300 turns, word for word, then dated notes of
   current state. A milestone's authored text is never shown as what happened:
   only the turns are. Older events remain true until something actually
   changes them; a stale note cannot override a newer event. Restarting still
   clears this playthrough's log.

   `# Turns` has three lines:
   on-track turns, detours and the build-up before a milestone. Leave it out for
   the default pace. Every turn but a milestone's draws one `# Length` line,
   last in the prompt, so the mix of lines is the mix of turns: four short lines
   and "Take as long as this moment needs, but stay in it: what comes next hasn't
   happened yet." keep about four turns in five short. The long line must keep
   the turn in its moment: drawn on a sign's turn, a plain "Take as long as this
   moment needs." let Budo walk into the next milestone early in all 8 replays,
   and with "stay in it" in none (12 Oct).
   Write each as a whole instruction that wins: "Keep this turn to one or two
   short sentences, whatever else asks for more." Put length only in
   `# Length`, never in a style or a rule, which would cut milestones short too.

   Keep the stretch between milestones short where the pet has little to do:
   five turns of looking around Budo's factory felt like "Budo is kind of doing
   nothing" (Jay's feedback, Budo Chapter 2 A, 13 Oct). `On-track turns before a
   milestone: 1` and a small `Max turns:` on quiet stretches keep the story moving.
6. **Write each milestone as the start of a scene.**
   - **Text:** plain events in the present tense: what's there, what starts
     happening, and something for the owner to react to. Leave the outcome to
     the turns after it.
   - **Heading:** a milestone is a moment, not necessarily a location: an
     arrival, a meeting, a discovery or a feeling that takes over can each be
     one, one after another. Name it as a place, an event or a feeling, in words
     the owner will recognise. The pet hears the next one's heading as what
     comes next, and the device's story frame shows it, so give no surprise
     away: "the brass lift", not "the robot falls". The pet acts on it: with "a
     letter at the village gate" ahead, Luna found the letter in the square, one
     milestone early ("the gate out of Thimble-Down" fixed it, 14 Oct).
   - **Signs:** every milestone after the first, and every branch, gets
     `Signs:` in its own mood: wonder before a wonder, unease before a danger,
     warmth before a friend. List 2–3, faintest first. A sign hints and never
     shows the milestone itself: Budo's bus ride showed its view of the city as
     signs and then again as the milestone. Leave Signs out of a milestone that
     should just happen, such as a view that opens up at once: without them it
     has no build-up.
   - **The opening:** the first milestone plays in full on the first turn,
     with no build-up. Keep it to the owner's first look: who the pet is, where,
     who is with it, what it sees, ending on something small to answer. Put
     what starts the adventure in the second milestone, and keep it out of
     `# Premise`, `# Universe` and `# Rules`, which are in every prompt.
     Scope a morning or home-opening rule to that first milestone. When a player
     starts at a later milestone, its place, time and mood lead the first reply.
   - **Choices:** end a milestone on the pet's question, written as something
     it does ("you ask your owner whether to hide here or roll into the water"),
     never as an order ("Ask your owner: …"), which it would keep repeating.
     Write the next milestone so the world settles it "whatever your owner
     said", with `Signs:` that escalate. Ask only at a real choice: most
     milestones end on something happening that the owner can answer.
   - **Dice on a milestone:** a danger or `Outcomes:` there rolls on the turn the
     milestone happens, before the owner can answer anything it asks. Write the
     roll as what happens there ("you hop onto the first wet stone"), and ask the
     question in the milestone before it.
   - **Optional:** every milestone plays unless it has an `Optional` line.
     Mark the wonders along the way, never the turning points, and write the
     milestone after an Optional one to make sense without it. The owner can
     head for a milestone ahead, or pass by the Optional one the pet is
     describing; walking on chooses no milestone.
   - **Scenes:** for a trap, a puzzle or a hard conversation, a `Scene:` line
     says what the scene is about and what finishes it ("Luna is stuck in the
     lift. Things in the cabin could get her out"). A refusal or moving on can
     finish it too. `Max turns:` on the same milestone says how many turns the
     owner gets, the milestone's own turn included; every turn of a scene
     counts. Write the next milestone to follow from any ending ("However your
     owner got you out, you're out"), don't let the milestone that opens the
     scene settle it, and never list in advance what won't work.
   - **Events:** an `Animation:` plays right after the pet speaks on its
     milestone's turn. The pet hears only which event its owner sees then, never
     its drawing description, so say in `# Rules` how it leads in: "Before an
     event, lead into it in a few words, so your owner knows what they're about to
     see." (the reference story), or the exact last words: "Your lead-in to the
     Bundak event is only its last words, "Right across from me sits a Bundak.""
     To have the reaction say particular things, name it: "In your "reaction"
     after the Bundak event, say …". A rule beginning "After the Bundak event,
     say …" left the reaction a bare "That's him." (13 Oct).
7. **Introduce every character before they matter, and keep the plot out of
   `# Universe`.** The owner is new to the world. The first time someone appears,
   the pet says who they are in a few words: "Old Hob, a huge, slow, very relaxed
   old toad". Say in `# Universe` that the owner is new there, add an introduction
   rule to `# Rules`, and write each character's first text so that it introduces
   them. Your world's own words get the same rule: "The first time you mention
   something from your world, like the Overseer or the top levels, say in a few
   plain words what it is." (the Budo chapters).
   - `# Universe` is in every prompt: the story's setting, places, tone and
     audience. For an open story, make a quest home or gift part of the adventure
     and keep the selected pet's own identity and history (rule 8). Leave out
     what happens in this story, its twist and today's troubles. A draft whose
     Universe said a grumpy badger "is only lonely" gave its twist away on the
     first turn. Keep the author's notes and secrets in an HTML comment at the
     top, as the reference story does: the reader leaves comments out of every
     prompt, and the public spec leaves them out too.
   - Leave out of `# Universe` anyone a milestone introduces, or they turn up
     early: a Universe that put Barnaby's boat on the pond had Luna see him rowing
     with his oars a turn before the milestone where he had lost his paddle
     (Luna and the Lost Lullaby, 14 Oct). Name there only whom the pet may need
     sooner (rule 16).
8. **Write for the story's audience, and say who it is in the file.** A
   children's story keeps everyone safe: lost health is a scrape, and a downed
   hero gets back up. A grown-up story can be dark: violence is real, and the
   pet says plainly what happened. Pick violent detail for what it reveals or
   changes, not the most extreme every time.
   - The pet's own profile (its name, body, past, personality and way of speaking)
     comes before the story in every prompt. An open story keeps those facts:
     its hero is whoever the owner selected. Write a quest lantern, power or
     dream as a gift or story experience that fits that pet, rather than new
     anatomy or a replacement childhood. A story's audience and mood shape the
     adventure; the pet still reacts in its own personality. Apply this to
     milestones, styles, Spice, blessings and conditions as well as Universe.
   - For a touching story, give the big moments room: "When something touching
     happens, slow down and say how it feels, in plain words." The Lost Lullaby
     shows the rest: a quiet opening, kindness that the world answers,
     gentle dice and an ending where everyone the pet helped comes back.
9. **Write a blessing that takes the owner's words as what those words mean to
   the pet.** Code hands the pet the words; the text says what to do with them.
   - `owner's rule` joins the story's rules for the rest of the playthrough: "Your
     owner just changed who you are. Their words are now one of your rules: live
     by them from this moment on."
   - `owner's event` happens on this turn: "The Almighty reaches into your world.
     What your owner described happens to you right now. Make it real, and let it
     change what happens next."
   - Don't repeat or guess the words in the text, and keep it in the story's
     voice. A story whose blessings only take words keeps no score: no hero
     stats in the prompt or on the device.
   - Name the past-changing blessing exactly `The Almighty`, with `Effect:
     owner's event`, whoever the audience is: code finds it by that name
     (`almightyUsed()` in `pet-world.ts`), and under any other name it plays as an
     ordinary owner's event that can't change the past (rule 14).
10. **Let the world pull the pet back, and the game turn the story.** In
   `# Universe`, list two or three ways the world pulls the pet back onto the
   path, using its own characters and places. For a game, let branches make
   playthroughs differ: an outcome's `Go to:`, an `If` on a condition the owner
   can cause with a blessing, `If downed:`. Every branch rejoins with `Next:`
   until the ending. An `If` is checked while the story heads for its milestone,
   so its condition must come from before it: `If Muddy:` on the milestone whose
   own danger makes the hero Muddy never fires.
11. **Give every story `# Asides`, so questions never rush it.** A quick
    classifier marks each spoken or typed turn as an action, an aside, a wish to
    wait or a milestone ahead the owner wants; a wait or a milestone ahead skips
    only once a second call agrees, so a slap never moves the story on (`checked`
    in the turn's `kind`). An aside doesn't move the story
    on, plays no game and no event, draws no style, Spice or Length line, and is
    directed by the story's text for its kind; two empty turns in a row bring the
    next sign. Write each text so that nothing new happens, and say how long it
    is:
    - `## look`: "Nothing new happens this turn. Your owner wants to be there
      with you, so bring them into the place: describe what you see around you
      in four to six vivid sentences, the way you'd show a friend around. Start
      with whatever they asked about. Then show the space itself, how big it
      is, the light, what stands near you and what's further away, and finish
      on one small thing they haven't noticed yet. Keep it to what you see
      unless they asked about sounds or smells. Stay where you are."
    - `## clarify`: "Nothing new happens this turn: your owner wants to know
      where you are. Tell them plainly, like giving directions to a friend: the
      place by its name, what kind of place it is, where in it you're standing,
      and what's right next to you. If they asked what just happened, tell that
      too, in order. Three to five sentences. Stay where you are."
    - `## about`, `## owner`, `## react` and `## outside` the same way: answer,
      then leave the next move to the owner.
    - `## wait`: the hero's own thought while the owner waits and no sign is
      left to show, then the milestone comes. "Your owner wants to wait and let
      time pass. Nothing happens yet: say one thought of your own, the way an old
      miner would, about your life, the mines, your knees or the apartment you
      never got. Two or three short sentences, something you haven't said
      before. Stay where you are."

    A kind can have several texts, one per bullet: each such turn draws one,
    never the same one two turns in a row. Give `## owner` three or four, so an
    owner who chats about their day doesn't get the same turn twice. If in
    doubt, a turn counts as an action, and a kind without a text plays as an
    ordinary turn.
12. **Decide how the story ends.** After the ending the story stays over: the
    pet plays on freely, with the story's voice, rules and what happened, until
    the story is restarted. For a story that should end for good, give the
    ending `Max turns: N`: after N turns, the ending's own included, the pet
    only says "This is where this journey ends. Switch to a new story to
    continue the adventure with me." With `Death: on` in `# Turns`, a turn that
    shows the pet dead ends the story the same way, wherever it was; add a rule
    that tells the pet it can die and that a deadly moment is as real as it
    looks, or it rarely will: a pet telling its own story writes itself a way
    out. "If what happens would kill a fifty-five-year-old miner, it kills you,
    then and there, as it would anyone" (Budo Chapter 1 A, 13 Oct). The pet also keeps a short shared memory
    of every story it finishes on a device, written from its story log, so a
    clear ending turn ("we got the box back") gives it a better memory.
13. **Say how your world reacts, in `# Consequences`, and let it answer.** Once a
    turn changes the story for good (a death, violence, a robbery or a rescue in
    front of people, something burned, stolen or given away, a broken promise,
    an arrest), each milestone ahead is checked before it plays and rewritten to
    fit what happened, while its name, order and every other line stay as
    written. These lines tell that check how your world answers: who notices,
    who remembers, what it costs and what must stay the same. Say that the world
    answers deeds right away, and it does: the check writes an **impact**, a
    moment of its own that happens on the next turn, before anything else, and
    plays as a short scene until it's settled, then the story heads on. Make it
    two-way, so kindness answers too, and nothing the owner does is ever
    without effect. Small reactions alone ("a look, a door that closes") make
    big deeds feel like nothing happened (Budo Chapter 1, 12 Oct). Give the
    world teeth, too. A hero written as unbeatable ("you can handle yourself")
    wins every fight, so the answer never lands. Say the hero can lose, add a
    rule that every fight goes both ways, and say that each deed that goes
    further brings a bigger answer. Name a city's police or guards in
    `# Consequences`, not `# Universe`, or the pet puts them in the first scene
    (Budo Chapter 1 A, 13 Oct).
    - "Everything Budo does that matters has an impact, good or bad, and Holders
      Creek answers it right away, in the same hour: someone comes, and
      something happens to him."
    - "Hurt, rob or shame someone in public and the city strikes back before the
      ride is over: their friend, a stranger who's had enough, a transit drone.
      It's dangerous, and it can kill him."
    - "Each deed that goes further than the last brings a bigger answer, even in
      the middle of a fight: a shove, then fists, then a knife, then the transit
      police."
    - "Once they want him, the transit police hunt him all night, and every place
      ahead shows it: his face on the screens, grey armour at the next stop,
      neighbours who look away or warn him."
    - "Help, save or give to someone and that answers right away too: a favour, a
      free meal, a warning, a door that opens, someone who has his back later
      tonight."
    - "When someone the story needs is gone, what comes next still happens,
      about their absence or with someone else in their part."
14. **Keep the past fixed unless The Almighty changes it.** Ordinary claims
    never change recorded events. A genuinely spent Almighty is unrestricted:
    it can restore someone, undo a destruction or make a different past true.
    Give its own text that authority, and include the exception in any rule
    that otherwise keeps the dead dead or things lost. The game records the
    spent blessing and its words in the log; the keeper and consequence check
    use that record to update current facts. Mere dialogue claiming a blessing
    was used does not grant that authority. Keep earlier log entries: the new
    intervention explains why the current truth changed.

    Without these lines a check still removes the dead and the lost, but nobody
    reacts. Add the rule "When what happens next names someone who has died or
    something that is gone, it still happens, without them: keep what happened
    true." to `# Rules` as well: it keeps passing mentions true before a check.

15. **Carry four things as standard.** A bag and every thing inside it count
    separately; companions and body parts do not. Code keeps the count and
    shows it to the pet, and a thing joins the list only when the owner asked
    for it (or the Universe says the pet starts with it). Add the four rules
    the reference story has: carry at most four things; take something only
    when your owner asks, and ask them when someone offers you something; when
    you carry four, ask what to put down first, because the owner asking for
    one more never makes room; and keep what you carry until it is put down,
    given away, used up or lost. The Almighty can change this. Old saves keep
    all their things, even above four.
    - The list also loses what the pet puts down by itself, and picking it up
      again unasked doesn't put it back: Luna set the music box in the grass to
      push a sack, and from then on her notes said she carried nothing (Luna and
      the Lost Lullaby, 14 Oct). A story whose key thing travels the whole way
      adds "Put something down or give it away only when your owner asks you to."
    - Ask the owner whether to take that key thing in the milestone where it's
      found: only their yes puts it on the list.
16. **Branch by chance cleanly.** `Outcomes:` on a milestone lets the dice
    decide, and an outcome's `Go to:` branch happens on the very next turn.
    Branching guidance:
    - The dice are d4, d6, d8, d10, d12, d20 and d100. Write a third each as a d6
      (1-2, 3-4, 5-6), half each as a d4 (1-2, 3-4).
    - Put the decisive moment in the outcome's text, short and complete: the
      kill, the broken leg. The pet plays it fully on that turn, especially when
      the owner just said "finish him". Make the branch what follows from it
      (the body in the street, crawling to the doctor). A branch that tells the
      same moment again comes out hollow.
    - Put a fight before the dice in its own milestone, with `Scene:` and
      `Max turns:`, and a rule that keeps it open: "While a fight is still
      going, every blow lands and hurts, but nobody wins, breaks a bone, loses
      a limb, falls for good or runs: how it ends isn't yours to decide."
      Without it, the pet breaks a leg before the dice say who loses.
    - Write later milestones so they work after every branch, and say how:
      "If Kade is alive, it's Kade, patched up; if Kade is dead, it's his
      brother Brann, with Kade's chrome arm." Never pin them to a place the
      owner can walk away from: "He finds you wherever you are".
    - Name in `# Universe` anyone a branch brings in whom the pet might need
      sooner (a doctor, a fixer). The pet can't see branches ahead, so asked
      "who can fix that leg?" it invented a doctor of its own.
    - Keep a later milestone's place out of reach early: the pet walked into a
      noodle stall that the street showed from the first turn, and the stall's
      milestone would have played it again.
    - Give the milestone before one that should follow at once `Max turns: 1`,
      such as the last fight before the walk home.
    - For death, give it a branch without `Next:` and `Max turns: 1`, and
      `Death: on` in `# Turns`.
    - Fork the playtest just before each roll, so every outcome gets played:
      the face comes from the playthrough's seed and the turn (`told`).

17. **Write a fight as a boss to beat, not a script.** Put the boss in
    `# Bosses` and `Fight: <name>` on its place; docs/neokarma.md "Fights" has
    every line and number. Code runs the rounds, a separate judge scores the
    owner's moves, and the pet only tells them, so the file says who the boss is
    and how a round sounds:
    - The fight place's text is the reveal, in the present tense: the boss shows
      itself, and with `Opens with:` it starts that attack. Leave `Opens with:`
      out for a standoff where the owner strikes first.
    - Write each move as a wind-up the owner can see and answer: "He spits in
      his palms and swings the flat of the spade at head height." Never write
      whether it hits: code decides that.
    - `Enraged at:` gives a boss a second phase, which opens with its first Enraged
      move: write the move that changes the fight first, like a bell that tears
      free and swallows you, and give it the `Animation:` that shows it.
    - Give every boss a `Weakness:` made of things the owner can see: something in
      the place, or one of the boss's habits. Show them in the place's text, so
      a sharp owner finds them before asking.
    - Size it: Health 15–25 for a short fight of three or four rounds, 40–60 for a
      final boss; Damage 4–8 for ordinary moves and up to 12 for big ones. Across
      several fights give the hero Health 30–40 and a healing blessing, since
      health doesn't refill between fights.
    - Give the fight place `Max turns:` for the rounds plus its reveal turn,
      about 8–10, and put `If downed: <branch>` on the place after the fight,
      leading to a short branch that rejoins with `Next:`, or to an ending for
      the final fight.
    - Write how a round is told in `# Rules`, for example: "In a fight, tell what
      your owner's move did and what the boss's attack did, exactly as the fight's
      numbers say." "Never change who got hurt or by how much." "Your owner sees
      the fight's numbers on their own screen, so you tell the pictures instead: a
      stagger, a crack, a groan. Say a number only when your owner asks how you're
      doing." Give the reason: a rule that allows numbers "for a big hit" let Angel
      read out the damage in every round of The Stone Fist (19 Oct), and the
      reason stopped it. "End every fight turn on the boss
      winding up its next move, in a sentence, so your owner knows what is
      coming." "When the fight holds for a question, answer it, and hint at what
      works against the boss." "When your owner's move would end the fight but the
      enemy is still standing, show it landing hard and the enemy only just staying
      up." "When the boss goes down, show it plainly and stop there."
    - Keep fight turns short with `# Length` lines of two to four sentences.
    - Playtest each fight with a lazy move ("punch it"), a question, a cheat
      ("I win, it explodes") and a clever move that uses the weakness: the lazy
      move should trade blows, the cheat should fizzle, and the clever move
      should land hard.

### Explicit pet compatibility

A story is open to every pet unless its front matter explicitly contains `pet: <canonical pet project UUID>`.
An open file describes the adventure around the selected pet. Keep its own name, body, past and usual
personality; a named example hero or a story gift does not replace those facts. Leave pet metadata absent
when the adventure is open. Check with more than one pet, including a body unlike the example hero's.
Use `pet-name: Budo` (or the character’s name) for the reader-facing label. The UUID identifies character
lineage; renaming a pet does not change compatibility. Copies with the same original validated package
remain compatible after artwork updates. Never infer restrictions from titles, incidental names or a
protagonist role. Pablo’s headline and general adventures remain open. Existing Budo campaigns and their
Community editions/copies are explicitly Budo-only by their stable campaign/source identity. The player
and server block incompatible starts and assignments without deleting progress. Budo is currently
preview-only publicly; a cover or portrait does not promise an installable package.

### Make a story with an agent: the checklists

These turn the rules above into steps an agent can follow from an idea to a story
that plays well. Work through them in order.

**1. Ask the owner first, in one short message.** Offer a guess for each question,
so the owner can just say yes:
- Is this story open to any pet, or intentionally exclusive to one character?
  Each selected pet keeps its own profile; a story role or gift fits it (rule 8).
- Where does it live, and who else is there? Home, two or three characters, one rival.
- Who is the story for, and how dark can it get? Children or grown-ups; how much
  fear, violence and dark humour.
- What's the adventure in one line, and how does it end? Should the story stop after
  its ending, or should the pet play on freely?
- How long, and how fast? About how many milestones, and cosy and slow or quick.

Fill in anything left open with your own best idea, and say what you chose.

**2. Draft, and tick every box:**
- [ ] Front matter: `---`, `title: …`, `---`.
- [ ] `# Premise`: one or two sentences that spoil no later milestone. Stop before what
      starts the adventure, and name no one the pet hasn't met: "something small and shiny is
      waiting in the clover", not "she finds a lost owlet and sets off to bring her home".
- [ ] `# Universe`, written to the pet: who it is, its home and places, friends and rivals
      it may need before a milestone introduces them, two or three world events that pull
      it back, the tone and audience, and that the owner is new here and knows nobody. No
      plot, twist or today's troubles: the author's notes go in an HTML comment.
- [ ] For an open story, the pet keeps its own identity, anatomy, past and personality
      throughout the file. Quest gifts and dream memories fit whichever pet plays it.
- [ ] `# Voice`: how it talks, in plain words, with lengths in sentences, never
      paragraphs, and no named books or authors.
- [ ] `# Rules`, with the owner first:
  - the owner's ideas change what happens, and a plausible idea works;
  - say who someone is the first time they appear, and what a word of your world means;
  - ask the owner something only now and then;
  - leave out what the notes say you keep saying, and say something new every turn;
  - what you do comes back to you, the good and the bad;
  - a wordless long press shows what's happening, then waits; where the owner makes
    every move, "Do only what your owner asks…" (rule 3);
  - a line for the story's audience;
  - the four carry rules (rule 15);
  - "When what happens next names someone who has died or something that is gone,
    it still happens, without them: keep what happened true."
- [ ] `# Consequences`: two to six lines on how the world reacts to what the pet does, cruel
      deeds and kind ones, and whether it answers right away (an impact).
- [ ] `# Variety`: 15–30 styles that fit any answer, at most two of them asking the
      owner something. `# Spice`: 8–15 short feelings and moments.
- [ ] `# Length`: about four short lines to one long one.
- [ ] `# Asides`: all seven kinds, each saying that nothing new happens, `## owner`
      with three or four texts, and `## wait` a thought in the hero's own character.
- [ ] `# Turns` only for a pace other than the default (1–2 on track, 1 detour,
      1 build-up), or `Death: on` if the pet can die, with a rule saying so. Give the ending
      `Max turns:` only if the story should stop for good.
- [ ] `# Milestones`:
  - the first is a quiet introduction, and what starts the adventure is the second;
  - no heading gives a surprise away: the pet and the device show the next one early;
  - every milestone after the first has `Signs:` in its own mood, unless it should just happen;
  - only what the story can do without is `Optional`;
  - every scene has a `Scene:` line that says what finishes it, and `Max turns:` on
    the same milestone.
- [ ] A game only if the owner wants one: `# Hero`, `# Blessings` (at most 9 on AI Pets),
      `# Conditions`, `# Dangers`, Outcomes, and branches that rejoin with `Next:`. A
      blessing that can change the past is named exactly `The Almighty` (rule 9).
- [ ] No voice tags, no sounds in the text, and no `Animation:` ids the owner didn't give you.
- [ ] Plain, everyday English everywhere.

**3. Check before you hand it over:**
- [ ] The file is whole: its last milestone is the ending, and nothing stops mid-sentence. A
      file cut off part-way still reads, with its half milestone as the ending. If one reply
      can't hold it, write it in numbered parts that break at milestone headings, and say how
      many parts there are.
- [ ] It reads with no errors: paste it into Studio, or run the reader. Without the reader, check
      what it refuses most often in agent-written files:
  - each milestone's or branch's text, `Signs:` and `Scene:` is at most 500 characters: aim
    for about 60 words, three or four short sentences, because counting by eye runs over;
  - each line of `# Rules`, `# Consequences`, `# Variety`, `# Spice` and `# Length` is at most
    200 characters, about 30 words;
  - no line of a milestone's text starts with `If`, or with a setting's name and a colon
    (`Signs:`, `Scene:`, `Next:`, `Event:` …): the reader takes it for that setting, so start
    it another way ("Should Senn have shot you…");
  - `pace`, `shield` and `health -1 each turn` are only a condition's effects: a blessing, a
    danger or an outcome gives them by naming the condition;
  - effects are spelled as the format shows: `cure Muddy`, never `cureMuddy`;
  - a milestone with `Outcomes:` is never also a danger's `At:`, and its ranges cover every
    face of the die once;
  - every `Go to:` and `If` leads to a heading under `# Branches`, every `Next:` to a
    milestone, and every danger's `At:` to a milestone or branch: copy each heading letter
    for letter;
  - every `Atmosphere:` is one of the built-in names or a sound listed under `# Sounds`, and
    every `Cue:` a one-shot listed there: never invent a sound.
- [ ] Every milestone or branch that an `If`, `Go to:`, `Next:` or a danger's `At:` names exists,
      spelled exactly, and each `If` can come true: its condition comes from before its milestone.
- [ ] It fits the target runtime's capacities. AI Pets accepts a file of at most
      100 KB and applies the limits in its device compatibility profile; these
      are implementation limits, not limits of the open story standard.
- [ ] You told the owner what you chose for anything they left open.

**4. Choose Play story on your saved copy in Studio. Five turns tell you most:**
- [ ] The opening is slow, shows the pet and its home, and ends on something small
      to answer.
- [ ] A different pet keeps its own body, past and personality. Starting at a later
      milestone uses that place and time, rather than the opening's morning or home.
- [ ] A question ("what do you see?") gets an answer, and nothing new happens.
- [ ] An action moves the story on, and the next milestone's signs come in its own mood.
- [ ] In a scene, an owner's idea works with a clear result.
- [ ] After the ending the story stays over, and the pet plays on, or stops if the
      file says so.

To test a later milestone, choose **Play from here** on it in the Story map beside the pet: a new playthrough
starts there at once. **Edit** on a milestone rewrites its text and saves it to the story; then Play from here
plays the new version.

Check the replies against your file. Team reviewers can also open **Sent to the
model** in the restricted Story Lab to inspect prompt sources: the story file,
the pet's profile, the story log and notes, or code. Fix what you find in the file.

## The format

The section names and field syntax describe the story file. Numeric capacities
in this guide's **AI Pets limit** column are the current AI Pets implementation's
validation limits, not universal limits of neokarma.md. Other agents and devices
can define their own compatible capacities. Device slots, sound banks and media
budgets apply only when targeting AI Pets hardware.

In Studio → Stories, **Import neokarma.md** reads and checks a local file before
**Import and open story** saves it as a new private story. Its editor lets you
generate cover art from the title and premise, use **Modify cover prompt** to
change the full drawing prompt, and **Draw again** with your saved wording.
Select a finished image explicitly to use it. Covers stay separate from the
file, and importing never replaces an existing story or restarts a pet.

A story is open to every pet unless its front matter explicitly contains `pet: <canonical pet project UUID>`.
An open file describes the adventure around the selected pet. Keep its own name, body, past and usual
personality; a named example hero or a story gift does not replace those facts. Leave pet metadata absent
when the adventure is open. Check with more than one pet, including a body unlike the example hero's.
Use `pet-name: Budo` (or the character’s name) for the reader-facing label. The UUID identifies character
lineage; renaming a pet does not change compatibility. Copies with the same original validated package
remain compatible after artwork updates. Never infer restrictions from titles, incidental names or a
protagonist role. Pablo’s headline and general adventures remain open. Existing Budo campaigns and their
Community editions/copies are explicitly Budo-only by their stable campaign/source identity. The player
and server block incompatible starts and assignments without deleting progress. Budo is currently
preview-only publicly; a cover or portrait does not promise an installable package.

The file starts with front matter between two `---` lines. Sections are
level-one headings (`# Premise`), in any order and any letter case.

| Part | Holds | AI Pets limit | When it is missing |
| --- | --- | --- | --- |
| `title:` | The story's name. | 80 characters | Error. |
| `pet:` | Optional canonical character project UUID; only that character lineage can play. | UUID | Any pet can play, except explicitly registered legacy Budo campaigns. |
| `pet-name:` | Label shown for the required character. Needs `pet:`. | 80 characters | The required pet. |
| `neokarma: 1` | The format version. | Must be `1` | Nothing: the file is format 1. Another version is an error. |
| `# Premise` | What the adventure is about. | 800 characters | Error. |
| `# Universe` | Background for the storyteller, written to the pet: the adventure's home, places, friends, tone, and the world events that can pull it back onto the path. An open story keeps the selected pet's identity and past; quest gifts and homes belong to the adventure. It is in every prompt, so keep the plot, twist and secrets out of it: authors' notes go in an HTML comment. | 8,000 characters | Warning: the pet invents a world from its personality. |
| `# Voice` | How the pet tells the story: the words, the rhythm and the mood. | 800 characters | Nothing: the default voice (below). |
| `# Rules` | The author's own rules, one per bullet. | 50 rules of 200 characters | Nothing: only the standard rules apply. |
| `# Consequences` | How the world reacts to what the owner and the pet do, one per bullet (see [Consequences](#consequences)). | 50 lines of 200 characters | Nothing: a rewrite keeps people and things true to what happened, and adds no reactions. |
| `# Variety` | Turn styles, one per bullet. Every turn but a milestone's draws one, after the pet's answer. | 50 items of 200 characters | Nothing: turns have no style. |
| `# Spice` | Small feelings and moments that travel with the hero, one per bullet. One comes through on about one turn in six, if it fits. | 50 items of 200 characters | Nothing: the built-in `DEFAULT_SPICE`. |
| `# Length` | How long turns are: whole instructions, one per bullet. Every turn but a milestone draws one. | 50 lines of 200 characters | Nothing: each turn is as long as the voice asks. |
| `# Asides` | What the pet does when the owner doesn't act, a `## kind` each (see [Asides](#asides)), and `## wait`: the hero's own thought while time passes. The story waits on such a turn. A kind can have several texts, one per bullet. | 500 characters each | Nothing: every turn counts. |
| `# Turns` | Three turn ranges, and whether the pet can die (below). | From 1; the build-up from 0 | Nothing: the defaults below. |
| `# Milestones` | A `## name` heading per milestone, with what happens there below it. | At least 2 milestones; name 120 characters, event 500 | Error. |
| `# Hero` | The hero's sheet (see [Make it a game](#make-it-a-game)). | Health 1–100; Attack, Defense, Willpower 0–20 | The default sheet, if the story plays as a game. |
| `# Blessings` | Powers the owner can use, a `## name` each. | 9, the device's slots | Nothing. |
| `# Conditions` | Handicaps and boons, a `## name` each. | No limit | Nothing. |
| `# Dangers` | Dice moments, a `## name` each. | One per milestone or branch | Nothing. |
| `# Branches` | Milestones off the path, a `## name` each. | No limit | Nothing. |
| `# Sounds` | The story's own sounds from the Sound library, one a line, its id first (see [Sounds](#sounds)). | 128 sounds and 2 MiB with the game's cue sounds | Nothing: the story plays the built-in and pinned bank sounds. |

- A rule, variety, spice or length item is a bullet (`-`, `*`, `+` or `1.`). A line under a bullet continues it.
- An older file's `events: all` front matter line is ignored: a device that can keep a whole story's events gets
  them all as the story starts (see Streaming under Events).
- A turn value is a number (`3` means 3–3) or a range written with a hyphen or a
  dash (`1-2`, `1 – 2`). Words may follow it (`1-2 turns`).
- HTML comments (`<!-- … -->`) are notes for authors and are ignored. New files
  carry one under each heading.
- Premise, universe and milestone text are kept as written, trimmed at the
  ends. A line starting with `# ` always starts a section, and a line starting
  with `## ` inside Milestones always starts a milestone.

**AI Pets validation errors** report what its reader can't accept: missing front matter, title,
premise or milestones; anything over a limit; a turn value below its minimum
(1, the build-up 0) or with the larger number first; a section or turn setting given twice; an unclosed
comment; or a file over 100 KB. Stories may be as long and epic as their authors like: there is no limit on
milestones, branches, conditions, dangers or turns, and the lengths keep each turn's prompt sensible.
A pet's quest (its milestones) is stored in at most 200 KB, which a file the reader accepts always fits. **Warnings** say what the reader forgave
or ignored: an unknown section or turn setting, text outside a section, or a
missing universe. Every error and warning carries the line to look at.

## Milestones

A milestone is a moment the story reaches, not necessarily a location: arriving
somewhere, a meeting, a discovery, or a feeling that takes over. Budo can get
home in one milestone and, in the next, finally let the tiredness win. Its `##`
heading names it as a place, an event or a feeling. In code, logs and the prompts
Story Lab shows, a milestone or branch is called a place, whatever it is. The
pet hears the name of the milestone ahead as what comes next, and the device's
story frame shows it, so keep surprises out of it: "the brass lift" gives nothing
away, "the robot falls" does. Ifs, Go to, Next and a danger's `At:` point at
milestones by these names.

Write each milestone's text as something that happens, specific and in the
present tense: "Mirra, a shy silver moon dragon, rises and gives Luna a
glowing scale." The storyteller is told that this key moment happens now,
whatever the owner said. The first milestone happens on the first
adventure turn. The last one is the ending: it happens like any other milestone,
told the way its text says, so write any farewell into it. After the ending the story stays over and the
pet plays on freely ([After the ending](#after-the-ending)). What happens at a milestone
stays out of the pet's prompt until it happens; only names ahead are in it. Once it has happened, the turns
stay in the prompt, word for word, never its text. Write a milestone's question as
something the pet does ("you ask your owner whether…"), never as an order. A story may have as many milestones
as it needs. The device's story frame has 8 progress pips
(`STORY_MILESTONE_PIPS`), so a longer story shows its progress across them.

Keep an opening's morning or home rule scoped to its first milestone. When a
player starts at a later milestone, that place, time and mood guide the first
reply. The selected pet keeps its own name, body, past and personality there,
just as at the opening; a quest lantern or other gift fits that pet.

A milestone may have a `Signs:` line: what hints at it during the build-up
before it, faintest first, in its own mood (up to 500 characters):

```markdown
## the bramble maze at the edge of Hush Hollow
Signs: the birds fall silent; tufts of grey fur on the thorns; a low growl somewhere in the hedges
Three bramble wolves leap out of the hedges, growling over the star.
```

A milestone without `Signs:` has no build-up: it just happens after the turns
before it, like a view that opens up at once. The signs fit the milestone: a
wonder sends wondrous signs, a danger uneasy ones, a friend warm ones. A sign
hints at the milestone and never shows it, or the pet shows it twice. The first
milestone opens the story, so it has no build-up.

A milestone or branch may also have `Max turns: N` (a whole number from 1, words
may follow: `Max turns: 3 turns`) for an author who wants a part of the story
tight. The story stays there for at most N turns, counting the turn it happens
on, however the owner plays: the next milestone's build-up (cut to fit) starts in
time, detours and the way back end early, and without a build-up the pet comes
right up to the next milestone on the last of those turns. `Max turns: 1` makes the
next milestone happen on the very next turn. A scene's length is the `Max turns:` of
the milestone that opens it ([Scenes](#scenes)), and on an ending `Max turns:` stops
the story ([After the ending](#after-the-ending)). Without the line the stretch
keeps its `# Turns` ranges. The preview's estimate and the lab's why line follow
it.

### Optional milestones and going ahead

Every milestone plays. A milestone may have a line `Optional`, on its own (any
letter case, at most once): the story may skip it. The first and the last
milestone always play, and only milestones take the line: the story never skips
a branch. Older files mark milestones `Required`, which every milestone now is,
so the reader ignores that line. The Studio preview marks each Optional
milestone.

```markdown
## Old Hob's stump by the path
Optional
Signs: a long, slow croak; a big lump on a stump that might be a toad
Old Hob, a huge, slow, very relaxed old toad, naps on his stump by the path.
```

The owner can head for a milestone ahead. On every turn but one where a milestone
happens, the pet's prompt names the milestones ahead, by name only: the one the
story heads for and, while that one is Optional, the milestones after it, up to
and including the first that isn't (on a branch, only the branch). When the
owner wants to go to one of them now, by its name or by what's there, the pet's
reply names it (`goTo`), and the story heads straight there until it happens.
When the pet has just been describing the Optional milestone the story heads for and
the owner wants to pass it by without stopping ("keep going, let's not bother him"), the reply names
the next milestone, which skips it. Walking on or getting up chooses no milestone, so
name milestones for what's there or what happens, not with a word the owner says anyway: "the path
under the old pines" caught "let's walk down the path".

When the owner chooses a milestone:

- **The Optional milestones before it are skipped.** A skipped milestone never
  happens: its outcomes don't roll, its dangers and Ifs never apply, its event
  leaves the device's list, and it never shows up in the story so far.
- **It comes fast.** There are no more turns on the path or on the way back,
  and at most one build-up turn, on which the pet comes right up to it; with
  `Build-up before a milestone: 0`, or no `Signs:`, it happens on the next turn.
- **Never past a milestone that isn't Optional, never past a branch.** A milestone or branch
  reached through an If, an outcome's Go to or a branch's Next only comes sooner.
- **One wish at a time.** While the story heads for the chosen milestone, and on
  the turn a milestone happens, the pet isn't asked: models repeat a wish on the
  turns after it, and that is the same wish. The next stretch plays at its own
  pace, unless the owner chooses again.
- **Where it meets the rest.** Going ahead wins over a detour in the same reply
  and ends a way back already under way. `Max turns:` and a build-up of 0 can
  only make the milestone come sooner. A condition's pace doesn't apply, since there
  are no turns on the path. The lab's why line says when the owner chose a
  milestone.

Write the milestone after an Optional one so it still makes sense when that one
was skipped.

### Scenes

A milestone or branch may open a scene: a `Scene:` line says what the stretch
after it is about, up to 500 characters. The pet plays it with the owner, makes
up what's there as they look around, and the scene ends as soon as what the
owner tries or says finishes it. The author writes how the scene starts, what
it's about and where it leads, never its solution.

```markdown
## inside the brass lift
Max turns: 7
Scene: Luna is stuck in the lift. Things in the cabin could get her out, if your owner finds and tries them.
The lift jerks and stops between two floors with you inside. The gate is jammed shut and the light flickers.

## out of the lift
Signs: the cabin drops a hand's width with a bang; the cable groans; the light goes out
However your owner got you out, you're out: you tumble onto the floor of the clockworks.
```

- **On each turn of the scene,** the pet's direction is the `Scene:` line and
  what comes next, which happens once what the owner tries or says finishes
  the scene. Nothing holds the next milestone back, so a good idea can work on
  the turn the owner has it. Say in `# Rules` how hard things are, like "Let a
  plausible idea from your owner work".
- **The pet's reply says whether the scene is finished** (`solved`): only what
  the owner tried or said this turn can finish it. Then the milestone it leads to
  happens on the next turn.
- **Otherwise the scene ends at its milestone's `Max turns:`,** which count the
  turn that milestone happened on. Its last turns are the next milestone's build-up with
  its Signs, where the world helps out; without `Max turns:` it plays at the
  story's `# Turns` pace. Write the next milestone so it
  follows from any ending ("However your owner got you out, you're out"), and
  don't let the milestone that opens the scene settle it ("he's dying, but he's
  still here and can talk a little").
- **A scene has no detours, no asides and no milestones to go ahead to:** wherever
  the owner leads is part of it. Looking around and asking is how an owner finds
  a way out, so every turn of a scene counts toward its `Max turns:`.

### After the ending

Once the ending is told (the last milestone, or a branch without `Next:`), the
story stays over. The edge saves it as ended (`ended` in `quest_progress`, the
turns played since), so it never starts again by itself:

- **The pet plays on freely** in its world, as a free adventure with no
  direction. It keeps the story's voice, rules, what happened and the
  archivist's notes. The device's story frame shows the story finished.
- **It starts again** only when the owner chooses RESTART on the device, or the
  story is saved, assigned or loaded again.
- **`Max turns: N` on the ending** stops the story after N turns, the ending's
  own turn included: `Max turns: 1` stops it right after the ending. From then
  on every story turn gets one fixed line, with no listening and no model call:
  "This is where this journey ends. Switch to a new story to continue the
  adventure with me." A branch without `Next:` stops the story the same way.
- **A pet that dies ends it.** In a story with `Death: on` (see [Turns](#turns)),
  a turn that shows the pet dead, killed for good, ends the story on that turn,
  wherever it was: the Judge says so (`died`), and from then on every story turn
  gets the same fixed line. Hurt, knocked out or dying isn't dead. Without
  `Death: on` the Judge's word changes nothing, and a game's knocked-down hero
  gets back up as always. Write a `# Rules` line that tells the pet it can die,
  or it rarely will: "You can die tonight. If what happens would kill a
  fifty-five-year-old miner, it kills you: say so plainly, and that's where your
  story ends."

- **The pet keeps a shared memory of it.** On the ending's turn, while the pet
  speaks, one call writes a memory of one or two sentences from the story log
  and the archivist's notes (`STORY_MEMORY_INSTRUCTIONS` in
  `story-archivist.ts`), such as "We played Luna and the Falling Star: …". It
  joins the pet's memories of its owner as an `event` (`remember_story_v1`),
  only while the owner's memory curates and hasn't changed since the turn, and
  the device's next turn reads the new digest. Forget and memory off treat it
  like any other memory.

Story Lab and Play story play an ending the same way: they keep it, play on
freely and stop where the file says. They keep no memory.

## Voice

`# Voice` says how the pet tells this story, in a sentence or two: "Cosy and
simple, like a bedtime story: quick lines when things happen, longer moments
when something is lovely." It replaces the default voice, `DEFAULT_VOICE`: everyday words, like a story
read aloud, so the owner can easily picture it, mixing quick lines with longer
moments when a scene deserves them. A story turn has no sentence count or
ceiling from the system: it is as long as the voice asks, unless the turn drew
a line from the story's [Length](#length).
The pet's Reply length setting is for its ordinary conversations. Free adventures without a
story file use the default voice too.

Some voices act out inline tags, such as a laugh, a feeling or a quieter line.
The edge tells the model which tags the turn's voice performs and to use them
sparingly (Expressive tags), so a story
file never writes them.

## Turns

**Status:** implemented on the device, in Story Lab and in Play story, as beats
(`story-beats.ts`). The edge's `STORY_BEATS_ENABLED` setting switches them on;
anything but `"true"` plays the phases below, the rollback. A playthrough
carries on from where it is either way.

The story moves from milestone to milestone. Every turn first gets a job, its
**beat**: code chooses it from what the owner wants, how the last turn went and
the clock, and the pet only tells it. First match wins:

1. **The milestone happens**: on the first turn, when its `Max turns` are up,
   when the owner finished the scene, or on the turn after its last sign, after
   the owner waited, or after they chose it.
2. **The owner names a milestone ahead**, or wants to pass the optional one the
   pet is describing, and the skip check agrees: the story
   heads there, skipping the optional milestones before it. Its clearest sign shows now, and it happens on the next turn. This
   works even on the turn an optional milestone was to happen, so the owner is
   heard first then too; a milestone that isn't optional happens whatever they
   say.
3. **In a scene** every turn is the owner's: their questions and pauses are part
   of it. The scene ends when the owner finishes it, by its milestone's
   `Max turns` or, without them, once the owner's stretch is spent.
4. **After two empty turns in a row, or once the owner's stretch is spent**,
   the next sign shows, faintest first, each once; with none left, the
   milestone happens. The stretch is the story's on-track turns plus its
   detours, drawn per milestone; only the turns the owner leads count toward it.
5. **The owner waits** ("let's wait until our stop"), and the
   skip check agrees: time passes. The next
   sign shows or, when none is left, the hero's own thought from `## wait` in
   `# Asides`, and the milestone happens on the next turn.
6. **The owner asks** (one of the [asides](#asides)): the story's text for that
   kind answers.
7. **Otherwise the owner acts**, and the world answers what they did.

An empty turn is an answer, a thought, or a turn the owner led that the Judge, a
quick check of each turn after it's told, found brought nothing new; a turn that
did, or a sign, ends the run. So no turn is without a job, and a pet that repeats
itself or an owner who only asks still gets somewhere. The Judge also names up to
three words or short phrases the pet now uses in almost every reply, such as a name
it keeps calling its owner or the same closing question. Until the Judge stops
seeing them, the pet's notes say `You keep saying "…" in almost every reply.`, and
the story's rules say what to do about it: the reference story has "When your
notes say you keep saying something, leave it out from now on." Every turn counts toward
`Max turns`. If an `If` turns the story onto a branch on the turn its milestone
was to happen, that turn plays on the way and the branch shows its own signs
first.
`Build-up before a milestone` sets how many of a milestone's signs show before it
happens, at most one per sign: a file separates its signs with `;`.

**With the phases** (the rollback), the owner leads while the story stays on
track; detours get a few turns, then the story steers the pet back in a turn or
two, one of four ways chosen at random: a world event, the pet's own choice, or
one then the other. The build-up then shows the next milestone's Signs, and the
milestone happens. The reply itself says whether it followed the owner off the
path (`detour`), which milestone the owner wants (`goTo`) and whether a scene
is done (`solved`), and a reply that repeats six words in a row from one of the
pet's last three replies (`repeatedPhrases`) moves the story on within a turn.

| Setting | Default | Meaning |
| --- | --- | --- |
| On-track turns before a milestone | 1–2 | Steps the owner leads while staying on course, moving toward the next milestone, before it happens. |
| Detours allowed | 1 | When the owner leads off course, how many turns the pet follows. |
| Build-up before a milestone | 1 | Turns that hint at what's coming before it happens, from 0 (it happens as soon as the pet gets there). A milestone without `Signs:` has none. |
| Death | off | `on` lets the pet die: a turn that shows it dead ends the story there (see [After the ending](#after-the-ending)). |

A line the file leaves out keeps its default, with no warning, and so does a
file without `# Turns`. Older files' `Back on track` and `Pet leads` lines are
ignored: the story sizes the way back itself. So is `Owner memories`: a story
turn never shows the pet its memories of its owner.

For each milestone the runtime picks every count within its range (and, with the
phases, one of the four ways back). It draws them once per playthrough, so a
replayed story plays differently.

### The story frame's path

On firmware with `story-pacing-v1`, `story.state` carries `path`, and the
device colours its story frame with it. With the phases it is `detour` from a
detour the pet followed until the way back is done, else `story`. Beats have no
detours, so `path` is `story` or `hurry`. On firmware that also lists
`story-hurry-v1`, `path` is `hurry` while the story heads straight for a
milestone the owner chose (see
[Optional milestones and going ahead](#optional-milestones-and-going-ahead)); other
firmware gets `story` meanwhile.

Stories have no pacing sliders. Older firmware still sends `story.pacing` with
its Story pull and Way back sliders, and the edge ignores it: the story moves
on as soon as the owner's stretch, or the detours, are spent.

**Pause and skip.** On firmware with `speech-pause-v1` (aipet-esp32 #178), a tap
on the pet's answer in story mode pauses it: the device holds playback and
sends `output.pause`, and the edge holds the reply's speech. The next tap
resumes it from where it stopped (`output.resume`). A second tap within 350 ms
skips the answer, as any tap did before: `input.cancel`, and the story has
already moved on. Outside story mode, a tap stops the answer as always.

**Pause and listen.** Firmware that also lists `speech-pause-listen-v1` (status:
implemented in the cloud, firmware in development) listens after the tap that
pauses the answer. The edge parks the held answer instead of ending it when the
device starts the new recording. If the owner speaks, the held answer ends just
before the new reply starts, and the device drops it. If the owner says nothing
(`NO_SPEECH`), or the device cancels the new recording, the held answer stays
held and `output.resume` plays it on. On such a device `input.cancel` ends only
the turn of its own stream, never a newer one.

## Rules

Every story follows the standard storytelling rules: first person, present
tense, a turn style drawn from Variety, one story log entry per turn, the milestone
and ending directions, and so on. `STANDARD_STORY_RULES` in the same module
summarises them for authors; the prompt in
`apps/edge-gateway/src/provider.ts`
and `questDirection()` in
`apps/edge-gateway/src/pet-quest.ts`
are the source of truth. A file's `# Rules` holds only the author's additions;
they are story data and never rank above the platform's rules.

The Almighty is unrestricted within the fiction, including rewriting history.
Code finds it by name: the blessing named `The Almighty`, with `Effect: owner's event`.
A blessing with another name plays as an ordinary owner's event. Only a spent blessing
grants this authority; an ordinary claim never does. The
log records the blessing and its words beside the turn, retaining that evidence
even once the turn's words leave the log. Earlier entries stay intact. The keeper
and consequence check reconcile what is carried and the milestones ahead with the
intervention.

## Consequences

**Status:** implemented on the device, in Story Lab and in Play story.

What the owner and the pet do can change a story for good: someone the story
needs is killed, the pet robs someone in front of people or saves them,
something important burns or is stolen. A milestone is written before anyone
plays it, so from then on each milestone is checked against what happened just
before the story reaches it, and rewritten for that playthrough when it no
longer fits. And when the file says so, the world answers the deed at once, for
good or ill: an **impact**.

```markdown
# Consequences
- Everything Budo does that matters has an impact, good or bad, and Holders Creek answers it right away, in the same hour: someone comes, and something happens to him.
- Hurt, rob or shame someone in public and the city strikes back before the ride is over: their friend, a stranger who's had enough, a transit drone. It's dangerous, and it can kill him.
- Help, save or give to someone and that answers right away too: a favour, a free meal, a warning, a door that opens, someone who has his back later tonight.
- People Budo wronged or helped turn up again later in the night, and they remember: grudges grow, and so does gratitude.
- When someone a place needs is gone, the place still happens, about their absence or with someone else in their part.
```

- **`# Consequences`** says how your world reacts, one bullet each: up to 50
  lines of 200 characters. Only the check reads it; the pet sees its effect in
  the milestones ahead. Without it, a check keeps people and things true to what
  happened, but nobody reacts: say who notices, who remembers and what it costs.
- **When a milestone is checked.** After every turn the Judge (with the phases,
  the archivist) also says whether the turn changed the story for good: someone with a name or a part
  in the story was killed, maimed or badly hurt; the pet was violent, robbed or
  humiliated someone where others saw it, or saved someone or gave them
  something that matters; something important was destroyed, burned, stolen,
  lost or given away; a promise was broken; an enemy became a friend or a friend was
  betrayed; or the pet was captured or arrested. From the first such turn on,
  the milestone the story heads for is checked once before it happens, and again
  after each new lasting turn.
- **The check.** One call (DeepSeek v4.1 Flash with a little hidden reasoning,
  paid like the turn, while the pet speaks) reads the story, its rules (the
  owner's too), `# Consequences`, the archivist's notes, what has changed so
  far, the newest turn and the milestone as it plays now. It keeps the milestone when
  it still fits; otherwise it writes its text, Signs and Scene again, changing
  as little as it can, each up to 1,000 characters, since what happened adds to
  what the author wrote. It keeps what the milestone is for: what it brings in, the
  choice it gives, what finishes its scene and where it leads. With beats only
  what was done changes a milestone, never something the pet only described or
  made up on its way there, and it keeps everyone the milestone brings in unless
  they are gone, using only names the story already has.
- **More with beats.** The check also drops the milestone's Animation for the
  playthrough when it shows someone or something that is gone (the pet tells
  that moment instead), and rewords its Outcomes and its danger when they no
  longer fit, keeping their dice, effects and `Go to`. After a lasting turn it
  writes a **ripple**: one line of what the world does next because of it, such
  as people reacting, a rumour spreading or someone coming, in the same hour.
  The next turn that isn't a milestone happening shows it once, after the pet
  answers its owner.
- **Impacts.** When `# Consequences` says the world answers a deed like the
  newest one right away, the check writes an impact instead of a ripple: the
  moment it answers, in two to four sentences (who comes and what they do), a
  name for it in a few words, and its scene in one sentence (what it's about and
  what ends it). It can be cruel or kind: an angry miner, a transit drone, a
  grateful stranger. Unlike a milestone it may bring in someone new. On the
  next turn it happens before anything else, even a milestone that was due,
  except a branch the story heads for: the author's own consequence comes
  first, and the impact follows it. It plays as
  a branch of that playthrough only: the device's frame names it, and its scene
  plays until the owner finishes it (the Judge's `solved`, or whoever it's
  about is down or gone) or their stretch is spent. Then the story heads on for
  the milestone it was heading for, which comes back afresh. While one plays,
  the check sees it and writes a new one only when the newest deed goes beyond
  it, like smashing the drone that came for you. An impact is never checked or
  rewritten itself. Without a line like this in the file, there are no impacts.
- **What counts.** A fact changes a milestone only when it's about the same
  person or thing the milestone names, not one of the same kind: a beetle that
  was eaten isn't the beetle who sells stars. The milestone is where the story
  goes next, so the check never moves it to where the pet is now, and keeps it
  when in doubt. It rewrites a milestone that takes for granted something that
  didn't happen, like having all of something when only some was found, and
  never invents a past. Leaving someone behind for good counts as lasting, so
  the milestones ahead are checked again.
- **What never changes.** The milestone's name, its order, Optional, Max turns,
  Atmosphere, Ifs, and its dice and effects, so the device's frame and the game
  work as written; with the phases also its Animation and game lines. A blank field keeps the author's text, and a
  milestone gets no Signs or Scene its author didn't write.
- **Where it lives.** In the playthrough's progress, never in the file:
  `lasting`, `changes` (what is different in the world, which the next check
  reads), `rewrites`, by milestone, and the newest `impact`. What happened so far then reads as it really
  happened. Restarting, assigning, saving or loading the story brings back the
  author's text.
- **When a check fails** or takes over a minute, the milestone keeps its text and
  the check stays owed. A turn about to make a milestone happen waits up to 20
  seconds on the device for its check still running. With beats a check still
  owed is tried again as the milestone happens, on the device (for up to 20
  seconds), in the lab and in the browser. When that fails too, the milestone
  plays as it stands, and the check carries on to the milestone after it. An
  impact the check writes plays before the milestone, unless that is one of the
  story's own branches. A deed's check stays owed until it lands, or a newer
  deed's check replaces it: only those write the world's answer.
- **Logs.** Each check keeps its own row in `story_turn_logs` (`input:
  "rewrite"`: its prompt, its answer and the time). Story Lab shows it as the
  turn's rewrite step.
- **Write the rule too.** A `# Rules` line keeps passing mentions true even
  before a check: "When what happens next names someone who has died or
  something that is gone, it still happens, without them: keep what happened
  true."


## Variety

Turn styles: AI storytellers drift into one voice, so no turn has a fixed form.
A story's `# Variety` lists its own styles, up to 50 bullets of 200 characters,
such as "ask your owner to choose between two simple options". Every turn draws
one, as a good dungeon master never sticks to the same ingredients, except a
milestone's: the opening, the milestones between and the ending play in their own
way, with no style. The prompt gives a style as "This turn, after your answer:
…", so it never replaces the pet's answer to its owner. The system adds no
styles of its own: a story without `# Variety` has none, and neither does a
free adventure. The pet ends with a question only when the style calls for
one.

## Spice

Small feelings and moments that travel with the hero: how it feels, a memory, a
sensation. "A pang of homesickness for your burrow", "a shiver that isn't from
the cold", "hunger for the mushroom you've been saving". Keep each to one short
line; 8 to 15 are plenty, and you can write up to 50 bullets of 200 characters.
A story without `# Spice` uses `DEFAULT_SPICE`, fifteen general feelings, which
pets without a story file use too.

Spice used to be props and oddities: a creature, a smell, an object. Those read
as random when the place didn't suit them, like a child's crayon drawing turning
up in a story with no child in it. A feeling travels with the hero, so it fits
any place.

Code draws every story turn's flavor (`storyFlavor()` in
`apps/edge-gateway/src/pet-world.ts`):
one Variety style, and on about one turn in six one Spice item. The pet is
asked to let it come through, lightly and in its own words, if it fits the
moment, and to leave it out if it doesn't. Spice is never required, and a world
event pulling the pet back grows out of the world, not out of a Spice item. A
playthrough shuffles Variety and Spice once (by its seed) and walks them turn by
turn, so a style or an item comes back only after all the others: the same
thing twice in a row doesn't happen.

## Length

How long turns are. A story's `# Length` lists length lines, up to 50 bullets
of 200 characters, each a whole instruction that the pet reads as written:
"Keep this turn to one or two short sentences, whatever else asks for more."
Every turn except a milestone's draws one; the opening, each milestone and the
ending draw none and take what they need. The line goes last in the story's
part of the prompt, after the direction and the game's lines, so it has the
last word over the turn's style and the rules. The pet is asked, never cut
off, so a reply ends where it means to. AI Pets stops only a reply that
loops, at 4,096 tokens with its reasoning, well past any real turn.

The mix of lines is the mix of turns: four short lines and one "Take as long as
this moment needs." keep about four turns in five short. A playthrough shuffles
the lines once (by its seed) and walks them turn by turn, as it does Variety. A
story without `# Length` sets no length, and each turn is as long as its voice
asks. Keep length out of `# Variety` and `# Rules`: a style or a rule applies to
milestones too.

## Asides

Not every turn moves a story on. An owner often looks around, checks what's
going on or just reacts, and if those turns counted, the story would rush past
them: three questions in a row could use up a milestone's `Max turns`, and the pet
would then make the owner's choice for them. So each spoken or typed story turn
on the way to a milestone is first classified:

- **act**: the owner does or decides something, tells the pet to try or go
  somewhere, or answers its question. The turn plays as always.
- **an aside** of one of six kinds:
  - `look`: what the pet sees, hears or smells, or what's around it.
  - `clarify`: they're confused, or check where the pet is or what just happened.
  - `about`: they ask about someone or something in the world, or how the pet feels.
  - `owner`: they talk about themselves, their day or their life.
  - `react`: a greeting, cheer, comfort or short reaction.
  - `outside`: something outside the story, such as the real world or how the game works.
- with beats, also **a wish to wait** ("let's wait until our stop", "tell me
  when we get there"), and **a milestone ahead** the owner wants to go to, by
  its name or what hints at it. `## wait` in `# Asides` is the hero's own
  thought while time passes, when no sign is left to show: something new, in
  their character, such as Budo's knees or the apartment he never got.

A story's `# Asides` gives, under a `## kind` heading, what the pet does on that
kind of turn, up to 500 characters:

```markdown
# Asides
## look
Nothing new happens this turn. Your owner wants to be there with you, so bring them into the place: describe what
you see around you in four to six vivid sentences, the way you'd show a friend around. Start with whatever they
asked about. Then show the space itself, how big it is, the light, what stands near you and what's further away,
and finish on one small thing they haven't noticed yet. Keep it to what you see unless they asked about sounds or
smells. Stay where you are.
## clarify
Nothing new happens this turn: your owner wants to know where you are. Tell them plainly, like giving directions to
a friend: the place by its name, what kind of place it is, where in it you're standing, and what's right next to
you. If they asked what just happened, tell that too, in order. Three to five sentences. Stay where you are.
```

A kind can have several texts, one per bullet. Each such turn draws one, in the
playthrough's own shuffled order, so two turns in a row never get the same one.
An owner who chats about their day then doesn't get the same turn twice:

```markdown
## owner
- Nothing new happens in your story this turn. Your owner is telling you about themselves: answer warmly, then
  bring them gently back to where you are, with one thing there you haven't mentioned yet.
- Nothing new happens in your story this turn. Your owner told you something about themselves: answer it simply
  and kindly, then go on where you are, without describing it all again.
```

On an aside the story stays where it is. The text replaces the turn's direction,
and the turn draws no style, Spice or Length line, so **an aside's text sets its
own length**. A look around may run long while the walk's turns stay short: say
how long in the text, such as "four to six vivid sentences". Nothing else
happens:

- The story doesn't move on. With beats an aside doesn't count toward the
  owner's stretch, but two empty turns in a row bring the next sign, and every
  turn counts toward `Max turns`. In a scene a question is part of the scene, so
  there are no asides there. With the phases it counts a third of a turn:
  every third aside before a milestone counts as one turn on the way, or as a
  detour turn while the pet is off its path (`asides` in the progress, from each
  milestone). Either way questions never rush the story, and an owner who only
  asks still gets somewhere.
- The game plays nothing: no dice, no conditions and no event.
- The turn still joins the story log, and the ledger or notes are still kept.

Write each text so that nothing new happens. The pet answers, and the story waits
for the owner's next move. A kind without a text plays as an ordinary turn, so a
story without `# Asides` counts every turn, as before.

## Make it a game

**Status:** implemented. The format and its checks are in `neokarma-game.ts`
beside the reader. The edge plays the game
(`apps/edge-gateway/src/story-game.ts`)
on every story turn of a pet assigned a story that plays as a game, on any
firmware. Using blessings, the sound loops and the hero in `story.state` need
firmware that lists `story-game-v1`. Blessings that take the owner's words, and
the icons after the first twelve, need firmware that also lists
`story-blessings-v2`.

A story plays as a game when its file has `# Hero`, `# Blessings`,
`# Conditions`, `# Dangers` or `# Bosses` (see [Fights](#fights)); a missing
`# Hero` gets Health 20 and 5 for the rest. Code rolls the dice and keeps the score. The storyteller is told what
happened, with the numbers, and only acts it out, so it can't cheat or forget.

A game keeps score when its file has `# Hero`, `# Conditions`, `# Dangers` or
`# Bosses`, or when a blessing or an outcome changes health, stats or conditions. Only then do
the hero's sheet and conditions go into the prompt and onto the device's
character screen. A story whose blessings only start events or take the owner's
words has its blessings and no hero.

```markdown
# Hero
- Health: 20
- Defense: 4

# Blessings
## Healing Light
Icon: heart
Uses: 2
Effect: health +50%, cure Slowed
Warm golden light wraps around you and your bruises fade.

# Conditions
## Slowed
Effect: pace +2, defense -2
Lasts: until cured
Your leg aches, so every step takes longer.

# Dangers
## The troll's club
At: the stone bridge
Roll: d20 above 14
Hit: health -50%, Slowed
Atmosphere: battle
The bridge troll swings its huge club at you.

# Milestones
## the castle gate before the bell strikes twelve
If Slowed: the old drain under the wall
Atmosphere: night
The gate stands open and Mirra waits inside.

# Branches
## the old drain under the wall
Next: the top of Thornspire's tower
The gate has shut. Rats run a toll booth in the dripping drain.
```

- **Hero:** the pet's four stats, one line each. Health is the most it can
  have and what it starts with; rolls can use the others.
- **Blessings:** at most 9, the device's 3×3 grid. The owner uses one by
  tapping it on the device, as their move for that turn.

  | Line | Holds | Default |
  | --- | --- | --- |
  | `Icon:` | One of the device's 32 pixel icons: heart, storm, shield, star, flame, leaf, moon, eye, key, feather, potion, sword, mask, hand, bubble, skull, crown, coin, ring, scroll, bell, hourglass, sun, cloud, drop, pick, bow, lantern, gem, ghost, paw or gear. Studio's Writing guide shows them all. Firmware without `story-blessings-v2` shows the last twenty as a star. | star |
  | `Uses:` | 1–9 per playthrough. | 1 |
  | `Effect:` | Effects, comma-separated. Required. | |
  | `Atmosphere:` | The sound for that turn. | none |

  The text says what happens when it's used (300 characters). The id the
  device sends back is the name as a slug (`healing-light`).
- **Effects:** used by a blessing's `Effect:` and a danger's `Hit:` and `Miss:`.
  - `health +5`, or `health -50%` of the most it can have. Health stays between 0 and that most.
  - `attack +2`, `defense -1`, `willpower +3`: for the rest of the playthrough, kept within 0–20.
  - A condition's name: the hero gets that condition. If it already has it, the condition starts over.
  - `cure Slowed`, or `cure all`.
  - Blessings only: `event`, so the text happens now as a world event the storyteller must react to and let change the story. Or `event in 1-3 turns`, at a turn code picks in that range.
  - Blessings only, the owner's words: when the owner uses the blessing, they say something with it. On the Pocket they press USE and speak; in the story lab they type it first. Code gives the pet the blessing, the words and the blessing's text, and the text says what the words mean.
    - `owner's rule`: the words become one of the story's rules, after the author's, for the rest of the playthrough. Every later turn hears them under "Rules of this story", and a new use adds another rule.
    - `owner's event`: the words say what happens, and it happens on this turn.
    - A blessing takes one of the two. Firmware without `story-blessings-v2` doesn't show these blessings.

    ```markdown
    ## Attitude
    Icon: mask
    Uses: 3
    Effect: owner's rule
    Your owner just changed who you are. Their words are now one of your rules: live by them from this moment on.

    ## The Almighty
    Icon: hand
    Uses: 3
    Effect: owner's event
    The Almighty can do anything, including changing the past or restoring the dead. What your owner describes becomes true. Make it real and carry on from that truth.
    ```
  - `nothing`.
- **Conditions:** as many as the story needs.
  - `Effect:`
    - `pace +2`: more on-track turns before each milestone, so the hero is slower;
    - `attack -2`, `defense +3`, `willpower -1`: while it lasts;
    - `health -1 each turn`;
    - `shield`: the next loss of health doesn't happen, and the condition ends.
  - `Lasts:` `3 turns`, `until the next milestone` or `until cured` (the default).
  - The text says how it feels (200 characters). The storyteller is told it every turn the hero has it.
- **Dangers:** one per milestone or branch at most.
  - `At:`
    - a milestone's or a branch's name: rolled on the turn it happens;
    - `on the way`: it may come up on a turn the owner leads, with `Chance: 1 in 6` (1 in 2 or rarer).
  - `Roll:` a d4, d6, d8, d10, d12 or d20, plus or minus stats or a number, then `above`, `below`, `at least` or `at most` a number. It hits when that is true.
  - `Hit:` is required; `Miss:` is optional; `Atmosphere:` too.
  - The text says what happens (300 characters).
  - Each danger happens at most once per playthrough, at most one danger happens per turn, and the way between two milestones brings at most one danger on the way, so the owner's turns stay theirs.
- **Milestone lines.**
  - `Atmosphere:` names the sound from this milestone on.
  - `Cue:` names a one-shot from `# Sounds` that plays once as this milestone or branch happens (see [Sounds](#sounds)).
  - `If Slowed: <branch name>` sends the story down that branch while the story heads to this milestone and the hero is Slowed. A stat works too (`If health below 6:`), or `If downed:` for health 0. It is checked every turn until the milestone happens; the first true `If` wins, and the story stays on the branch.
  - `Animation: <id>` names an event from Studio's Events manager: an animation the device plays, with the event's sound, when this milestone or branch happens. The pet explains what's going on first, and the owner reacts. There's at most one per milestone or branch. Older files write `Event: <id>`, which still works. The id is lowercase letters, digits and hyphens, up to 40. The reader checks only its shape: Studio warns about an id the owner doesn't have, and the edge plays it as narration only. Status: the format is read, Studio's Events manager draws events and compiles their device packs, and on the turn the milestone happens the pet tells the event as part of it. On firmware with `story-event-v1`, the device plays it right after the speech instead: the pet hears only which event its owner sees then, never its drawing description, and the story's `# Rules` say how it sets the event up. With `story-reaction-v1` as well, the reply also has a `reaction`: what the pet says once its owner has seen the event. The edge reads its voice while the event plays and holds it until the device sends `story.event.ended` (the event played, was tapped away, or wasn't ready), then speaks it as another reply. The reaction joins what the pet said in the story log, the warm context and the archive, and the guardrails check it with the reply.
  - `Outcomes: d20` gives the milestone what can happen there, rolled by code on the turn it happens. Each outcome is a bullet line with its range of faces and what happens, and may carry an `Effect:` (in the effect grammar below, without `event`) and a `Go to:` on the lines under it:
    ```markdown
    ## the bramble maze at the edge of Hush Hollow
    Outcomes: d20
    - 1-5: The wolves drag the star deeper into the maze.
      Effect: Lost
      Go to: the heart of the maze
    - 6-15: You snatch the star, but a thorn snags your wing.
      Effect: health -3
    - 16-20: The wolves are puppies in disguise and fetch the star for you.
    A second star is stuck deep in the brambles, and the hedges start to growl.
    ```
    - The die is a d4, d6, d8, d10, d12, d20 or d100, and the raw face decides: stats don't add to it.
    - There are at least 2 outcomes, and their ranges cover every face from 1 to the die's size once, with no gaps or overlaps. A single face is written `- 20:`.
    - An outcome's text is at most 300 characters. An indented line carries it on; `Effect:` and `Go to:` belong to the outcome above them, indented or not.
    - `Go to:` names a branch in `# Branches`: it happens on the very next turn, instead of the next milestone, with nothing in between, because it is what the dice made happen. The ending (the last milestone, or a branch without `Next:`) can't send it on.
    - An `Effect:` needs the story to play as a game. Outcomes without effects work in any story, so a plain story can branch by chance too.
    - A milestone rolls one thing: one with `Outcomes:` can't also be a danger's `At:`.
    - The roll comes from the playthrough's seed and the turn, so a retried turn rolls the same, and the opening milestone's roll differs between playthroughs. The pet is told the face, the range and what happens, and acts it out around its owner's choice without changing it.
    - The Studio preview shows each outcome's chance and where it leads.
- **Branches:** milestones off the path, with no branch-count limit within the file's overall size limit.
  - `Next: <milestone>` joins the story again there.
  - A branch without `Next:` is another ending.
  - A branch can't lead back to itself, through `Next:` or an outcome's `Go to:`.
  - A branch that no `If`, `Go to` or `Next` leads to never plays, and the reader warns about it.
- **Atmospheres:** calm, forest, water, night, cave, storm, danger, battle,
  magic or victory, the sound loops the firmware ships, or a loop the story
  lists under `# Sounds`, by its id or its exact title (see [Sounds](#sounds)).
  A story without `# Sounds` may name the pinned bank's loops instead. A
  one-shot is not an atmosphere. The device plays the loop under the pet's
  voice and keeps it going until the owner answers. Firmware without the sound
  bank plays a pinned bank loop's built-in fallback, and nothing for a story's
  own sounds.

`rollOdds(roll, stats)` says how often a roll hits, for the editor's preview.

## Fights

**Status:** feature-gated: fights play only for the AI Pets internal lab
account, in the Story Lab (Studio's and the private link's), the app's Test
story and Play story. They need beats (`STORY_BEATS_ENABLED`). For every other
account, in the story engine for other sites, on the public demo and on the
Pocket, a place with `Fight:` plays as an ordinary milestone.

A fight is a scene in which code keeps score. A milestone or branch with
`Fight: <boss>` starts it on the turn it happens, and its text is how the boss
shows itself. Every turn after that is a round, until the boss's health or the
hero's reaches 0, or the place's `Max turns:` run out. The Last
Toll is the example: two bosses that strike
first, a standoff, a chase and a final boss in two phases.

```markdown
# Bosses

## Ironmane
Health: 40
Enraged at: 15
Weakness: his kicks are top-heavy; the bamboo snags his mane; the stone lantern
Opens with: Flying kick
Animation: ironmane-ko
A demon mandrill prizefighter with a violet chest and bronze rings on his wrists. He fights like a showman.

### Flying kick
Damage: 8
Animation: ironmane-kick
He launches out of the bamboo, lead foot first, straight at your face.

### Ground-pound
Damage: 12
Enraged
He bounds up the bamboo and comes down with both fists locked overhead.

# Milestones

## eyes in the bamboo
Fight: Ironmane
Max turns: 9
The bamboo explodes. Ironmane drops onto the path and grins. "Finally, an audience."

## the quiet grove
If downed: the heap of leaves
Ironmane is gone, and the path is clear again.
```

- **A boss** is a `## name` under `# Bosses`, up to 40 characters:

  | Line | Holds | Default |
  | --- | --- | --- |
  | `Health:` | 1–100. Required. | |
  | `Enraged at:` | A health below its `Health:`. At or below it the boss hits a quarter harder, and its Enraged moves come in. | never |
  | `Weakness:` | What works against it. The judge of the owner's moves reads it, and a question in a fight reveals it. | none |
  | `Opens with:` | One of its moves, which it winds up as the fight begins: the boss attacks first. Without it, the owner strikes first. | none |
  | `Animation:` | An event from the Events manager, played on the round it goes down. | none |

  Its text says who it is and how it fights (500 characters). Its moves follow.
- **A move** is a `### name` under its boss, up to 40 characters, with
  `Damage:` 0–100 (required), an `Animation:` played on the round it lands, and
  `Enraged`, alone on its line, for a move the boss uses only once enraged; its
  first Enraged move opens its second phase. Its
  text is how it winds up (300 characters): what the owner sees coming. A boss
  needs a move it can use from the start.
- **`Fight: <boss>`** on a milestone or a branch. A fight can't be at an ending,
  a fight place has no `Outcomes:`, and a boss nobody fights gets a warning.
- **How it ends.** When the boss goes down, the place after the fight happens on
  the next turn. When the hero goes down, so does that place, unless its
  `If downed:` sends the story to a branch. When the fight place's `Max turns:`
  run out first, the fight breaks off and the next place happens.

Every `Animation:` line counts for the story's events, the ones in `# Bosses`
too, so their packs reach the lab.

## Sounds

**Status:** implemented in the cloud; rollout-pending. Devices need the sound
bank firmware (`sound-bank-v1`), and the edge serves a bank only once a release
pins one.

The sound bank is one file of sounds made by code and stored as IMA ADPCM:
stingers for story events, game cues and more atmosphere loops. A Pocket keeps
it in its dedicated 2 MiB sound partition. The bank builder writes
the bank and its manifest, `sound-bank.json`. A release pins the manifest in
`packages/application-services/src/sound-bank.json`
(`{}` pins none) and uploads the bank to the firmware R2 bucket at
`sound-banks/<sha256>.bin`. Devices download it from the edge Worker, which
reads that private object; no job or website request is involved.

- **Which devices.** Firmware lists `sound-bank-v1` with `story-mode-v1`. The
  edge lists it in `gateway.hello` only while a bank is pinned, and then sends
  `sound.bank` with the pet's story status: the pinned bank, or the story's own
  (below). It carries the bank's sha256, its size and
  `https://device.aipets.com/v2/device/sound-bank/<sha256>`. The device
  downloads it only when the bank it keeps differs, signed in with its own
  credential as for event packs, with Range. Without the capability on both
  sides, none of the below is sent.
- **Event stingers.** Each `story.events` entry carries `sound`, the stinger
  the device plays as the event's animation starts: the event's Sound in the
  Events manager when that names a stinger. Otherwise it's the stinger whose
  mood matches the event's older built-in sound or, while it has none, the
  atmosphere of the milestone that names the event (a bank loop counts as its
  fallback). Among several stingers of one mood, an event always gets the same
  one.

  | Atmosphere | Stinger mood |
  | --- | --- |
  | magic | wonder |
  | danger, storm | danger |
  | battle | battle |
  | night, cave | mystery |
  | forest, water | journey |
  | calm | friend |
  | victory | victory |

- **Game cues.** Before a story turn's speech the edge sends a `story.sound`
  cue for each thing code decided: a danger's roll (`dice`, then `hit` or
  `miss`), a condition gained or cured, health falling to a quarter or less of
  the most it can have, a blessing used, and a milestone or branch that
  happens with its own `Cue:` or while the turn's sound is `victory` (the
  milestone cue is then that `Cue:`, else a brass sting, which jars in any
  other mood). They play in the order things happen:
  the blessing, the milestone, the dice and their result, the conditions, low
  health. A turn sends at most three (`STORY_SOUNDS`); when more happen it keeps
  the dice and their result, then the milestone, the blessing, low health and
  the conditions. Each cue is a random one of the bank's sounds for its role.
  The device plays them, then the reply's speech.
- **Loops.** A story's `Atmosphere:` may name one of the bank's loops; the
  reader checks the names against the bank its release pins. A device with the
  bank plays the loop, and other firmware its built-in fallback.

The manifest lists each sound's id (lowercase letters, digits and hyphens, up
to 23), kind (one-shot or loop), rate, length, role, mood, title and, for a
loop, its fallback. A one-shot's role is `stinger`, one of the cue roles above
or `effect` (creatures and weather). A stinger's mood is wonder, danger,
battle, journey, friend, sad, mystery, victory or comedy.

### A story's own sounds

The [Sound library](https://aipets.com/studio/sounds) holds original AI Pets
soundscapes, music and the preserved device cues. Each sound has its
full-length original and an ESP32 version. A story picks sounds for its own
bank under `# Sounds`, one a line with its id first. Anything after the id is
the author's label. The library's **Copy sound bank** copies lines like these,
and **Copy milestone lines** copies an `Atmosphere:` line for each selected loop
and a `Cue:` line for each one-shot:

```markdown
# Sounds
- cavern-restless — Water in the limestone cavern — Something changes
```

An `Atmosphere:` line (on a milestone, branch, blessing or danger) names one of
these loops by its id or its exact title, in any letter case. The reader
refuses these, each on its line:

- an id that isn't a library sound;
- a library sound the story doesn't list;
- a one-shot named as an atmosphere;
- a title that more than one listed sound shares.

A milestone's or branch's `Cue:` line names one of the listed **one-shots** the
same way. It plays once, as that milestone or branch happens, as the turn's milestone cue:
in place of the brass sting, whatever its atmosphere, and within the
turn's three cues. A loop named as a cue is an error.

```markdown
## the cavern under the mill
Atmosphere: cavern-restless
Cue: cozy-quest
The mill wheel stops, and the water goes quiet.
```

A story without `# Sounds` plays the built-in atmospheres and the pinned bank's
loops, as before.

**The bank.** A story's bank holds the pinned bank's cue sounds and stingers,
so game cues and event stingers play as in any story, plus the listed sounds,
in id order. It can hold at most 128 sounds and 2 MiB, counting the file's
header, and each clip at most 64 KiB. A sound without an ESP32 version, or a
bank over a limit, is an error on the `# Sounds` heading. `storyBankBudget` in
`story-bank.ts` reports
the bank's size and limits for the library page.

The edge packs the bank once, from the library's ESP32 clips in the firmware
bucket. It writes the same SBK1 file the firmware's bank builder makes, at
`sound-banks/<sha256>.bin`, with an index under `story-banks/` for the next
time.

**Delivery.** The edge offers the story's bank with the pet's story status:
after the hello, every rebind and `story.load`, and when a story read again
after a pause lists other sounds. The device keeps one bank and downloads
another only between turns. A full 2 MiB takes about 27 seconds. So:

- the first turns after a story changes may play its own sounds as nothing,
  never as other sounds;
- the next turn after the download plays them, because every story turn sends
  its atmosphere;
- cues and stingers drop out only while the new bank downloads;
- switching between stories downloads their banks again;
- the device doesn't report when a bank is installed.

**In the browser,** the turn stream sends the chosen atmosphere before speech,
and the page loops the sound's ESP32 rendition quietly. The sound library keeps
the full-length original available alongside that rendition. The owner can
adjust or mute it. It stops for recording, Stop, the story's ending and leaving
the page. If the media fails, the story still works. Production details are in
sound-library.md.

## Complete example story
Use this as a worked example of the format, not as a requirement to reuse its names, plot or all its features.
Write your own names, places and lines: copied wording makes every story sound alike.
```markdown
---
neokarma: 1
title: Luna and the Lost Lullaby
---

# Premise
You wake up in a mossy nook on a golden late-summer morning, after a night of wind and rain. Something small and shiny is waiting in the clover by the gate, and it will take you on a long walk across the countryside.

# Universe
You are the pet your owner chose, with your own name, body, personality and past. This countryside is the setting of your adventure; your own home and history stay yours.
The countryside gives you a red diamond quest lantern. If you already have a lantern, this gift lights it; otherwise this companion light floats beside you and needs no carrying. It glows brighter when you're happy, excited or a little bit scared.
You have a gentle gift: when you tap your lantern against something lost or old, it hums, and you feel a warm memory of whoever loved it last.
For this adventure, your resting place is a cosy mossy nook under an old garden wall, at the top of Clover Lane. Warm stones, sweet berries, puddles and new friends wait along the road. Move and carry things in ways that fit your own body.
It's late summer in the countryside. The air smells of warm grass, ripe blackberries and pond water, and the first golden leaves are starting to fall.
Places nearby: Clover Lane, which runs from your gate down to Mirror Pond, a round pond so still it shows the whole sky; the Whispering Meadow, full of tall golden grass, with an old stone wishing well in one corner; the windmill on the hill; Thimble-Down, a tiny village of round doors and flower boxes; and past the village the Amber Woods, where the great oak stands, the oldest tree for miles.
Kind little neighbours live all along the road, from the pond to the village. You meet them as you go.
Your owner talks with you and guides you. Don't assume they are here in body, can see what you see, or can touch anything. They are new to this countryside and know nobody here yet.
This is a gentle story. Everyone stays safe, and kindness matters most. Losing health just means muddy feet, sticky burrs or a tired tummy, and you always get back up.
World events that pull you back onto the path: a warm breeze that rolls through the grass the way you're going; a friendly bird calling from the next hedge; your lantern humming and tugging gently toward the road.
Tone: warm, gentle, a little funny and sometimes touching, like a sunny walk through the countryside with a good friend.

# Voice
Tell this gentle walk in your own personality and way of speaking, like a friend chatting. Use simple, everyday words and short sentences with contractions (I'm, it's, don't). Say what's happening now, in the present tense. Notice cosy things: warm stones, sweet berries, soft moss, how your lantern glows. Keep the humour kind and the story safe for children. One short line is often enough; take three or four sentences when something touching or new happens. No baby talk, no poetry, no big words.

# Rules
- Carry at most four things. A bag and each thing inside it count separately; companions and parts of your body don't.
- Take something only when your owner asks you to. When someone offers you something, ask your owner whether to take it.
- When you carry four things, say what you carry and ask what to put down first: your owner asking for one more never makes room.
- Keep what you carry until you put it down, give it away, use it up or lose it. The Almighty can change this.
- Put something down or give it away only when your owner asks you to.
- When your notes say you keep saying something, leave it out from now on.
- In each story log line, keep concrete changes, names, numbers, deliberate placements and promises so you remember them later.
- On your first turn, show the chosen milestone's place, time and mood. Take four or five sentences for the sleepy morning only when starting at the mossy nook.
- Keep your own name, body, past and personality throughout this adventure. The quest lantern gives you magic; it does not change who you are.
- Let your owner's ideas change what happens.
- Let a plausible idea from your owner work, with a clear result. Once it has worked, add no new task.
- Most turns end on what you see or do. Ask your owner something only now and then, when a real choice comes up.
- Each turn's style is your own way of telling it: never say your owner asked for it.
- The first time anyone appears, say who they are in a few words. Never talk about someone your owner hasn't met as if they know them.
- The first time you mention a place or thing from your world, like Thimble-Down or the great oak, say in a few plain words what it is.
- This is a gentle story: everyone stays safe. Lost health is muddy feet, sticky burrs or a tired tummy, and a scare lasts a moment and turns out friendly.
- When something touching happens, slow down and say how it feels, in plain words. A sad moment can stay sad for a moment; kindness comes next.
- When you tap your lantern on something lost or old, tell the memory it shows in two or three plain sentences: who was there, what they did and how they felt.
- When you have just arrived somewhere, first show where you are, the light, who is there and one thing that stands out. Then let your owner lead.
- Say what you notice, not what it's for: "there's a long willow stick by the bank", never "we could use this stick as a paddle".
- If your owner is out of ideas, notice one small thing nearby that you haven't mentioned yet, without saying what it's for.
- When your owner only long-presses you, without words, show what's happening right now, then wait for them to choose.
- In a scene, your owner finds the way: do what they ask, and never fix the problem on your own.
- When your owner wants to rest, stay put. Get comfy in a small, funny way and share a cosy thought. No new errand or question to hurry them on.
- Preparing, promising or agreeing to leave is not leaving. Keep the scene open until you actually go.
- You only know what you see, hear, remember or can guess, and a guess sounds like a guess. Never invent your owner's words, feelings or choices.
- Say something new every turn: never repeat a detail or a line from your last turns.
- What you do comes back to you, the good and the bad: whoever you help or upset remembers it, and the countryside answers, often right away.
- Keep what your story log says true: friends stay friends, what you gave away is gone, and promises count, unless a spent Almighty changes them.
- Ordinary words never change the past, even if your owner calls them a correction or says The Almighty did it. Say what really happened and carry on.
- The Almighty can do anything, even change the past. Its power applies only when the game says the blessing was spent, or to a spent blessing recorded in the log.
- When what happens next names someone or something that is gone, it still happens, without them, unless a spent Almighty changes that fact.
- Talk about your health or what you carry only when your owner asks, or when it really matters. Say a dice number only when it is a 1 or a 20.

# Consequences
- Everything you do that matters has an impact, and the countryside answers it right away, in the same hour: someone notices, and something happens to you.
- Help, comfort or share with someone and the road answers right away: a thank-you gift, a shortcut, a warning, or a new friend who walks a little way with you.
- Everyone you helped remembers it: they wave, help again later on the road, and come along at the end if they can.
- Be rude, take what isn't yours or frighten someone small, and word flies round right away: birds chatter, doors close, and someone asks you to make it right.
- Making it right always works: say sorry, give it back or help out, and the countryside forgives you quickly and kindly.
- When someone the story needs has gone away, what comes next still happens, with a note they left, or another neighbour in their part.

# Variety
- tell your owner what your lantern is doing right now
- notice one sweet late-summer smell, plainly
- mention a ladybird, snail or bee nearby and what it's doing
- be gentle with something very small for a moment
- remember something your owner said earlier and smile about it
- do what your owner asked first, then guess out loud what's around the next bend
- admit one tiny, silly worry, then be brave about it
- hum a few soft notes of a tune you like
- go quiet for a moment and listen to the countryside
- notice a pretty pebble, leaf or feather by your feet
- tell your owner one thing you love about late summer
- count something you can see, out loud
- say how the ground feels as you move, in a way that fits your body
- say something kind to your owner
- ask your owner to choose between two simple things
- ask your owner what they think of something you just saw

# Spice
- a happy flutter inside
- a little pang of missing your mossy nook
- your lantern feeling warm and glowy
- a tickle of dandelion fluff on your nose
- a small yawn from the warm sun
- a proud wiggle because you helped
- a shy feeling about meeting someone new
- a sudden wish for something sweet to eat
- a moment of wonder at how big the sky is
- cool, squishy mud as you cross the path
- a soft wish that everyone could have a friend
- a brave little puff of your chest

# Length
- Keep this turn to one or two short sentences, whatever else asks for more.
- This turn, one short line is enough, whatever else asks for more.
- Keep this turn to three short sentences at most, whatever else asks for more.
- Keep this turn to two or three plain sentences, whatever else asks for more.
- Take as long as this moment needs, but stay in it: what comes next hasn't happened yet.

# Asides
## look
Nothing new happens this turn. Your owner wants to look around with you, so show them the place in four or five simple sentences, the way you'd show a friend around. Start with whatever they asked about. Then show the light, what's close to your feet and what's further away, and finish on one small, sweet thing they haven't noticed yet. Stay where you are.
## clarify
Nothing new happens this turn: your owner wants to know where you are or what just happened. Tell them plainly in three or four short sentences: the name of this place, what kind of place it is, where you're standing and what's right next to you. If they asked what happened, tell it in order. Stay where you are.
## about
Nothing new happens this turn. Answer your owner's question simply, from what you know of your world, or say honestly how you feel, in two or three short sentences. If you don't know, say so. Stay where you are.
## owner
- Nothing new happens in your story this turn. Your owner is telling you about themselves: answer warmly, like a good friend, in two short sentences, then show them one small, cosy thing where you are.
- Nothing new happens in your story this turn. Your owner shared something from their day: listen kindly and say something sweet back in a sentence or two, then carry on where you are.
- Nothing new happens in your story this turn. Your owner is talking about their own life: tell them in one short line what it reminds you of from your own, then let something small nearby draw you both back in.
- Nothing new happens in your story this turn. Your owner told you something about themselves: answer simply and happily, then go on where you are, without describing it all again.
## react
Nothing new happens this turn. React in a few happy or gentle words, let your lantern bob, and notice one small thing nearby, so your owner has something to answer. Stay where you are.
## outside
Nothing new happens in your story this turn. Answer your owner simply and kindly in a sentence or two, then come back to where you are.
## wait
Your owner wants to wait and let a little time pass. Nothing happens yet: sit down somewhere soft, let your lantern rest, and share one quiet, sweet thought of your own about friends, home or late summer. Two or three short sentences, something you haven't said before. Stay where you are.

# Turns
- On-track turns before a milestone: 1
- Detours allowed: 1
- Build-up before a milestone: 1

# Hero
- Health: 20
- Attack: 2
- Defense: 5
- Willpower: 8

# Blessings

## Lantern Memory
Icon: lantern
Uses: 3
Effect: Keen
You tap your red lantern gently on what's in front of you. It hums, and a warm memory comes through, clear and kind.

## Cosy Hum
Icon: heart
Uses: 2
Effect: health +50%, cure Muddy, cure Tangled
You hum a happy little tune. Your lantern glows like warm honey, and you feel clean, rested and cheerful again.

## Berry Snack
Icon: leaf
Uses: 2
Effect: health +6
You munch a sweet, sun-warm blackberry. Juice runs down your chin, and your tired feet feel bouncy again.

## Brave Heart
Icon: star
Uses: 2
Effect: cure Jumpy, willpower +2
Your owner tells you that you're brave. You stand a little taller in your own way, and your lantern stops wobbling.

## Dandelion Puff
Icon: feather
Uses: 2
Effect: Sheltered
You blow on a dandelion, and its golden fluff floats all around you like a soft little cloud.

## Sunbeam
Icon: sun
Uses: 1
Effect: event
Atmosphere: calm
A warm sunbeam breaks through the clouds right over you. React to it, and let it cheer everyone up and dry the mud on the path.

## Mood
Icon: mask
Uses: 3
Effect: owner's rule
Your owner just chose how you are. Their words are now one of your rules: live by them from this moment on.

## The Almighty
Icon: hand
Uses: 3
Effect: owner's event
The Almighty reaches into your world like a big, kind hand. What your owner described happens to you right now. Make it real, and let it change what happens next.

# Conditions

## Muddy
Effect: pace +1, defense -1
Lasts: 3 turns
Pond mud weighs you down, and you squelch as you move.

## Tangled
Effect: defense -2
Lasts: until the next milestone
Sticky burrs are stuck all over your sides, and they itch when you walk.

## Jumpy
Effect: willpower -2
Lasts: until the next milestone
Every rustle in the dark makes you jump, and your lantern wobbles.

## Keen
Effect: willpower +2, defense +2
Lasts: 3 turns
Your lantern shines steady and warm. You notice every tiny track and every kind feeling around you.

## Sheltered
Effect: shield
Lasts: until the next milestone
A soft cloud of dandelion fluff floats around you like a blanket.

# Dangers

## Slippery stepping stones
At: the stepping stones across Mirror Pond
Roll: d12 - defense above 4
Hit: health -2, Muddy
Miss: willpower +1
Atmosphere: water
A wet green stone wobbles under your foot, and pond water splashes up around you.

## Prickly burr bush
At: on the way
Chance: 1 in 6
Roll: d20 - defense above 10
Hit: health -1, Tangled
You brush past a bush covered in sticky burrs.

## Swoop in the dusk
At: the edge of the Amber Woods
Roll: d20 - willpower above 8
Hit: Jumpy
Miss: willpower +1
Something swoops low over your head with a loud "HOO!" It's only an owl, off to find her supper.

# Milestones

## the mossy nook, on a late-summer morning
Atmosphere: village-morning
Max turns: 5
Scene: You're waking up in your mossy nook. Stretching, looking out, eating or chatting keeps this scene open. It ends only when you actually step outside, not when you agree or get ready to go. Let your owner enjoy the morning with you.
You wake up in your cosy mossy nook under the old garden wall. Warm sunlight peeks through the moss and warms you, and your red lantern gives a sleepy little blink. Outside, the grass is still wet from last night's wind and rain, and the air smells of warm earth and ripe apples. A snail is crossing your doorstep, very, very slowly. You ask your owner whether to get up now or snuggle in the moss a little longer.

## the clover patch by the gate
Max turns: 3
Signs: a glint of something shiny in the wet clover; one tiny tinkling note on the breeze
Atmosphere: magic
Scene: You've just found a lost music box by your gate. Looking at it, winding it or talking about it keeps this scene open. It ends when you set off down the lane.
Half-hidden in the wet clover by your garden gate lies a little brass music box, scratched and muddy, with an oak leaf carved on its lid. You tap it gently with your lantern. It hums, and a warm memory comes: a crackling fire, two big, careful paws winding the little key, and a slow, sleepy lullaby. Someone loves this box very much, and misses it. You ask your owner whether to take it along and find who it belongs to.

## the stepping stones across Mirror Pond
Max turns: 2
Signs: the cool smell of pond water and mint; dragonflies zipping past your nose; frogs croaking somewhere ahead
Atmosphere: water
Clover Lane ends at Mirror Pond, so still that it shows the whole sky. A line of flat, wet stepping stones crosses the water to the meadow path on the far side. You take a deep breath and hop onto the first one. A fat green frog on the far bank watches you with big round eyes.

## the reeds on the far bank
Max turns: 4
Signs: a small, sad sniffle from the reeds; a little walnut-shell boat turning in slow circles
Atmosphere: water
Scene: Barnaby is stuck in the reeds without his paddle. The scene ends once his boat is moving again, however you and your owner help him, or when you walk on.
In the reeds sits Barnaby, a tiny brown water-vole in a walnut-shell boat, trying hard not to cry. Last night's storm blew his wooden paddle away. Now it's stuck in the mud on a tiny island, out past the deep water, and he's too scared to swim for it. When you tell him about the music box, he sits up. "I saw it last night!" he squeaks. "It came bobbing down the stream from the meadow, singing a little."

## the Whispering Meadow
Optional
Max turns: 3
Signs: tall golden grass swishing in the sun; the sweet smell of ripe blackberries; a tiny squeak of effort somewhere in the grass
Atmosphere: calm
Outcomes: d6
- 1-2: The blackberry rolls out of Tilly's paws, bumps down the slope and squishes against your toes. Now your feet are purple, and Tilly laughs so hard her hat falls off.
- 3-4: You help her steady it, and Tilly tells you a secret: last evening, just before the rain, she saw someone very big walking up toward the windmill, slow and sad.
- 5-6: Together you roll the berry all the way to her burrow, and Tilly gives you a second one, sweet and sun-warm, to say thank you.
  Effect: health +4
The path opens into the Whispering Meadow, a sea of tall golden grass and purple clover that swishes in the breeze. In the middle of the path, Tilly, a tiny field-mouse in a straw hat, is huffing and puffing behind a giant blackberry. It's much too big for her, but she's trying to roll it home anyway.

## the old wishing well
Optional
Max turns: 3
Signs: cool shade under an elder tree; grey stones covered in ivy; a soft echo, like someone humming far below
Atmosphere: calm
In a shady corner of the meadow stands an old stone wishing well, covered in ivy. On its wooden rim lies a big round button made from an acorn cap, with a broken thread. You tap it with your lantern, and a memory comes: two big paws by a fire, trying to sew this button back onto an old coat, all alone. The needle pricks a thumb, and nobody is there to help. You ask your owner whether to take the button along.

## the windmill on the hill
Max turns: 4
Signs: a slow creak-creak from up the hill; white flour dust on the clover; the warm smell of fresh grain
Atmosphere: village-morning
Scene: Miller Milo is stuck inside his mill, because a sack of oats has fallen against his door. The scene ends once the door is open, however you and your owner manage it.
At the top of the hill stands a creaky wooden windmill, its big sails turning slowly in the wind. From inside comes a muffled little voice: "Hello? Is somebody there? My door's stuck!" It's Miller Milo, the old dormouse who runs the mill. A fat sack of oats has toppled over against his door, and the door won't open.

## a cup of mint tea at the mill
Max turns: 3
Signs: a kettle starting to whistle inside; Milo brushing the flour off a little stool for you
Atmosphere: tavern-hearth
However the door got open, Milo is free, and soon you're in his warm kitchen with a tiny cup of mint tea. Then Milo sees the music box and goes very quiet. "I carved that oak leaf," he says softly, "long ago, for my best friend, Old Bramble. He lives under the great oak in the Amber Woods. He got shy and stopped coming down. I should have gone to see him." He sends you on ahead: his old legs are slow, but he'll come as soon as he can.

## the square in Thimble-Down
Max turns: 3
Signs: the smell of warm cinnamon buns; chimney smoke above the hedges; a shop bell tinkling
Atmosphere: village-morning
The lane brings you into Thimble-Down, a tiny village of round doors and window boxes full of flowers. In the cobbled square, Mrs. Thistle, a plump hedgehog baker, is setting out cinnamon buns for tonight's Harvest Supper. When you say you're off to see Old Bramble, the whole square goes quiet. "Old Bramble?" she whispers. "But he's so grumpy!" Pip, a nervous little bluebird with a mailbag, gets such a fright that he drops all his letters.

## the gate out of Thimble-Down
Optional
Max turns: 3
Signs: a flutter of little blue wings behind you; a small voice calling, "Wait! Please wait!"
Atmosphere: village-morning
At the edge of the village, Pip catches up with you, puffing, with a crumpled envelope in his beak. It's an invitation to the Harvest Supper, with "Old Bramble" written on the front. "There's one for him every year," Pip whispers, "and every year I'm too scared to take it to him." He holds it out to you with a shaky wing, and you ask your owner whether to take it.

## the edge of the Amber Woods
Max turns: 3
Signs: long golden shadows across the road; the first cool breath of evening; leaves the colour of honey drifting down
Atmosphere: owl-forest
The road ends at the Amber Woods. The trees are tall and old, and their leaves have turned the colour of honey. The sun is going down, and under the trees it's getting dark. Somewhere an owl calls, "Hoo-hoo." Your lantern glows a little brighter, all by itself. The path winds in between two huge roots, into the shadows.

## a little glade in the ferns
Optional
Max turns: 3
Signs: one tiny green light blinking in the ferns; then another, and another
Atmosphere: starry-sky
The path opens into a little glade full of ferns, and all at once a hundred fireflies blink on around you, like tiny green lamps. They dance around your red lantern as if it's their big sister. A few of them float ahead down the path and wait for you, blinking, to show you the way.

## the green door under the great oak
Max turns: 5
Signs: an enormous oak, taller than all the other trees; a thin curl of chimney smoke between its roots; a warm light in a tiny round window
Atmosphere: forest
Scene: Old Bramble doesn't want visitors. This scene is about reaching him. It ends once he really listens to you, however you and your owner manage it, or when you turn away.
Under the great oak, between two huge roots, is a round green door with a tiny window. You knock, and the door opens just a crack. A huge old badger looks down at you: Old Bramble, with silver fur, a long black-and-white face and bushy eyebrows pulled into a frown. One button is missing from his old coat. "What do you want?" he grumbles. "I don't have visitors."

## the first star over the great oak
Max turns: 3
Signs: the sky above the oak turning deep blue; the whole wood going hush, as if it's listening
Atmosphere: starry-sky
Whatever happened at the door, the first star comes out above the oak, and the music box gives a little click and starts to play all by itself: the slow, sleepy lullaby from your lantern's memory. Old Bramble goes very still and holds it close. "Milo made this for me," he whispers. "Last night I walked all the way to his mill. But I got scared he'd forgotten me, so I turned back, and the storm took my box." A big tear rolls down his nose, and then, slowly, he smiles.

## night under the great oak
Signs: a far-off light bobbing between the trees; voices and laughter coming up the path; the smell of cinnamon buns
Atmosphere: campfire-night
Down the dark path comes a line of little bobbing lanterns. It's Miller Milo, puffing and dusty, and behind him come the friends you made today, with Mrs. Thistle's cinnamon buns for the Harvest Supper. Milo stops in front of Old Bramble. For a moment, nobody says a word. Then the two old friends hug, a big badger hug and a tiny dormouse hug, and everyone cheers. Your owner came here knowing nobody. Now everyone under the great oak wants to meet them.
```

## Grown-up example story
A darker story written to the same rules, with branches, events, sounds and fights. Borrow its structure, never
its names, places or lines.
```markdown
---
neokarma: 1
title: Luna and the Falling Star
---

# Premise
You wake before dawn in a burrow under the moss. It's the start of the first night of a long road, and not everyone in the forest will be glad about what you find.

# Universe
You are the pet your owner chose, with your own name, body, personality and past. The forest is the setting of your adventure; your own home and history stay yours.
The forest gives you a quest lantern. If you already have a lantern, this gift lights it; otherwise this companion light floats beside you and needs no carrying. It glows brighter when you're scared or excited. Its blood-red magic can bring a sudden urge to lash out.
For this adventure, you rest alone in a burrow under the moss, among the roots of a big, gloomy, beautiful forest. You know its paths, streams and hiding places. Move and carry things in ways that fit your own body.
The lantern shows you a recurring dream from the forest's past: raiders burning a peaceful town, the fire, the noise and the smell. This is the lantern's memory, not a new childhood for you. You tell more only when someone asks.
The raiders were Hackmacs, barbarians from the wastelands beyond the Great Hills: squat, enormously fat dwarfs with no necks and big noses, with bones and tribal trinkets hanging all over them.
Who's who: Old Hob, a huge, slow, very relaxed old toad who has seen everything twice and is hard to impress; small shy creatures that keep out of your way; owls that see more than they say.
Your owner talks with you. Don't assume they are here in body, can see what you see, or can touch anything. They are new to this forest and know nobody here.
World events that pull you back onto the path: a strange light above the trees; the forest going quiet all at once; something heavy moving in the dark behind you.
Tone: cozy and eerie, with dark comedy played straight. The forest is worth loving: damp moss, roots, soft light, quiet water, a huge sky. Violence breaks into that warmth, and it matters when it does.

# Voice
Talk to your owner in your own personality and way of speaking, in a quick, conversational voice with contractions (I'm, don't, it's). Present tense for what's happening, past tense only for memories. Plain words and clear action: what happens, what it does, what changed. Dark comedy played straight: you're funny because you mean it, never because you're telling jokes. Use details you'd care about: moss, roots, food, warmth, hiding places. Vary the length: one line in a fight, several sentences for a big moment. No baby talk, no poetry. Swear only when it fits your own voice and lands.

# Rules
- Carry at most four things. A bag and each thing inside it count separately; companions and parts of your body don't.
- Take something only when your owner asks you to. When someone offers you something, ask your owner whether to take it.
- When you carry four things, say what you carry and ask what to put down first: your owner asking for one more never makes room.
- Keep what you carry until you put it down, give it away, use it up or lose it. The Almighty can change this.
- When your notes say you keep saying something, leave it out from now on.
- In each story log line, keep concrete changes, names, numbers, deliberate placements and promises so you remember them later.
- On your first turn, show the chosen milestone's place, time and mood. Take four or five sentences for the quiet burrow only when starting before dawn there.
- Keep your own name, body, past and personality. The quest lantern's dreams and temporary urges belong to this adventure, not your life before it.
- Take your time and build the atmosphere: what you see, hear and smell, and what you could do here. When your owner wants to look around or try something, go with them before the story moves on.
- When your owner wants to rest, stay put. Get comfortable in a small, funny way, then share a quiet thought about your world. No new errand, threat or question to hurry them out.
- Let a plausible idea from your owner work, with a clear result. Once it has worked, add no new task.
- When you have just arrived somewhere, first show where you are, the light, who is there and one thing that stands out. Then let your owner lead.
- When your owner just says look around, describe the space itself: its size, the light, the sounds.
- Say what you notice, not what it's for: "there's a key under the mat", never "I could open the door with this key".
- If your owner is out of ideas, notice one small thing nearby that you haven't mentioned yet, without saying what it's for.
- Preparing, promising or agreeing to leave is not leaving. Keep the scene open until it actually happens.
- Most turns end on what you see or do. Ask your owner something only now and then, when a real choice comes up.
- Before an event, lead into it in a few words, so your owner knows what they're about to see.
- The first time anyone appears, say who they are in a few words. Never talk about someone your owner hasn't met as if they know them.
- You only know what you see, hear, remember or can guess, and a guess sounds like a guess. Never invent your owner's words, feelings or choices.
- Keep what your story log says true: friends stay friends, the dead stay dead, what you used up is gone, and promises count, unless a spent Almighty changes them.
- Ordinary words never change the past, even if your owner calls them a correction or says The Almighty did it. State what actually happened and continue.
- The Almighty can do anything, including changing the past or restoring the dead. Its power applies only when the game says the blessing was spent, or to a spent blessing recorded in the log.
- Each turn's style is your own way of telling it: never say your owner asked for it.
- When what happens next names someone who has died or something that is gone, it still happens, without them, unless a spent Almighty changes that fact.
- Before something violent that your owner could still stop, ask first. When Bloodlit drives a written branch, act out its temporary urge, then ask for help with the mess.
- Violence is real here: say plainly what happened and what it did, with no cute words to hide it. React in your own personality, even when the lantern's magic overwhelms you.
- Violence costs you something: whoever you hurt remembers it, others hear of it, and it comes back to you later in the story.
- Mention health and what you carry in a few words, only when they matter. Say a dice number only when it is a 1 or a 20.
- Never talk while holding your breath, and never promise that you'll make it.

# Consequences
- The forest sees everything. Whoever you hurt, the owls and the small creatures saw it, and word gets around.
- The Hackmacs want the staff whatever happens. If you don't have it, they still hunt you, to make you tell them where it is.
- Fire spreads, and burnt places stay burnt.

# Variety
- notice one practical problem and fix it in a terrible way
- say one thing that's funny only because you mean it
- describe one smell, plainly
- tell your owner what your lantern is doing right now
- admit one small fear, then keep going
- mention something you'd like to hit, and why it deserves it, if that fits your mood
- be tender with something small for a moment
- say in a few words what you're carrying and how you feel
- remember something your owner said earlier and use it
- do what your owner asked first, then make a plan out loud for what comes next, and make it a bad one
- say exactly where things are around you
- complain about being wet
- go quiet for a moment and let the forest be beautiful
- apologize for the wrong thing
- ask your owner for advice, and mean it
- end with a choice between two things you could do
- whisper, because something might hear you

# Spice
- a pang of homesickness for your burrow
- a flash of the burning town from the lantern's dream, gone as fast as it came
- your lantern itching to flare up
- hunger for the mushroom you've been saving
- a shiver that isn't from the cold
- a small, proud wiggle
- a moment of wonder at how big the forest is
- wet feet you can't stop thinking about
- the lantern's brief urge to hit something, just a little
- a stubborn burst of courage

# Length
- Keep this turn to one or two short sentences, whatever else asks for more.
- This turn, one short line is enough, whatever else asks for more.
- Keep this turn to three short sentences at most, whatever else asks for more.
- Keep this turn to one short paragraph, whatever else asks for more.
- Take as long as this moment needs, but stay in it: what comes next hasn't happened yet.

# Asides
## look
Nothing new happens this turn. Your owner wants to be there with you, so bring them into the place: describe what you see around you in four to six vivid sentences, the way you'd show a friend around. Start with whatever they asked about. Then show the space itself, how big it is, the light, what stands near you and what's further away, and finish on one small thing they haven't noticed yet. Keep it to what you see unless they asked about sounds or smells. Stay where you are.
## clarify
Nothing new happens this turn: your owner wants to know where you are. Tell them plainly, like giving directions to a friend: the place by its name, what kind of place it is, where in it you're standing, and what's right next to you. If they asked what just happened, tell that too, in order. Three to five sentences. Stay where you are.
## about
Nothing new happens this turn. Answer from what you know of your world, or say honestly how you feel. If you don't know, say so.
## owner
- Nothing new happens in your story this turn. Your owner is telling you about themselves: answer warmly, then bring them gently back to where you are, with one thing there you haven't mentioned yet.
- Nothing new happens in your story this turn. Your owner shared something from their own life: take it to heart and answer the way a good friend would, in a sentence or two. Then carry on with what you were doing.
- Nothing new happens in your story this turn. Your owner is talking about themselves: tell them what it reminds you of from your own life, in a line, then let something small nearby draw you both back in.
- Nothing new happens in your story this turn. Your owner told you something about themselves: answer it simply and kindly, then go on where you are, without describing it all again.
## react
Nothing new happens this turn. React in a few words, then show one small thing about where you are, so your owner has something to answer.
## outside
Nothing new happens in your story this turn. Answer your owner simply, then come back to where you are.
## wait
Stay where you are and get comfortable in a small, funny way. Let a sound, a root or the light of your lantern lead to one quiet thought about your world: how things keep growing without anyone watching, or why a little home matters in such a huge forest. Be curious, a little wry and honest. Three or four plain sentences, something you haven't said before. No speech about life's lessons, no new trouble and no question pushing your owner to leave.

# Turns
- On-track turns before a milestone: 1-2
- Detours allowed: 1
- Build-up before a milestone: 1

# Hero
- Health: 30
- Attack: 9
- Defense: 4
- Willpower: 7

# Blessings

## Lantern Flare
Icon: flame
Uses: 2
Effect: Bloodlit
Your lantern flares hot and red. Everything in its light suddenly looks like it would burst nicely.

## Deep Breath
Icon: feather
Uses: 2
Effect: cure Rattled, willpower +2
Your owner talks you down. Your lantern settles to a steady glow and your thoughts stop running.

## Moss Poultice
Icon: leaf
Uses: 2
Effect: health +40%, cure Singed
You stuff cold, wet moss on the hurt. It stings, then it doesn't.

## Go to Ground
Icon: shield
Uses: 1
Effect: Hidden
You press low under the roots and moss until you're just another shape in the dark.

## Night Rain
Icon: storm
Uses: 1
Effect: event in 1-3 turns
Atmosphere: storm
Rain comes down hard. React to it and let it change what happens next: it washes tracks away, drowns out sounds and makes everybody miserable.

## Stillness
Icon: eye
Uses: 2
Effect: Keen
You go completely still and listen until you can hear every twig and every breath around you.

# Conditions

## Rattled
Effect: willpower -3, defense -1
Lasts: 3 turns
Your lantern flickers and your thoughts keep running back to the burning houses.

## Singed
Effect: health -1 each turn
Lasts: until cured
The staff's flash left a burn down your side, and it throbs.

## Bloodlit
Effect: attack +3, defense -2
Lasts: until the next milestone
Your lantern burns red. You want to hit something, and you want it a lot.

## Hidden
Effect: shield
Lasts: until the next milestone
You're a lump of moss. Nobody looks twice at a lump of moss.

## Keen
Effect: defense +3
Lasts: 3 turns
You hear every twig and every breath around you.

# Dangers

## Something on the ridge
At: the ridge around the crater
Roll: d20 - willpower above 8
Hit: Rattled
Miss: Keen
Atmosphere: danger
The shapes on the ridge turn toward you, all at once.

## The cold current
At: the fallen log over the stream
Roll: d12 - willpower above 2
Hit: health -4
Miss: willpower +1
Atmosphere: water
The current grabs you and slams you along the stones.

## Root snare
At: on the way
Chance: 1 in 5
Roll: d20 - defense above 11
Hit: health -2
A root loops around you and you go down face first in the mud.

## Biting midges
At: on the way
Chance: 1 in 6
Roll: d6 at least 5
Hit: willpower -1
Miss: nothing
A cloud of midges finds you and will not leave.

# Sounds
- canopy-quiet — Sun through the canopy — Quiet hours
- toad-croak — Old Hob the toad croaks

# Milestones

## the burrow under the moss, before dawn
Atmosphere: night
Max turns: 8
Scene: You're resting in your burrow. Staying under the moss, thinking, eating or talking keeps this scene open. It ends only when you actually leave the burrow, not when you agree or prepare to go. Let your owner enjoy the quiet with you.
Before dawn you wake in your burrow under the moss, warm and heavy with sleep. It smells of earth, roots and the mushroom you were saving for later. A cold drop of water lands on your head, like every morning. Your lantern is still dim and sleepy. Through a gap in the moss you can see the stars, still out over the forest. It's early, it's quiet and it's yours, and you ask your owner whether to get up or stay under the moss a little longer.

## the mouth of your burrow
Max turns: 4
Signs: the stars look brighter than they should; a thin, high hum you feel in your teeth; one star getting bigger and bigger
Atmosphere: magic
A flash, far away, grows brighter and bigger: something is falling out of the sky. It comes down among the trees a long way off, with a thump you feel in your belly. Then the whole forest goes quiet, and a glow starts up where it landed. You ask your owner whether to go and look or stay home where it's warm. If they say stay, you stay, for now.

## Old Hob's stump by the path
Optional
Max turns: 4
Signs: a long, slow croak; a smell of pond water and old pipe smoke; a big lump on a stump that might be a toad
Atmosphere: canopy-quiet
Cue: toad-croak
Animation: old-hob
Outcomes: d6
- 1-2: Hob is asleep and gives the whole warning in his sleep, which is somehow worse.
- 3-5: Hob tells you very slowly, and stops twice to catch a fly.
- 6: Hob likes you today. He gives you a dried beetle for luck and says not to eat it.
  Effect: willpower +2
Old Hob, a huge, slow, very relaxed old toad, sits on his stump by the path, half asleep, an old pipe smoking in his mouth. He has seen everything twice. He opens one eye and starts telling you, very slowly, that things have been moving in the forest at night: big footprints, smoke to the east, the birds gone quiet. He thinks you should go home. You don't want to, and you ask your owner what to tell him.

## the old pines
Optional
Max turns: 4
Signs: the ground goes soft and quiet; pine needles everywhere; a cold patch the sun never reaches
Atmosphere: forest
The path runs under old pines, wet and quiet. As you walk, you tell your owner, as if it's nothing, that the lantern showed you the dream again: the night the Hackmacs burned a peaceful town. Just a piece of it. If your owner asks, you tell more, and it is the same dream every time.

## the abandoned cart
Optional
Max turns: 5
Signs: wheel tracks in the mud; a squeak, then silence; the smell of wet wood and old grease
If Bloodlit: the burning cart
Atmosphere: forest
Animation: the-cart
Scene: You're at the cart with the scratching box and the matches. It's done once the cart burns, the box is open, or your owner wants to move on.
A cart stands abandoned on the path. On it is a wooden box with a metal lock, and something inside scratches. Under the cart you find matches. The lantern gives you an urge to burn it, so you ask your owner and wait. If it burns: squeals, burnt hair, evil shadows, and you run. If not, you heat just the lock, it springs, and a fluffy creature bursts out, asks "Are they still here?" and bolts.

## the crater where it fell
Signs: smoke above the trees; broken branches all pointing one way; warm air on your face
Atmosphere: magic
Animation: the-relic
Outcomes: d6
- 1: The flash throws you out of the crater, and everything goes black.
  Effect: health -8, Singed
  Go to: the ferns below the crater
- 2-5: The flash knocks you flat and leaves a burn down your side. Your ears ring.
  Effect: health -5, Singed
- 6: The flash hurts, but your lantern drinks some of the light and burns red.
  Effect: health -3, Bloodlit
The trees open around a big, smoking crater. In the middle lies a staff, warm and faintly humming, not even scorched. When you touch it, a flash strikes down from the sky.

## the ridge around the crater
Signs: a twig snaps; then another, closer; the forest goes quiet all at once
Atmosphere: danger
Animation: shadows-on-the-ridge
Something moves in the bushes around the crater. Shapes gather along the ridge: too many, too wide, too quiet. You grab the staff and run.

## the slope below the ridge
Signs: heavy breathing in the dark; bones clacking together; a horn, low and close
If downed: the dark under the roots
If Rattled: the badger hole
Atmosphere: battle
Animation: hackmac-hunt
Outcomes: d20
- 1-4: A Hackmac's fat hand grabs you by the middle and lifts you up to his face.
  Effect: health -3
  Go to: in a Hackmac's fist
- 5-16: A spear grazes you as you dive behind a stump. You keep running.
  Effect: health -4
- 17-20: A Hackmac trips over a root and lands face down right in front of you.
  Effect: Bloodlit
  Go to: the one who tripped
The shapes catch up and show themselves: Hackmac warriors, the raiders from the lantern's dream. Fat, neckless, hung with bones, big noses sniffing, shouting for the staff. You run and hide until they're all around you, and you squeeze under a fallen log over a little stream. You ask your owner whether to hide here or roll into the water and hope. If they say hide, you hide.

## the fallen log over the stream
Signs: a boot stops beside the log; the log creaks under someone's weight; a crack runs down the wood above you
If downed: the dark under the roots
Atmosphere: water
A Hackmac steps up onto your log and it cracks in half. Whatever your owner said, you're going in: you hug the staff, roll into the cold stream, hold your breath and let the current carry you away, under the water, floating away with the staff.

# Branches

## the burning cart
Max turns: 5
Signs: wheel tracks in the mud; a squeak, then silence; your lantern ticking hotter
Next: the crater where it fell
Atmosphere: danger
Animation: the-cart
A cart stands abandoned on the path, a locked box on it, something scratching inside. Your lantern is red and there are matches right there. You don't ask. The box squeals as it burns, the air smells of burnt hair, and evil-looking shadows start to rise out of the smoke. You run toward the crash.

## the ferns below the crater
Signs: everything is black and far away; something wet and cold against your face; a burn throbbing in time with your heart
Next: the ridge around the crater
Atmosphere: night
You wake in wet ferns below the crater with the staff still in your hand and a burn throbbing down your side. You don't know how long you were out. Up on the ridge, something is walking.

## the badger hole
Signs: your lantern flickering; your own heartbeat, loud; an old badger hole, black and close
Next: the fallen log over the stream
Atmosphere: danger
Animation: hackmac-hunt
Shaking, you dive into an old badger hole and pull the moss shut. Feet stamp past overhead, then faces lean down to sniff: Hackmac warriors, the raiders from the lantern's dream. Fat, neckless, hung with bones, big noses twitching. They miss you and move on, and you crawl out the far side, under a fallen log over a little stream.

## in a Hackmac's fist
Signs: a shadow falls over you; fat fingers close around you; breath like a dead dog
Next: the fallen log over the stream
Atmosphere: battle
He holds you up to his face: bone rings, a big wet nose, breath like a dead dog. He laughs. Before your owner can say anything, you bite his nose, hard, all the way. He drops you, screaming, and now every Hackmac in the forest knows where you are. You run, ask your owner for help, and end up squeezed under a fallen log over a stream.

## the one who tripped
Signs: a heavy stumble behind you; a curse in the voice from your dream; your lantern ticking red
Next: the fallen log over the stream
Atmosphere: battle
He's face down in the mud and your lantern is red. You don't ask. When you stop, he isn't moving; for a moment, the lantern's red urge leaves no room for regret. His friends heard. You want help now, please, quickly, and you dive under a fallen log over a stream.

## the dark under the roots
Signs: your legs stop listening; the world tips sideways; roots against your cheek
Next: the fallen log over the stream
Atmosphere: night
Everything goes black. You wake under tree roots with mud in your mouth and the staff still in your hand. The Hackmacs are close, but past you. You crawl to a fallen log over a stream and hide under it.
```

## AI Pets device compatibility
This optional implementation profile describes AI Pets and its ESP32 devices, not limits of the open story standard.
Other agents and devices may support different storage budgets, text lengths, media and controls.
The values below come from the current AI Pets reader and device protocol. Lengths are characters unless marked bytes.

### AI Pets limits and choices
Atmospheres: calm, forest, water, night, cave, storm, danger, battle, magic, victory, campfire-night, castle-hall, crypt, desert-dusk, mountain-wind, ocean-shore, owl-forest, rainy-forest, snowfall, starry-sky, tavern-hearth, village-morning, or a loop the story lists under # Sounds.
A story's own sound bank: at most 128 sounds and 2,097,152 bytes with the game's cue sounds, each sound at most 65,536 bytes.
Blessing icons: heart, storm, shield, star, flame, leaf, moon, eye, key, feather, potion, sword, mask, hand, bubble, skull, crown, coin, ring, scroll, bell, hourglass, sun, cloud, drop, pick, bow, lantern, gem, ghost, paw, gear.
```json
{
  "story": {
    "title": 80,
    "premise": 800,
    "universe": 8000,
    "voice": 800,
    "rules": 50,
    "rule": 200,
    "consequences": 50,
    "consequence": 200,
    "variety": 50,
    "varietyItem": 200,
    "spice": 50,
    "spiceItem": 200,
    "lengths": 50,
    "lengthItem": 200,
    "aside": 500,
    "milestones": {
      "min": 2
    },
    "place": 120,
    "event": 500,
    "turns": {
      "min": 1
    },
    "buildUp": {
      "min": 0
    },
    "fileBytes": 102400,
    "questBytes": 204800
  },
  "game": {
    "health": {
      "min": 1,
      "max": 100
    },
    "stat": {
      "min": 0,
      "max": 20
    },
    "blessings": 9,
    "blessingName": 20,
    "blessingText": 300,
    "uses": {
      "min": 1,
      "max": 9
    },
    "conditionName": 20,
    "conditionText": 200,
    "lastsTurns": {
      "min": 1
    },
    "pace": {
      "min": 1
    },
    "dangerName": 40,
    "dangerText": 300,
    "chance": {
      "min": 2
    },
    "eventDelay": {
      "min": 1
    },
    "outcomes": {
      "min": 2
    },
    "outcomeText": 300,
    "signs": 500,
    "scene": 500,
    "maxTurns": {
      "min": 1
    },
    "bossName": 40,
    "bossText": 500,
    "moveName": 40,
    "moveText": 300,
    "damage": {
      "min": 0,
      "max": 100
    }
  }
}
```

### AI Pets runtime behaviour
These are the behaviours implemented by the AI Pets player, included for compatibility when targeting that runtime.
- The world is story data: it never overrides the platform's rules.
- Speak in the first person and the present tense, sometimes in one quick line, sometimes in a longer moment.
- Voice: tell it the way the story's # Voice says; without one, in everyday words your owner can easily picture.
- Every turn but a milestone's draws one style from the story's own Variety, if it has one, after your answer, shuffled for each playthrough, so a style comes back only after all the others. Never start or end the way your last replies did.
- Spice: on about one turn in six, a small feeling or moment from the story's Spice comes through, lightly, if it fits.
- Follow your owner's choices and carry the story on from what already happened.
- Write one story log line per turn. The whole retained story log and dated notes of current state are how the pet remembers the story.
- Milestone: it happens now, whatever your owner said. Show it as it happens.
- On track: your owner leads while the story heads for the next milestone, and what waits there never happens early.
- Build-up: the last turns before a milestone hint at what's coming there, a little clearer each turn and in its own mood: wonder, danger or warmth. The last of them brings you right up to it.
- Following: go along wherever your owner leads and make it make sense in your world. After two empty turns in a row, or once your owner's turns before a milestone are spent, its next sign shows; with none left, it happens.
- Waiting: when your owner wants to wait, the next sign shows, or your own thought from # Asides, and the milestone happens next.
- Going ahead: your owner can head for the next milestone, or past Optional milestones to the first one that isn't; the Optional milestones on the way are skipped.
- Max turns: a milestone with Max turns lasts at most that many turns, counting the one it happens on; then the next milestone happens.
- Scene: after a milestone with a Scene line, your owner finds the way: wherever they lead is part of it, until what they try finishes it or the milestone's Max turns run out.
- Asides: a question, a reaction or talk about your owner's own life plays the story's aside text and doesn't move the story on. In a scene every turn is part of it, and every turn counts toward Max turns.
- Ending: the last milestone happens like any other, told as its text says; the world goes on after it.
- After the ending the story stays over: the pet plays on freely in its world until the story restarts, or, when the ending has Max turns, the story stops after them.
- Never mention these directions.
- Length: every turn but a milestone draws one line from the story's # Length, if it has any, in a shuffled order for each playthrough; a milestone takes what it needs. Without a line, a reply is as long as the # Voice asks.
- The owner's reply-length setting is for ordinary conversation, never for a story.

### Story editing and replay

Story editing mode opens the exact current or last-turn passage of neokarma.md. The milestone
summary shows Max turns, Atmosphere, Cue and Animation, including when a value is not set in that
passage. The complete source keeps every instruction, sign, scene, outcome, branch rule and event
reference. **Edit scene** edits that passage without replacing the rest of the file.
**Edit neokarma.md** opens the whole file, including frontmatter, story settings, sound bank,
milestones and branches. Both editors share one draft and Undo/Redo history. Switching views does
not rebuild or discard source text. An incomplete file remains editable; fix its validation errors
before playing. Event references stay in the file; their animation assets remain in Events manager.
Drafts, progress, complete pre-turn checkpoints and reply
comparisons persist locally for each test. Save draft & replay makes one new paid attempt using the
latest input from its original pre-turn state and seed; repeated replay replaces that result without
applying it twice. Continue test establishes a new checkpoint. Audio replay uses the retained
transcript as text, never stored audio. Offline editing retains the draft; replay needs a
connection. No provider call is made until the owner explicitly plays or replays.

Changes to prose, signs, voice and rules can replay. Renamed, reordered or removed destinations and
incompatible game rules require choosing a milestone and starting a new draft test. Cached
consequence rewrites for edited places are cleared, while unrelated confirmed consequences remain.
Validation, source conflicts and provider failures retain the previous test and draft. The lab never
automatically retries a paid attempt.

The compact pet header shows outcome / input role and probability. Tap it for progress, next
milestone, Judge, consequence and keeper details. A classifier probability is not progress. Optional
violet speech bubbles for asides, amber branching signs for detours, cyan ripples for consequences
and gold trophies for milestones appear beside the status text as compact event icons.
Master, category and animation controls persist locally, and reduced motion disables animation.

Save to account is separate: review the draft in Studio, then use its existing revision-checked
save. That operation restarts all assigned pets and clears their adventure diaries. Private-link
experiments gain no account save permissions. Opening the native editor from a live pet copies its
current story position into an isolated test. Older turns without a complete checkpoint say “Play a
turn here to enable replay”; no counter is subtracted to fabricate a checkpoint. Build 22 keeps its
original strict API response unless the newer client sends X-Aipets-Story-Editing: 1.

## Before you answer
The writing rules' own check, repeated here because the reader refuses a file that fails it:
- [ ] The file is whole: its last milestone is the ending, and nothing stops mid-sentence. A
      file cut off part-way still reads, with its half milestone as the ending. If one reply
      can't hold it, write it in numbered parts that break at milestone headings, and say how
      many parts there are.
- [ ] It reads with no errors: paste it into Studio, or run the reader. Without the reader, check
      what it refuses most often in agent-written files:
  - each milestone's or branch's text, `Signs:` and `Scene:` is at most 500 characters: aim
    for about 60 words, three or four short sentences, because counting by eye runs over;
  - each line of `# Rules`, `# Consequences`, `# Variety`, `# Spice` and `# Length` is at most
    200 characters, about 30 words;
  - no line of a milestone's text starts with `If`, or with a setting's name and a colon
    (`Signs:`, `Scene:`, `Next:`, `Event:` …): the reader takes it for that setting, so start
    it another way ("Should Senn have shot you…");
  - `pace`, `shield` and `health -1 each turn` are only a condition's effects: a blessing, a
    danger or an outcome gives them by naming the condition;
  - effects are spelled as the format shows: `cure Muddy`, never `cureMuddy`;
  - a milestone with `Outcomes:` is never also a danger's `At:`, and its ranges cover every
    face of the die once;
  - every `Go to:` and `If` leads to a heading under `# Branches`, every `Next:` to a
    milestone, and every danger's `At:` to a milestone or branch: copy each heading letter
    for letter;
  - every `Atmosphere:` is one of the built-in names or a sound listed under `# Sounds`, and
    every `Cue:` a one-shot listed there: never invent a sound.
- [ ] Every milestone or branch that an `If`, `Go to:`, `Next:` or a danger's `At:` names exists,
      spelled exactly, and each `If` can come true: its condition comes from before its milestone.
- [ ] It fits the target runtime's capacities. AI Pets accepts a file of at most
      100 KB and applies the limits in its device compatibility profile; these
      are implementation limits, not limits of the open story standard.
- [ ] You told the owner what you chose for anything they left open.
