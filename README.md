# Sadaf-pm-skills
Claude skills from my core product management workflow, built and tested
on real product work. Each skill gives Claude a repeatable method, a fixed
output format and quality checks, so results are consistent and cited.

## Plugins
# Product Research

Skills for the research that feeds product decisions. Every output is
cited, dated and honest about what it couldn't find.

## Skills

### competitor-research

Turns a question about competitors into a brief the team can act on:
what competitors offer, how their capabilities work, what customers
say about their features, and what it all means for us.

**Modes**
- **Quick scan**: who the competitors are, and the headline implications
- **Deep dive**: a full brief on one competitor
- **Comparison**: 2-6 competitors side by side
- **Refresh**: only what has changed since a previous brief

**What you get**
1. **Landscape table**: each competitor's type, segment, positioning,
   starting price, last funding and an "as of" date
2. **Comparison tables**: one per theme (such as pricing or onboarding),
   with every cell dated and "Not found" instead of blanks
3. **Capabilities and how they work**: what each capability does and how
   it works in plain language, drawn from engineering blogs, technical
   talks, product docs and API docs. Each entry is labelled as stated by
   the company or inferred.
4. **Customer feedback on features**: praise and complaints tied to
   specific features, with approximate counts and date ranges, from
   Trustpilot, app stores, G2, Capterra, Reddit and other sources
5. **Implications for us**: where we win, where we lose, white space
   and threats, each linked to a finding
6. **What couldn't be found, and why it matters**: each gap, where the
   skill looked, and how it affects the decision
7. **Sources**: a numbered list with links and access dates

**Example prompts**
> Use competitor-research to compare Tide, Revolut Business and Monzo
> Business on pricing and onboarding for UK sole traders.

> Use competitor-research for a deep dive on Allica Bank, including how
> its lending decisions work, to inform whether we enter SME lending.

> Use competitor-research to refresh last quarter's brief on UK
> expense-management tools.
