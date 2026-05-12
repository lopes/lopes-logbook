# Editorial Lines

Personal error log for English writing. Each entry records a recurring mistake, its cause, and the fix. Grouped by category — not by post — so patterns accumulate over time.

---

## False Cognates (PT → EN)

Mistakes caused by direct translation from Portuguese that produce a different meaning in English.

| Wrong | Right | Why | Source |
| ----- | ----- | --- | ------ |
| "the gains I just **exposed**" | "the gains I just **described**" | *expor* → expose (uncover something hidden), not present/describe | Detection-as-Code, Then What? (2026-04-07) |
| "helps the team to **escalate** engines" | "helps the team **scale**" | *escalar* → scale (grow), not escalate (intensify/raise urgency) | Detection-as-Code, Then What? (2026-04-07) |
| "the rule in an **envelop**" | "the rule in an **envelope**" | *envelope* is the English noun; *envelop* is a verb (to wrap/surround) | Detection-as-Code, Then What? (2026-04-07) |
| "I **can't be different**" | "I'm **no different**" | *não posso ser diferente* → "I'm no different" (same as everyone else) | Detection-as-Code, Then What? (2026-04-07) |
| "**laboral** and boring work" | "**tedious**, boring work" | *laboral* (PT/ES) has no English equivalent; use *tedious*, *menial*, or *labor-related* depending on sense | Plain-Text Accounting With Claude (2026-05-13) |
| "what Steven Yegge **told**" | "what Steven Yegge **said**" | *contar/dizer* in PT both translate to *tell/say*; English *tell* needs a recipient ("told me"), *say* does not | Plain-Text Accounting With Claude (2026-05-13) |
| "I was **hearing** Estranged on Spotify" | "I was **listening to** Estranged on Spotify" | *ouvir* → both *hear* (passive) and *listen to* (active); music is always *listen to* | Plain-Text Accounting With Claude (2026-05-13) |
| "**fatidic** session" | "**fateful** session" | *fatídico* → *fateful* (consequential, ominous); *fatidic* is archaic/rare in English | Plain-Text Accounting With Claude (2026-05-13) |
| "in his **participation on** the podcast" | "during his **appearance on** the podcast" | *participação* → *appearance/guest spot*, not direct *participation* for talk shows/podcasts | Plain-Text Accounting With Claude (2026-05-13) |
| "**face** this transformation **as** the new typewriter" | "**treat** this transformation **as** the new typewriter" | *encarar como* → *treat as* / *see as*; *face as* is not idiomatic | Plain-Text Accounting With Claude (2026-05-13) |
| "right when things broke, **see in the next lines**" | "right when things broke, **more on that below**" | *veja nas próximas linhas* → English uses *below* / *later in this post*, not literal "next lines" | Going YOLO With Claude Code (2026-05-12) |

---

## Articles & Prepositions

Small but frequent errors around articles (*a/an/the*) and prepositions (*of/on/to/in*).

| Wrong | Right | Rule | Source |
| ----- | ----- | ---- | ------ |
| "monitoring **an** specific part" | "monitoring **a** specific part" | *an* before vowel sounds only; *specific* starts with /s/ | Detection-as-Code, Then What? (2026-04-07) |
| "tracked by **other** tool" | "tracked by **another** tool" | *another* = one more singular; *other* needs a plural or article | Detection-as-Code, Then What? (2026-04-07) |
| "keep track **on** them" | "keep track **of** them" | fixed phrase: *keep track of* | Detection-as-Code, Then What? (2026-04-07) |
| "not enforced **to** all engineers" | "not enforced **on** all engineers" | enforce something *on* someone | Detection-as-Code, Then What? (2026-04-07) |
| "in **minor** scale" | "on a **smaller** scale" | scale takes *on*, not *in*; *minor* is for importance, not size | Detection-as-Code, Then What? (2026-04-07) |
| "not experts **git**" | "not **Git** experts" | adjective order: modifier before noun; proper noun capitalized | Detection-as-Code, Then What? (2026-04-07) |
| "refer to IDs **than** names" | "refer to IDs **rather than** names" | comparisons of preference use *rather than*, not *than* alone | Detection-as-Code, Then What? (2026-04-08) |
| "context window was higher **then** 50%" | "context window was higher **than** 50%" | *then* = time/sequence; *than* = comparison. Constant trap | Plain-Text Accounting With Claude (2026-05-13) |
| "consuming **less** tokens" | "consuming **fewer** tokens" | *fewer* for countable nouns, *less* for uncountable; tokens are countable | Plain-Text Accounting With Claude (2026-05-13) |
| "kept **in the loop always**" | "kept **in the loop forever**" / "**always in the loop**" | adverb placement: English puts frequency adverbs before the prepositional phrase or replaces with a stronger word | Plain-Text Accounting With Claude (2026-05-13) |
| "smarter **everyday**" | "smarter **every day**" | *everyday* (one word) = adjective ("an everyday task"); *every day* (two words) = adverb ("happens every day") | Plain-Text Accounting With Claude (2026-05-13) |
| "expensive software **of** wait" | "expensive software **or** wait" | typo for *or*; not a rule, just a hygiene point — proofread short words | Plain-Text Accounting With Claude (2026-05-13) |
| "the faucet **of** your kitchen" | "your **kitchen faucet**" | English prefers possessive noun-compound order over PT-style *of*-phrases for everyday objects | Plain-Text Accounting With Claude (2026-05-13) |
| "I'm impressed **on** how nice" | "I'm impressed **by** how nice" | *impressed by* (the cause) / *impressed with* (the result); never *impressed on* | Plain-Text Accounting With Claude (2026-05-13) |
| "put them **in practice**" | "put them **into practice**" | fixed phrase: *put X into practice* (movement preposition, even when figurative) | Plain-Text Accounting With Claude (2026-05-13) |

---

## Sentence Structure

Errors in clause construction, punctuation between clauses, adverb placement, and parallel structure.

| Wrong | Right | Rule | Source |
| ----- | ----- | ---- | ------ |
| "I don't need to cover the basics, **they're well written**" | "...the basics**; they're** well written" | comma splice: two independent clauses need a semicolon, period, or conjunction | Detection-as-Code, Then What? (2026-04-08) |
| "that's optional**;** a side project for periods..." | "that's optional**,** a side project for periods..." | semicolons join independent clauses; an appositive takes a comma | Detection-as-Code, Then What? (2026-04-08) |
| "it'll help you scale, it'll make audits easier, **because** it'll improve..." | "...scale, make audits easier, **and** improve..." | parallel lists use *and* for the final item; don't repeat *because* mid-list | Detection-as-Code, Then What? (2026-04-08) |
| "engineers **usually are not** Git experts" | "engineers **are usually not** Git experts" | adverbs of frequency (*usually*, *often*, *rarely*) go between the auxiliary and main verb | Detection-as-Code, Then What? (2026-04-08) |
| "Claude **and me** were re-sorting" | "Claude **and I** were re-sorting" | subject pronoun (*I*) for subject of verb; *me* is for objects. Trick: drop the other party — "me was re-sorting" is wrong | Plain-Text Accounting With Claude (2026-05-13) |
| "checkpoints that **allows** you" | "checkpoints that **let** you" / "**allow** you" | subject-verb agreement: plural antecedent (*checkpoints*) takes plural verb | Plain-Text Accounting With Claude (2026-05-13) |
| "ability **of AI recovering** the file" | "**AI's ability to recover** the file" | English uses possessive + infinitive (*X's ability to Y*), not *of X Y-ing* (Portuguese gerund pattern) | Plain-Text Accounting With Claude (2026-05-13) |
| "stuff that otherwise I'd judge infeasible **due to the lack of time I had**" | "things I'd otherwise judge infeasible **given how little time I have**" | post-modifier overload — restructure with *given* or *because* + clean clause; avoid stacking *of*-phrases | Plain-Text Accounting With Claude (2026-05-13) |
| "I have my concerns **but** I'm pumped anyway" | "I have my concerns**, but** I'm pumped anyway" | coordinating conjunction (FANBOYS: *for/and/nor/but/or/yet/so*) joining two independent clauses needs a comma before it | Going YOLO With Claude Code (2026-05-12) |
| "maybe **later I go for** OpenFinance connectors, not now" | "maybe **later I'll go for** OpenFinance connectors, not now" | future intention in English needs an explicit modal (*will*/*'ll*); PT uses bare present for near-future plans, English does not | Going YOLO With Claude Code (2026-05-12) |
| "recovering the data from **it's** own logs" | "recovering the data from **its** own logs" | *it's* = contraction of *it is* / *it has*; *its* = possessive. Constant trap — grep before publish | Going YOLO With Claude Code (2026-05-12) |
| "two days of **back and forth** with Claude" | "two days of **back-and-forth** with Claude" | when used as a noun, *back-and-forth* takes hyphens; bare *back and forth* is an adverb | Going YOLO With Claude Code (2026-05-12) |

---

## Draft Hygiene

Notes left in the file that would have published as-is.

| Issue | Fix | Source |
| ----- | --- | ------ |
| `What to write:` / `Direction:` preamble left in body | Delete before publishing; use `<!-- TODO -->` comments for private notes | Detection-as-Code, Then What? (2026-04-07) |
| `QUESTION: How to ensure only certain teams...` inline note | Resolve or remove; HTML comments won't render in Quarto | Detection-as-Code, Then What? (2026-04-07) |
| `(review this link, should be internal)` inline note | Same as above | Detection-as-Code, Then What? (2026-04-07) |
| Missing YAML frontmatter entirely (no `title`, `description`, `date`, `image`) | Add frontmatter before drafting body; pre-commit validates required fields | Plain-Text Accounting With Claude (2026-05-13) |
| Generic placeholder slug `log/ai/` — too vague for the actual topic | Rename directory to descriptive slug (e.g., `log/plaintext-accounting-claude/`) before first commit | Plain-Text Accounting With Claude (2026-05-13) |
| `xhigh effort` — non-standard term left in published meta line | Use documented Claude Code effort levels (*low*, *medium*, *high*); proofread shorthand before publishing | Plain-Text Accounting With Claude (2026-05-13) |
| Typo cluster: *postponning*, *convertions*, *unsuccessfuly*, *rationle*, *typewritter*, *breath* (for *breathe*) | Run a spell-check pass on the full draft before submitting for review | Plain-Text Accounting With Claude (2026-05-13) |
