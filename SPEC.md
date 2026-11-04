# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: `BRAND-001` implemented; awaiting learning-record review and commit/PR handoff.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Implementation kept; learner review, commit, PR, merge, and optional publishing remain.
- Next small decision: Name and one-sentence promise for the selected audience.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                                            | Secondary audience                                                        |
| ------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| Person in a concrete situation        | A fashion-conscious man preparing for an evening with friends               | A young professional attending an after-work networking event             |
| Goal or meaning they seek             | Feel put together without looking too casual or try-hard; stand out subtly  | Look polished and sophisticated without feeling overdressed or too formal |
| Concern before choosing               | A shirt that appears ordinary or effortful rather than clean and effortless | A shirt that reads either too informal or unnecessarily formal            |
| What the page should help them decide | Whether the shirt and fit support a polished night-out look                 | Whether the shirt can bridge smart-casual networking attire               |
| Evidence or assumption                | Assumption; not validated                                                   | Assumption; not validated                                                 |

## Early brand brief

| Decision                                 | Agreement                                                                                                                                                 |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Brand name                               | Iced-T                                                                                                                                                    |
| One-sentence promise                     | Iced-T brings effortless style to the classic white tee, helping you look fresh, feel confident, and stand out without trying too hard.                   |
| Primary archetype: the brand's character | Ruler; Hero may support the character as needed                                                                                                           |
| Three voice traits                       | Confident, polished, effortless                                                                                                                           |
| One example line in this voice           | Never Loud. Always Noticed.                                                                                                                               |
| Learner's predicted audience effect      | The visitor may feel stylish, self-assured, and attracted by the idea that a simple white T-shirt can create a strong impression without trying too hard. |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                               |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | “Never Loud. Always Noticed.” / “The classic white T-shirt. Effortless style for evenings, friends, and rooms where first impressions matter.” / “Choose your size” |
| Modernist preview, reference, and annotations     | [modernist.html](public/explorations/modernist.html); Josef Müller-Brockmann, [MoMA](https://www.moma.org/artists/4182-josef-muller-brockmann)                      |
| Postmodernist preview, reference, and annotations | [postmodern.html](public/explorations/postmodern.html); David Carson, [designer archive](https://davidcarsondesign.com/)                                            |
| Chosen direction and reason                       | Modernist; confidence through simplicity, clean layouts, minimal colors, and strong typography so standing out does not require flash                               |
| Original SVG logo                                 | [wordmark.svg](public/assets/wordmark.svg); ICED-T, black lettering, thin blue underline                                                                            |
| Monochrome and small-size variants                | Same SVG works as a one-color wordmark; black lettering presentation reviewed at navigation size                                                                    |
| Logo review at actual use size                    | Kept by learner after revised actual-size presentation                                                                                                              |
| Shared palette, typography, spacing, and assets   | Not chosen yet                                                                                                                                                      |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle                | Actual copy or interaction                                                                   | Visitor benefit / factual support                                                          |
| ------------------------ | -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Reciprocity              | “Reveal a free evening styling tip” gives an optional one-layer, clean-shoe suggestion       | Uses advice as the offered value; no purchase condition or unsupported product claim       |
| Commitment / consistency | Voluntary “I want an effortless look” checkbox displays a matching simple styling suggestion | The next suggestion follows the visitor’s stated preference without enrollment or pressure |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                              | Issue / PR                                                           | Actual checks and observations                                                                                                                                                                                                                  |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | [Storefront](public/index.html), [style guide](public/styleguide.html), [logo](public/assets/wordmark.svg), and [SPEC.md](SPEC.md) | [Issue #2](https://github.com/Jovandon9/is117-brand-studio/issues/2) | Final `npm run check`: formatting passed, 7 server tests passed, and 10 Chromium/axe browser tests passed; learner observed a clean/trustworthy/demo-like first impression, selected the implementation, and reported keyboard/mobile behavior. |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.
