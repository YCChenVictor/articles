# Thresholds for Constitutional Change: Population-Based Models and Proposals

## Real-World Models: Approval Thresholds Tied to Population

In many countries, constitutional adoption or amendment via referendum
requires more than a simple majority of votes cast -- the threshold is
explicitly linked to the total electorate (or population). **Table 1**
highlights several examples of such population-based thresholds:

  | **Country / Case** | **Population-Based Approval Threshold** | **Context and Outcome** |
|-------------------|----------------------------------------|-------------------------|
| **Taiwan (current rule)** | **Absolute majority of all eligible voters must approve** | Constitutional amendments need >50% of *all* voters in favor. This ultra-high bar, added in 2005, has made amendments extremely difficult. |
| **United Kingdom (Scotland devolution, 1979)** | **40% of the entire registered electorate required to vote “Yes”** | A majority voted yes (51.6%), but that was only ~33% of the electorate, so the devolution law failed. A *Yes* needed at least 40% of all voters – an example of an absolute electorate threshold. |
| **Italy (referendums)** | **50% turnout quorum required for validity** | For abrogative referendums, at least half of registered voters must participate. If turnout is below 50%, the referendum is invalid. (E.g. a 2005 fertility law referendum saw 79% *Yes* votes, but only ~26% turnout, so it failed.) |
| **Poland (constitutional referendum)** | **50% turnout minimum for binding result** | The Polish Constitution stipulates that a referendum on constitutional matters is valid only if over half the electorate votes. (Turnout below 50% means the result has no legal effect.) |
| **Denmark (constitutional changes)** | **Yes votes from >40% of all voters typically required** | Historically, Denmark’s constitution required a yes from at least 45% of registered voters. In 1939 a new constitution passed 91.9%–8.1%, but only 44.5% of the electorate voted yes, so it failed. The current 1953 Constitution eased this to a majority yes *and* ≥40% turnout threshold. |
| **Lithuania (pre-2002 law)** | **Yes by >50% of all registered voters** | Until 2002, any referendum needed more than half of the *entire* electorate voting yes to be binding. This extremely high bar meant most proposals failed. (The rule was later relaxed to one-third of voters for most issues.) |


**Table 1: Selected cases of constitutional referendums with thresholds
tied to total voters or population.** These mechanisms require either a
**majority of the electorate** or a **minimum turnout** (participation
quorum) in addition to a majority of votes cast, ensuring that a change
has support from a substantial share of all citizens, not just a slim
voting majority.

Such requirements are designed to confer greater legitimacy on major
constitutional decisions. For example, Taiwan's post-2005 rules make any
amendment impossible without at least 50% of all eligible citizens
agreeing. In new democracies or sensitive votes (independence,
sovereignty, etc.), absolute electorate majorities have been used to
demonstrate undeniable popular support. Lithuania's 1991 independence
referendum, for instance, was deemed successful only because about **¾
of all voters** participated and over 90% voted yes -- roughly 68% of
the entire electorate in favor, clearing a two-thirds electorate
threshold for secession. Similarly, Montenegro's 2006 independence vote
set a high bar (55% yes with at least 50% turnout) to ensure broad
consensus. And in the U.K., the 1979 devolution referendums showed how a
population-tied threshold can thwart a change even if a voting majority
favors it, because the **total** electorate backing did not meet the
required fraction.

However, these strict thresholds come with pitfalls. Critics note they
**bias the status quo** by making change harder; a non-vote effectively
counts as a "no." In Scotland (1979), many argued the 40% rule "rigged"
the result against devolution. Turnout quorums can also induce strategic
abstention: opponents may **boycott the vote** to invalidate the result.
This *"no-show paradox"* is well-documented -- if people know low
turnout will sink the proposal, then not voting is equivalent to voting
no. For example, in Italy and Poland, organized abstention campaigns
have defeated referendums by keeping turnout below the required 50%,
even when a majority of those who did vote were in favor. Because of
these issues, bodies like the Venice Commission caution against overly
high turnout requirements, as they can *"discourage participation"* and
distort voter behavior.

## Academic and Theoretical Models for Legitimacy Thresholds

Scholars and constitutional designers have long debated how to
mathematically determine a "legitimacy threshold" in a democracy.
**Supermajority requirements** are one approach: requiring more than 50%
of votes (e.g. 2/3 or 3/4) for fundamental changes. The rationale is
that the **greater the impact of a decision, the broader the consensus
needed** to legitimize it. For instance, some U.K. commentators argued a
major step like Brexit or electoral reform deserved a two-thirds
majority rather than a bare 50%. Many U.S. states likewise mandate 60%
or 66% approval for constitutional amendments via ballot measures. This
is a simple fixed formula -- *f(x) = 0.6* (60%) or more -- regardless of
turnout.

Other theorists propose **formulas that account for turnout and
population size**. One straightforward idea is a *double requirement*:
"more than *Y*% of votes **and** at least *X*% of the entire
electorate." The cases above (Italy, Poland, Denmark, etc.) use this
logic with specific X and Y values. Some have suggested tying *X* to a
past benchmark; for example, political scientist Michael Saward noted
that a reasonable legitimacy quorum could be *"somewhere between 50% of
the electorate and the turnout in the previous general election"*. In
other words, if a country typically sees (say) 70% turnout in general
elections, one might demand that a constitutional referendum's turnout
be near that level to count. This approach scales the expectation based
on a known participation rate, rather than an arbitrary number.

Game-theoretic models have tried to **optimize quorum rules**. Research
by scholars like Sanne Zwart explored whether there exists an "optimal"
quorum that makes the referendum outcome mirror true popular will. Some
pivotal-voter models show that any turnout quorum can create multiple
equilibria (one where everyone votes, and one where the opposition
abstains to invalidate). In essence, there is a mathematical trade-off:
a higher threshold of participation increases the **mandate** of a yes
outcome, but also increases the risk of no outcome due to apathy or
boycott. **Social choice theorists** have pointed out that setting the
quorum "right" is daunting -- too low, and a small active minority might
change the constitution; too high, and almost no change can ever occur.
Lithuania's experience of nearly all post-1990 referendums failing under
a \>50% electorate rule is a cautionary tale. After 2002, Lithuania
lowered the requirement to one-third of all voters for most issues, and
introduced tiered thresholds: e.g. **¾ of the electorate for altering
core sovereignty clauses**, and \>½ for ordinary constitutional
amendments. This tiered model in law is effectively a formula
recognizing different legitimacy levels for different topics -- the most
fundamental issues demand the broadest support.

Beyond turnout and percentage formulas, **innovative mathematical
models** have been proposed. One intriguing example is the use of *fuzzy
logic* to set a context-dependent quorum. In a 2015 study, Turcoane and
Ionescu outline a *"Mamdani fuzzy inference system"* that takes into
account criteria like the **type of referendum, the degree of change
from the status quo, and the timing** ("age") of the issue, to compute
an appropriate quorum size. Instead of a fixed percent, the threshold
would *dynamically adjust* -- for instance, a drastic, unprecedented
constitutional overhaul might trigger a higher required turnout or
majority than a minor technical amendment. The fuzzy logic model's goal
is to capture nuance (gradations of importance and controversy) in
determining how much of the population's explicit approval is needed.
While still theoretical, it shows how computational models and
algorithms could aid constitutional design by **calculating legitimacy
thresholds** in a more granular way than blunt 50% or 2/3 rules.

Legal scholars also discuss **multi-dimensional legitimacy** in
democracies. Instead of just raw numbers, legitimacy might come from
**distributed approval** -- which leads to ideas like requiring approval
in different segments of the population. In federal or multi-ethnic
states, this appears as *"double majorities"* (or even triple
majorities): for example, **Switzerland** requires both a majority of
nationwide voters and a majority of cantons for constitutional
amendments, ensuring geographically spread support. This isn't tied to
the total population percentage per se, but to a concept of legitimacy
across regions. Similarly, *Australia* mandates a nationwide majority
**and** separate majorities in at least 4 of 6 states for constitutional
changes. These models reflect the idea that a constitution's legitimacy
comes not only from raw numbers of yes-votes, but from acceptance across
different communities.

## Dynamic and Innovative Threshold Ideas

Looking forward, constitutional designers have floated various **dynamic
threshold mechanisms** to balance inclusivity and practicality:

-   **Sliding-Scale Thresholds:** Rather than a fixed cut-off, the
    required majority could vary with voter turnout. For instance, if
    turnout in a constitutional referendum is very low, the rule might
    demand a supermajority (e.g. 60% or 66% *yes*) to pass, on the logic
    that broad consensus is needed when few people vote. Conversely, if
    turnout is extremely high (indicating robust engagement), a simple
    50%+1 might suffice. This sliding-scale approach incentivizes
    participation and ensures a minimum fraction of the population
    consents. While not yet codified in national constitutions, scholars
    have suggested such formulas informally. The principle is that
    **legitimacy = f(turnout, majority)** -- e.g. requiring a higher
    approval ratio when turnout drops below a certain benchmark. An
    example might be: "If turnout is below 50%, require 2/3 approval; if
    turnout 50--70%, require 60% approval; if turnout above 70%, require
    \>50%." This kind of rule dynamically adjusts to the participation
    rate.

-   **Concurrent Majority and Demographic Distribution Requirements:**
    In divided societies, a simple majority of votes could all come from
    one region or group, undermining perceived legitimacy. Innovative
    thresholds can require **concurrent majorities among different
    groups**. A real-world example is the Good Friday Agreement
    referendum (1998) which, while not formally requiring it,
    effectively tested majority support in both Northern Ireland and the
    Republic of Ireland separately. Analysts have suggested making this
    explicit: e.g., in Northern Ireland any constitutional change might
    need not just an overall majority but also a majority within both
    the unionist and nationalist communities. This idea of
    *"cross-community consent"* is analogous to power-sharing rules, but
    applied to direct democracy. It ensures no single bloc can force
    through a fundamental change against the will of a large minority.
    Other variants include requiring a majority in each province/state
    or even each major ethnic group for amendments. These demographic
    distribution thresholds seek to enhance legitimacy by proving the
    decision has **wide-ranging support**, not just numerical
    superiority from one faction.

-   **Turnout Bonuses or Penalties:** Another novel concept is to bake
    turnout directly into the result calculation. For example, some have
    proposed that if turnout fails to reach a certain threshold, the
    referendum could be declared void or a second confirmatory vote
    could be required. Conversely, exceptionally high turnout could be
    treated as a legitimacy "bonus" that might lower other requirements.
    One could imagine a formula where the effective "yes" percentage is
    weighted by turnout. (For instance, *Effective Yes % = Yes votes /
    total electorate*. Under such a rule, a proposal passes only if this
    effective yes-percent exceeds 50% -- which is exactly an absolute
    majority of citizens criterion.) In fact, many existing systems
    already do this implicitly: requiring a majority of the electorate
    *is* a form of turnout-weighted threshold. Some constitutional
    designers have suggested more continuous weighting schemes, though
    these are complex and not in practice yet.

-   **Iteration and Deliberation Mechanisms:** While not a threshold
    formula per se, an innovative idea is to tie thresholds to *multiple
    rounds* of voting or deliberation. For example, if a first
    referendum passes by a small margin or with low turnout, a
    constitution could require a second vote or a legislative
    supermajority to confirm it. This ensures that a change isn't made
    on a fluke of low engagement. The threshold for final adoption might
    be effectively higher unless reinforced by sustained public support.
    This idea recognizes **legitimacy as a process** -- the bar to amend
    goes up if citizen participation is low or opinions are sharply
    split.

Finally, it's worth noting that **any dynamic threshold must balance
inclusivity with governability**. If set too high, it can paralyze
constitutional evolution (as seen in Taiwan, where an absolute majority
of all voters is nearly impossible to achieve). If too low or too
complex, it may fail to confer the intended legitimacy. Legal experts
often advise clarity and simplicity in rules, which is a challenge when
designing formulas that account for turnout or demographics. The
experience of countries like Lithuania, which amended its referendum law
to a more attainable quorum after learning from failures, shows that
there is often a need to **fine-tune threshold models** in practice.

## Conclusion

In summary, there is a spectrum of models for determining constitutional
adoption thresholds relative to population:

-   **Fixed high thresholds** (absolute majority of the electorate, or
    supermajority of votes) used in many nations to ensure wide support,
    at the cost of making change difficult.
-   **Theoretical formulas and academic proposals** that attempt to
    mathematically calibrate legitimacy -- from turnout-contingent
    requirements to fuzzy logic systems that set quorum levels based on
    context.
-   **Innovative and dynamic ideas** that adjust thresholds for voter
    turnout or require distributed approval across society, aiming to
    bolster the credibility of constitutional decisions.

Real-world examples demonstrate both the **value and the drawbacks** of
strict population-based thresholds. They can provide strong legitimacy
(no one can question a change approved by, say, two-thirds of all
citizens), but they can also thwart the democratic will when used
inflexibly. Contemporary scholarship is thus exploring ways to
**modulate these requirements**, seeking an optimal balance where a
constitution can be neither too easily changed by a small active group
nor too rigid against the clear desire of the majority.

Ultimately, the choice of threshold model reflects a country's
historical context and political philosophy -- whether it prioritizes
**majority rule** or **consensus and stability**. As democratic theory
and practice evolve, we may see more nuanced threshold mechanisms that
dynamically ensure both broad participation and decisive outcomes,
keeping constitutional change legitimate in the eyes of the people.

**Sources:** Relevant examples and analyses have been drawn from
comparative reports and scholarly studies, including referendum cases in
the UK, Europe, and Asia, as well as insights from political scientists
and constitutional experts on supermajorities, turnout quorums, and
innovative quorum design.
