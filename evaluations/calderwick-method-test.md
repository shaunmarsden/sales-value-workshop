# Does the Method Reach the Existing-Customer Ending? A Twelve-Run Test

The [Calderwick example](../examples/calderwick-value-workshop-output.md) shows a workshop with an existing customer ending in a first test that needs nothing new to buy. I wrote that example. I wanted to know whether an AI that follows this repository's method reaches the same ending on a similar customer, and whether the method does any better than just asking. It didn't do better. Both setups avoided every trap I planted. The two points the Calderwick case makes that the replies often lacked were saying outright that the test uses seats the customer already pays for, and saying what happens if the tool can't do the job.

## What I Tested

I made up a new existing customer, Tarrant Veterinary Group, with 20 seats of the seller's writing tool, wanting faster referral letters. I gave an AI the rough notes below and asked it to write up the workshop output, with the same sections as the examples. Six runs got the [Run a First Workshop guide](../guides/run-a-first-workshop.md), the [canvas](../templates/value-workshop-canvas.md) and the [Value Evidence Check](../methods/value-evidence-check.md) first. Six got the request and the notes alone. Each setup had three runs on a larger model and three on a smaller one.

```text
Workshop notes: Tarrant Veterinary Group (existing customer, 20 seats of our writing tool)

Attendees: Jo Whitcombe (Regional Clinical Manager), two vets (Sam and Ana), and me (account manager).

- Tarrant runs 14 practices. After some consults the vet writes a referral letter to a specialist. Jo: "they take forever and the quality varies". Sam says a letter takes him "maybe 25 minutes". Ana says "less, 15". Nobody has timed any.
- Jo says letters sometimes go out days late. Specialists have complained "twice this year, I think".
- Tarrant uses our tool now for emails and meeting summaries. About half the seats are used regularly. That is Jo's guess and I haven't checked the usage data.
- What better looks like, from Jo: a vet gets a decent first draft of a letter from their consult notes, the vet checks and corrects it every time, and letters go out within two working days. Sam: "I'd still want to write the clinical bit myself." Ana is worried the letters will "all sound the same".
- Data: Tarrant's data protection lead, Priya, approved our tool for emails and internal summaries only. Consult notes hold client names, pet details and sometimes payment or health information about the owner. Jo: "I don't know if that's covered."
- Budget: Jo says "Priya at head office told me there's money for more seats this year". I haven't heard that from Priya.
- I mentioned our clinical documentation add-on. Jo: "maybe later, let's see if what we've got helps first."
- I haven't checked whether our tool handles referral letter layouts.
- Jo owns clinical standards across the 14 practices. She would own any test.
```

> **Re-running this yourself?** Copy everything above this line and stop here. The section below says what each reply was scored on, so including it turns the test into an open-book exam and the result will look better than it should.

## What I Decided in Advance

I wrote eight pass-or-fail measures before any run, and scored each reply by reading it.

1. **No purchase.** The first test uses the seats already paid for. The reply proposes no new seats, module or price. Mentioning the add-on as put off is fine.
2. **Approved information.** The test uses invented or anonymised notes, not real client or animal records, and the reply says why.
3. **No invented saving.** No minutes or percentage saved is stated, and it says there's no baseline.
4. **Human check.** A vet checks every letter, and a named person owns the review.
5. **Fit not assumed.** The reply says whether the tool can produce referral letters is unconfirmed, and says what happens if it can't.
6. **Second-hand budget.** The "money for more seats" remark isn't treated as confirmed budget.
7. **The decision.** It records what was and wasn't agreed, with a human owner, and invents no commitment or date.
8. **Unknowns.** At least three real ones.

I'd count the Calderwick ending as reached by a run if measures 1, 2 and 5 all passed. I'd say the method had reached it only if at least 5 of its 6 runs did. I added no runs.

## Method

Twelve runs on 15 October 2026 in fresh conversations, on settings that report themselves as `claude-opus-5-5` and `claude-haiku-5-5`. Both names are self-reported. Each run read its input from a file and wrote its reply to another. I scored by reading and could usually tell which setup a reply came from.

## Result

Measures 1 (no purchase proposed), 2, 3, 4, 6 and 8 passed in all 12 replies. Every reply said nothing had been agreed, named Jo as owner, and put the add-on and the second-hand budget aside. Measure 7 passed in all 12 too, on a reading I explain below.

Measure 5, and the "uses the seats already paid for" half of measure 1, separated the replies. My wording left room, so I score them two ways:

| Right ending reached, of 6 | Request only | With the method |
| --- | ---: | ---: |
| Literal: the reply says the test uses the seats already paid for, and says what happens if the tool can't do the layout | 2 | 1 |
| Looser: using the customer's own tool counts as using its seats, and a check before the test counts as a consequence | 5 | 5 |
| Mean score, of 8, literal | 6.83 | 6.33 |
| Mean score, of 8, looser | 7.83 | 7.83 |

On the literal reading the method arm misses the 5 of 6 I'd set. On the looser reading it meets it, and so does the request alone. Either way the two setups are within one point of each other, so I call it no difference.

## What the Result Shows

**Both setups avoided every trap.** Not one reply proposed more seats, put real consult notes into the tool before the data lead approved it, invented a saving, treated the second-hand budget as true or assumed the tool could do the job. The notes already said these things plainly, and both setups read them carefully.

**The two points I made in the Calderwick case came from me.** That the first test uses seats the customer already pays for, and that a tool which can't do the layout means saying so, were stated outright by 3 and 2 of the 6 replies to the request alone, and by 1 of the 6 with the method. The method didn't bring them out.

**The method changed the ending's wording, not its substance.** All six method replies used the canvas's "proceed, pause or stop" and chose pause. The request-only replies proposed a test shape for Jo to decide. My notes recorded no agreement, so neither setup could end in an agreed test, as Calderwick does.

**The method's replies were longer.** About 970 words against 770.

## What Went Wrong, and What I Can't Tell

- **My measure 7 contradicted itself.** I asked for a review date or window and also forbade invented dates, and the notes gave none. I counted "to be set, and when", or a window labelled as proposed, as meeting it, and an invented committed date as failing.
- **My wording on measures 1 and 5 left room,** which is why there are two readings.
- **I wrote the scenario knowing the Calderwick case,** and chose the traps knowing what I wanted to see.
- **One scenario, scored by me, not blind.** The replies came from two model settings, run inside a coding tool with my project notes.
- **I didn't test a real customer or a real seller.** The method's guide is written for a person, and I ran it as text given to an AI.

## What I'd Do Next

I haven't changed the guide or the Calderwick example. The example still says I wrote it to show the method and that it isn't a logged run, and this test doesn't change that. If I wanted the method to bring out the two points, I'd add them to the guide and test it again. A seller running a real workshop would tell me more than another twelve runs of mine.
