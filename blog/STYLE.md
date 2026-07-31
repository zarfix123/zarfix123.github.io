# Dennis Freyman, Blog Voice & Style Guide

Derived from close reading of the three existing posts:

- `posts/blog-entry-1.html`, *Failing at Quant Trading (and What It Taught Me)* (Jun 15, 2026)
- `posts/who-verifies-the-verifier.html`, *Who Verifies the Verifier?* (Jun 18, 2026)
- `posts/make-your-value-obvious.html`, *Make Your Value Obvious* (Jun 26, 2026)

This is a description of what the writing *actually does*, not a prescription. Use it to keep new
posts sounding like the same person wrote them.

*(This doc deliberately contains no em dashes in its own prose. See §3b.)*

---

## 0. How to use this doc

**Voice is fixed. Structure is not.**

- **§3, §3b, §4, §6, §8 are rules.** Vocabulary, no em dashes, sentence rhythm, persona, HTML
  conventions. These hold for every post regardless of subject. Breaking them makes it sound like
  someone else wrote it.
- **§1, §2, §5, §7 are observations.** They describe what the first three posts happened to do,
  because all three happened to be single-lesson pieces. They are not a mold. If a post carries two
  lessons, weave them. If it needs a different arc, use a different arc. Structure follows the
  material.

The failure mode to avoid is writing to the template instead of to the story.

## 1. The macro shape (observed, not required)

The first three posts all follow the same eight-beat arc, mostly because each argues exactly one
thing. Useful as a default when a post has one lesson. Ignore it when it doesn't.

1. **Name the abstract thing and call it interesting.** No scene-setting, no hook. Just start talking.
2. **Give the background.** What you were doing and why, in plain terms.
3. **Narrate chronologically.** What you built, what you tried, in order.
4. **The complication.** The moment it went wrong, or the objection you didn't see coming.
5. **Analyze why.** This is where the real thinking is. Usually the longest stretch.
6. **One numbered list.** Three items. The concrete lessons, problems, or options.
7. **Generalize past the specific domain.** "This lesson goes much further than hackathons."
8. **Forward-looking personal close.** What's next for you, with a light touch.

The posts are **essays with a thesis**, not diary entries or recaps. Each one argues something.
Even the quant post, nominally a story about losing money, is really an argument about unconscious
incompetence.

**Length: the first three posts run 632 / 922 / 983 words.** That's the band for a single-lesson
post, and going much past 1,000 on one lesson usually means padding. A post carrying two threads
earns more room. Judge by whether every paragraph is doing work, not by the count.

## 2. Openings

The first sentence names a concept and flags it as worth thinking about. Three for three:

> "Feels weird writing a blog, it's almost like a diary but for old people haha."
> "Verification is such an interesting concept."
> "A hackathon is an interesting thing."

Then sentence two immediately grounds it in something concrete. The move is **abstract to concrete
within two sentences.** Never open with a scene, a quote, or a dramatic reveal.

**Copy the move, not the sentence.** This is the easiest way to get it wrong. "A hackathon is an
interesting thing" and "Verification is such an interesting concept" are the same *pattern*, but
writing "X is an interesting thing" for a new post is a near-literal reuse and reads as recycled.
Note that opening #1 (the quant post) doesn't use the formula at all, so there is real range here.
Other openings that fit the voice without repeating it:

- Name what the thing claims to be, so the post can undercut it: "YC Startup School markets itself
  as a weekend of talks."
- A wry observation about the situation you're in (the quant-post move).
- A flat factual statement whose implication is the hook.

Before publishing, put the new first sentence next to the other three and make sure it doesn't
rhyme with any of them.

## 3. Signature vocabulary

Words and constructions that recur enough to be fingerprints:

| Tic | Examples |
|---|---|
| **"interesting"** | "such an interesting concept", "an interesting thing", "a really interesting thing", "It's an interesting question". The single most characteristic word. Used as a hedge that opens into analysis. |
| **"The thing is,"** | "The thing is, that's not what matters at a hackathon." Also "The thing with these hackathons…" |
| **"So"** as sentence/paragraph opener | "So now how do you verify…", "So now, the dilemma:", "So essentially the idea was…" |
| **"Essentially"** | "Essentially my idea was…", "So essentially the idea was…" |
| **"Also"** as paragraph opener | "Also, as far as software security clearances…", "I also realized…", "Also in the domain of quant…" |
| **"Although"** opening a sentence | "Although we had the coolest tech…", "Although Beacon has value in its own way…" |
| **"I'd say"** | "I'd say we built it pretty well", "I'd say out of the 3 problems…" |
| **"Upon"** | "Upon reading through it", "upon testing with that same CS department" |
| **"pretty"** as intensifier | "pretty far", "pretty good track record", "pretty awful", "pretty well" |
| **"and such"** | "some rough testing with Claude and such" |
| **"yea"** (never "yeah") | "and yea that's gonna be a bunch of loss" |
| **"Makes sense" / "Cool."** | Standalone two-word reactions used as paragraph punctuation. |

Do **not** use: "Furthermore", "Moreover", "arguably", "perhaps", "delve", "landscape", "leverage"
(as a noun). The register is smart-person-talking, not essay-class.

## 3b. HARD RULE: no em dashes in prose

**Never use an em dash in body text. Not one.** This is confirmed by the data: across all three
posts there are zero em dashes in prose. The only `&mdash;` occurrences anywhere are the
`&mdash; Dennis Freyman` separator in `<title>` tags (site-wide template boilerplate) and a single
figcaption. Body prose: zero.

Where a writer would reach for an em dash, Dennis uses one of:

| Instead of an em dash | He writes |
|---|---|
| Parenthetical aside | A comma splice: "Not a competitor I'd looked at and dismissed, one I had genuinely never heard of" |
| Dramatic pause before a reveal | A full stop: "Here's the thing though. Neither of them changed what I'm doing." |
| Appositive / restatement | A comma, or just a new sentence |
| Bracketed list inside a sentence | "and" chains: "long sales cycles and broke customers and procurement" |
| Emphasis break | Actual parentheses, or nothing |

The comma splice is the workhorse here (see §4). It does most of the work an em dash would, and it
sounds spoken rather than edited. When in doubt, break it into two sentences.

## 4. Sentence rhythm

Long, comma-spliced, run-on sentences that track how he actually talks, punctuated by very short
ones for landing.

> "Essentially my idea was, let's say the stock bounces off a resistance line, you take a long for
> it to hit your next line above, but if it comes back, and every time it comes back, you just sell
> there, and get a 'flat'."

Then:

> "Cool."
> "Little did I know, we were so very wrong."
> "The **value** is obvious."

**The comma splices are not errors.** They are the voice. Do not clean them up into tidy
independent clauses, it kills the spoken quality. But keep the short landings short. The contrast
is what makes the rhythm work.

## 5. Structural mechanics

- **No `<h2>` headings.** The template offers them; all three posts ignore them. A post is an
  unbroken run of `<p>` tags with one list in it. Keep it that way.
- **Exactly one `<ol>` per post**, almost always **three items**, introduced by a short
  colon-terminated line on its own:
  - "So now, the dilemma:"
  - "There are three main problems with building something like this at a hackathon:"
  - "I learned the importance of looking out for 3 big things especially in ML-related stuff:"
  - List items vary wildly in length. One is a single clause, another runs four lines. Don't
    force parallelism.
- **No `<ul>`.** Only ordered lists.
- **Bold appears roughly once per post**, on the single key concept: `<strong><em>spread</em></strong>`,
  `<strong>value</strong>`. It marks the word the whole post is about. Don't spread emphasis around.
- **Arrow notation for process flows**, inline in prose, rendered `-&gt;`:
  > "You record a video -> we use Claude vision to pick keyframes -> we do arithmetic…"
  > "I'm working on a problem -> my agent asks other agents in my company/team…"
- **Paragraphs run 3 to 6 rendered lines.** Occasional one-line paragraph to set up a list.

## 6. Persona rules

- **Willing to look dumb, on purpose.** "my smartass obviously thought I was better and smarter
  than that." "Little did I know, we were so very wrong." "Unconscious incompetence really is a
  thing." The self-deprecation is load-bearing, it buys credibility for the analysis that follows.
- **"We" for Tolus and hackathon work** (with Hao, referred to by first name only). **"I"** for solo
  projects and for opinions.
- **"You" for generalized advice.** "you have to make value obvious", "you get picked off".
- **Name-drop with the credential in parentheses, casually, at the end of an anecdote.**
  > "That guy was Kenny Zhang (3x YC)."
- **Digits, not spelled-out numbers.** "3 projects", "3 to 5 minutes", "1st", "+427% YTD", "$100,000".
- **One casual aside per post, in parens or with lol/haha/:)**, but only one. It's seasoning.
  > "(Sorry, I just binged all of Silicon Valley lol)"

## 7. Endings

Never ends by restating the thesis. Ends on **what's next for me**, with a light touch:

> "…Specifically I'm really interested in looking into crypto funding arbitrage bots and futures."
> "…I'd rather be one of the Pied Pipers instead of one of the Hoolis. (Sorry, I just binged all of Silicon Valley lol)"
> "But I can't end on a loss of course, so we'll see how CalHacks goes in October :)."

Note the last one explicitly comments on the act of ending. That kind of meta-wink is in range.

## 8. HTML conventions

Copy `posts/_template.html`, then match the existing posts exactly:

- Typographic entities in body prose: `&rsquo;` apostrophes, `&ldquo;`/`&rdquo;` quotes,
  `&larr;` in the back link, `&gt;` in arrows.
- **`&mdash;` is title-only.** The `<title>` tag uses a literal em dash character:
  `Post Title — Dennis Freyman`. That separator is on every page of the site, so keep it.
  It is the *only* place an em dash belongs. Never in `<p>` text. See §3b.
- Add `<meta name="description">`, one sentence, same text reused as the blurb in `blog/index.html`.
- Back link: `<a class="back-link" href="../index.html">&larr; all posts</a>`.
- `<p class="post-meta">Month DD, YYYY</p>` under the `<h1>`.
- Body goes in `<div class="post-body">`.
- Images, when used, go in `<figure>` + `<figcaption>` (see the verifier post).
- **Register the post** by adding an `<a class="post-feature">` card at the *top* of the
  `.post-cards` div in `blog/index.html` (newest first), with date, title, and blurb spans.

## 9. Quick self-check before publishing

- [ ] **Zero em dashes in the body?** (`grep -n '&mdash;\|—' <file>` should match only the `<title>` line.)
- [ ] Is every paragraph doing work? (Length is fine if yes. Padding is the actual enemy.)
- [ ] Does it argue something, or is it a recap? (Must be the former. One lesson or several,
      but they have to be woven, not stacked.)
- [ ] Is there a moment where I admit I was wrong or didn't know something?
- [ ] Exactly one `<ol>`, ~3 items, introduced by a colon line?
- [ ] Zero `<h2>` tags?
- [ ] Bold used once, on the key concept?
- [ ] Does the last paragraph look forward instead of summarizing?
- [ ] One aside/joke, not three?
- [ ] Did I say "interesting" at least once? (Genuinely, it's the tell.)
