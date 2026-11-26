# Cynthia’s Gauntlet

## Strategy
Legal 40-point roster selected using seeded candidate search and battle simulation. The policy uses public species statistics, type effectiveness, estimated damage, speed, observed opponent moves and legal actions to choose attacks or replacements. It does not access hidden variants, seeds or external files.

## Validation and results
Both rosters passed the supplied team validator. The custom policy passed the supplied security/sample-turn check. On seeds 1000–1099, the custom roster won 7/100, with zero recorded fallbacks in in-process testing. The supplied runner automatically changes public to policy variant when a custom policy is supplied. The team-only alternative won 5/100 against public with the default policy. These are different opponents and are not directly comparable. No hidden variants were tested. These are modest results, not a claim of competitive superiority.

## Credits
Battle engine, public Pokémon datasets and simulator: Custodia × WiTS organizers. Search and policy implementation: ChatGPT AI assistance. Participant: review, testing and submission (complete with actual team member names and contributions before submitting).

## Usage
Upload team.json and policy.py only if custom policies are permitted. Otherwise use the separately provided team-only alternative renamed team.json. Confirm submission rules with organizers.
