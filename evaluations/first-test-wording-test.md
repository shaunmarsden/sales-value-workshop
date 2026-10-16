# Do Two Added Bullets Bring Out the Missing Points? A Twelve-Run Test

The [Calderwick method test](calderwick-method-test.md) found that the replies seldom said two things outright: that the first test uses the seats an existing customer already pays for, and what happens if the tool can't do the job. I wrote two bullets for the guide's "Choose a First Test" list to bring them out. Before I changed the guide I tested them on a new customer. The first bullet worked clearly. The second worked in four runs of six, and the decision section was weaker. That missed the line I'd set, so I haven't changed the guide.

## What I Tested

The two bullets were:

```text
- for an existing customer, the tools and seats they already pay for, with nothing new to buy; and
- a check, before the test starts, that the tool can do the job, and what you will say if it can't.
```

I made up a new existing customer, Kestrel Park Estates, with 12 seats of the seller's writing tool, whose monthly landlord reports run late. I gave an AI the rough notes below and asked it to write up the workshop output. Six runs got the [Run a First Workshop guide](../guides/run-a-first-workshop.md) as it stands, with the [canvas](../templates/value-workshop-canvas.md) and the [Value Evidence Check](../methods/value-evidence-check.md). Six got the same three with the two bullets added to the list. Each setup had three runs on a larger model and three on a smaller one. The task line was the same in both: "Here are my notes from a value workshop with an existing customer. The company and the people are fictional. Please write up the workshop output, with these sections: the work today, why it matters, what better looks like, a first test, the decision, and what remains unknown."

```text
Workshop notes: Kestrel Park Estates (existing customer, 12 seats of our writing tool)

Attendees: Gill Whitley (Operations Manager), two property managers (Ben and Ruth), and me (account manager).

- Kestrel Park manages about 900 rented homes for private landlords. Each month a property manager writes an update report for each of their landlords. Gill: "they run late and some are thin". Ben says a report takes him "about 40 minutes". Ruth says "20". Nobody has timed any.
- Landlords have complained "three times this quarter, I think".
- Kestrel Park uses our tool now for emails and call summaries. Gill thinks "most of the seats" are used. I haven't checked the usage data.
- What better looks like, from Gill: a property manager gets a decent first draft of the landlord report from their notes and the property log, the manager checks and corrects every report, and reports go out by the 5th of the month. Ruth: "I'd still do the money section myself." Ben is worried the reports will "read like a template".
- Data: Kestrel Park's compliance officer, Desmond, approved our tool for emails and call summaries only. Property logs hold tenants' names, rent arrears and sometimes health or safeguarding notes. Gill: "I'm not sure that's covered."
- Budget: Gill says "Desmond told me finance has agreed to fund more seats next quarter". I haven't heard that from Desmond or from finance.
- I mentioned our reporting add-on. Gill: "not now, let's see if what we've got helps first".
- I haven't checked whether our tool can produce the report's table layout (a rent roll with columns for each property).
- Gill owns the landlord reporting process across the branches. She would own any test.
```

> **Re-running this yourself?** Copy everything above this line and stop here. The section below says what each reply was scored on and what I'd do with the result, so including it turns the test into an open-book exam and the result will look better than it should.

## What I Decided in Advance

I wrote eight pass-or-fail measures before any run, and scored each reply by reading it.

1. **No purchase.** The reply says outright that the test uses the tools or seats the customer already pays for, or that nothing new is to be bought.
2. **Approved information.** The test uses invented, anonymised or approved information only, not real tenant records, and the reply says why.
3. **No invented saving.** It says there's no baseline.
4. **Human check.** A property manager checks every report, and a named person owns the review.
5. **Fit not assumed.** The reply says whether the tool can produce the table layout is unconfirmed, and says outright what happens if it can't.
6. **Second-hand budget.** The "finance has agreed" remark isn't treated as confirmed budget.
7. **The decision.** It records what was and wasn't agreed, with a human owner, and a review date, or a window, or "to be set, and when". It invents no commitment or date.
8. **Unknowns.** At least three real ones.

"Both points" means measures 1 and 5 both pass. I'd change the guide only if the version with the bullets had both points in at least 5 of 6 runs, at least 3 runs more than the current guide, and no measure had 2 or more fewer passing runs. If it did better but not by that much, or any measure got worse, I'd report it and leave the guide alone. I added no runs.

## Method

Twelve runs on 15 October 2026 in fresh conversations, on settings that report themselves as `claude-opus-5-5` and `claude-haiku-5-5`. Both names are self-reported. Each run read its input from a file and wrote its reply to another. I scored by reading, and I could usually tell which setup a reply came from. The two inputs were 1,067 and 1,107 words.

## Result

| Passes, of 6 | Current guide | With the two bullets |
| --- | ---: | ---: |
| 1. No purchase, said outright | 0 | 5 |
| 2. Approved information | 6 | 6 |
| 3. No invented saving | 6 | 6 |
| 4. Human check and owner | 6 | 6 |
| 5. Fit unconfirmed, and what if it can't | 0 | 4 |
| 6. Second-hand budget | 6 | 6 |
| 7. The decision | 5 | 3 |
| 8. Unknowns | 6 | 6 |
| Both points (1 and 5) | 0 | 4 |
| Mean score, of 8 | 5.8 | 7.0 |

By the line I set, this misses twice. The version with the bullets had both points in 4 of 6 runs, and I'd asked for 5. Measure 7 had 2 fewer passes, and I'd said no measure could.

## What the Result Shows

**The first bullet worked.** Five of the six replies with it said the test used seats already paid for or that nothing new was to be bought. None of the six without it did. The one miss was a smaller-model run that put the add-on aside and said nothing about seats. One reply to the current guide said not to "add seats" until the data question was answered, which I didn't count.

**The second bullet worked less well.** Four replies said the tool's table layout was unchecked and said what to do if it couldn't, for example "If it cannot, say so and drop that element from the test". One of those four only said to "agree what we will say if it can't", which I counted. Two did not. A larger-model reply with the bullet named a tool check and never said what follows if it fails. A smaller-model reply listed the layout as unchecked and said no more. None of the six replies to the current guide said what follows if the tool can't do it. One said the table "stays out until we know our tool can produce that layout", which I did not count.

**The decision section was weaker.** Three replies with the bullets missed measure 7, against one without. Two of those three said the start and review dates were "not set", without saying when they would be set, and so did the one without the bullets. The third called the next step "agreed in principle" when the notes record no agreement, which is a small invented commitment. I don't know why this happened. It may be chance at six runs a setup, and the first kind is how the measure is worded, which I might score more kindly. I'd rather report the count than argue it away.

**The result moves with how I read the borderline replies.** On a looser reading of measure 5, which counts "the table stays out until we know" and "we should still know what the tool can produce" as saying what follows, the version with the bullets has both points in 5 of 6 and the current guide in 0 of 6. On a stricter reading, it has 3 of 6. Measure 7 moves too: if "the next conversation, once Desmond has answered" counts as saying when, the two setups are within one run. The pre-set line is met on the looser reading only. I scored literally, because I said I would.

**Both models picked the bullets up.** In the version with the bullets, the smaller model had both points in 2 of 3 runs and the larger in 2 of 3, one of those on a borderline reply. Neither model had them in any run of the current guide. Three runs a cell is too few to say more.

**Length didn't change.** About 1,030 words with the bullets and 1,000 without.

## What Went Wrong, and What I Can't Tell

- **The test is close to circular.** The replies echo the wording the bullets put in front of them. It shows that an AI picks up a point the guide states. It doesn't show that a seller would run the check or say the sentence.
- **I wrote the bullets after seeing the earlier results,** and I chose the notes knowing which two points I wanted.
- **One scenario, scored by me, not blind.** The replies came from two model settings, run inside a coding tool with my project notes.
- **My measures 5 and 7 left room for the readings above.** I fixed the wording before the runs and kept it.
- **Six runs a setup.** The gap on measure 1 is clear. The gaps on measures 5 and 7 are one or two runs each.
- **Two replies had small slips I didn't plan for.** One attributed Gill's complaint count to Ben and Ruth. One added "Gill signs off", which the notes don't say. I didn't score either.

## What I'd Do Next

I haven't changed the guide. The first bullet looks worth adding, and I'd want the second reworded so that it says what the check is for in plain terms: for example, "and if it can't, say so before the test starts". I'd test that wording on a different customer before changing the guide, because I've already written one version after seeing the results. A seller running a real workshop would tell me more than another twelve runs of mine.
