# Primitive Conceptual Predicates

The purpose of this repository is to systematically identify and document Primitive Conceptual Predicates.

## What are Conceptual Predicates?

There can be many different concepts relating the same entities:
- John is the father of Sam.
- John is taller than Sam.
- John likes Sam.

Each entity has a different role in the concept. If we swap their roles, the meaning changes.
- Sam is the father of John.
- Sam is taller than John.
- Sam likes John.

> e.g. Lojban; in Lojban a Conceptual Predicate is a tanru or a gismu or a lujvo. Roles are places in Lojban gismu (but roles aren't necessarily assigned positionally).

Languages associate a Conceptual Predicate to a particular morphological word form (the letters/sound/symbol for the word, separate to any meaning) to provide vocabulary. Conceptual Predicates are not specific to any language, so they do not include a morphological word form (although they may be given as examples or used to help communicate the concept).


## What are Primitive Conceptual Predicates?

A Conceptual Predicate is primitive if:
- It cannot be separated into more primitive concepts without loosing it's meaning
- It does not conflate orthogonal meanings
- Its meaning cannot be constructed by other existing Primitive Conceptual Predicates

> e.g. Lojban; in Lojban a Primitive Conceptual Predicate is a gismu.

For example, the concept "to give" involves a giver, a gift and a recipient. None of these elements of the "to give" relationship can be removed without it loosing its meaning. The reason for giving the gift (christmas, birthday, charity, etc.) does not need to be conflated with the "to give" relationship.

For example, the concept of "eat" or "ingest" or "consume" involves an eater, and food. Saying something "is food" does not remove the role of the eater from the relationship (otherwise it isn't food anymore), it just leaves it unspecified. It doesn't make sense to break down this relationship more. Also, this relationship does not need more concepts conflated with it (e.g. conflate time into the word like "eating" vs "ate").

If a Conceptual Predicates conflates some orthogonal concepts, then it is difficult to communicate the individual concepts conflated together.

> e.g. Lojban `fenki`: I'd argue crazy/insane are the same, but are probably separate from frantic/frenzy.

Scalar variations (opposite/negation or variation of intensity/strength) are an example of things that can be constructed.

> e.g. Lojban `citno` vs `nalci'o` vs `tolci'o`:

> e.g. Lojban `gleki` vs `tolbadri`, `badri` vs `tolgleki`:

> e.g. Lojban `fenki` vs `tolracli`:

Lots of concepts can be explained with many words.

## Why do this?

Building an intended Conceptual Predicate to communicate some particular meaning is difficult if concepts are not separated atomically. When orthogonal concepts are separate, they can each be added as appropriate.

Additionally, it would be inefficient to have a word for every combination of concepts.
If you have 5 atomic concepts, needing only 5 words. If you wanted to assign words for each pair of concepts, there are 10 different pairs needing 10 words.
This grows exponentially. If you have 10 concepts, you have 45 pairs.

When complete, this set of Primitive Conceptual Predicates can provide a well documented vocabulary of concepts, ready to be mapped to morphological word forms.

## What is the method for doing this?

Systematically examine each Conceptual Predicate with a series of questions.
These answers form documentation defining and justifing each Primitive Conceptual Predicate.

### Justify this is Primitive

- Is it a primary/atomic concept? Is it tangled with some concept that should be orthogonal? Can you think of an example where the concept is orthogonal?

- Consider if key words in the definition were replaced with (near) synonyms, would it introduce some orthogonal meaning?

> e.g. Lojban `citka`: Defined as `eat` vs `consume` vs `ingest`. Is it about bringing food into digestive system? Or about absorbing nutrition from it?

- Is it the opposite/negation or variation of intensity/strength of another Primitive Conceptual Predicate?

- What are the best attempts to construct this Conceptual Predicate with other Primitive Conceptual Predicates?

> e.g. Lojban `linto` vs `cmalu grake`, `tilju` vs `barda grake`:
> The base gismu should be something like "x1 has mass". I think `grake` is the best fit. Weight is not mass so `junta` is wrong.

### Justification of roles included/excluded in the concept?

- Are all of the roles essential to the concept? Can any roles be separated to an orthogonal relationship?

> e.g. Lojban: The "under conditions" places are examples of being orthogonal to the core concept of the gismu.

- What is an example of an entity which fills each role in the predicate?

> e.g. Lojban: What do each of the places mean as a sumti? What are translations for: `lo broda`, `lo se broda`, `lo te broda`, `lo ve broda`.

- What plausibly important things were excluded? Is the core concept complete?

- Can you think of examples of two destinct aspects of the concept that both best fit in the same role? In other words, is any role overloaded?


### Define the Primitive Conceptual Predicate in detail

After justifying this word should exist, rather than the alternatives.
Now we need to explicitly explain how it differs from each alternative or similar word.

- What are examples of when this Predicate does or does not apply?

- What distinguishes this Primitive Conceptual Predicate from similar/related Primitive Conceptual Predicates?

- Are there any Primitive Conceptual Predicate that have potentially similar places? How do they differ?

> e.g. Lojban `lo fasnu` vs `lo se gasnu` vs `lo rinka` vs `lo se bredi`;
which of these is equivilent to "an event"? Why?

The definitions of these Conceptual Predicate should explain how these differ from each other.

> e.g. Lojban `fenki` vs `bebna`; can bebna x1 be an event?

> e.g. Lojban `zgana` vs `catlu`; how do these differ? the distinction is not clear from in the definitions.

- Can you think of an example where swapping this Conceptual Predicate for the potentially similar Conceptual Predicate would cause the bridi to change from true to false.

### Check the definition is culturally neutral

- Does it refer to any culture specific icons or customs?
- How does the definition tie to current technology, which may change in the future? Is a flying car still a \jbo{karce}?
- Would it work for an alien culture?

> e.g. Lojban `terdi`: is this Earth specifically? Would an alien race call their home planet `terdi`?
> I would expect a definition like "x1 is a terrestrial planet" (with maybe some other places like "...in system x2...", etc.).
> Earth would then be the human terrestrial planet, `remna terdi` or some lujvo of that.
> This would be similar to the way lojban names countries, `sralo gugde` = Australia.

## How to contribute

Contributions are welcome.

Please create a pull request with any changes.

By providing a contribution you are agreeing to license your work under the same license (CC-BY-SA-4.0).

## Can a logical language use Conceptual Predicates which are not primitive?

Yes. One could say "this concept is not atomic, it is composed of these other two concepts, but we decide it is important enough to be a first class anyway".

Can we say "lets have this word because it would be super convenient, despite it not being primitive".


