# Quality Assurance

## QA Summary

- Release pipeline: v2
- Golden source: metadata/*.json
- Clip count: 12
- Metadata count: 12
- Privacy-reduced clips folder: clips_blurred/
- SHA256 generation: final step after rendering

## Diversity Checks

- Unique sources: 12
- Unique sessions: 12
- Unique collectors: 7
- Unique capture dates: 7
- Unique scene labels: 2

## Score Checks

- Average buyer value score: 78.75
- Average commercial use readiness score: 70.75
- Average metadata quality score: 70.75

## Scene Distribution

- intersection: 10
- market: 2

## Road Context Distribution

- market-zone: 9
- urban-road: 3

## Mobility Mix Distribution

- mixed-mobility: 10
- pedestrian-dominant: 2

## Validation Policy

Validators are read-only in Release Pipeline v2. They must not generate, patch, rewrite, or mutate release artifacts.
