# Checklist Version Comparison Desk

A standalone browser worksheet for deciding whether two checklist scores are comparable. It asks about the item set, item wording, scoring direction, weighting, and treatment of unanswered items. It produces a printable comparison note rather than assuming that matching numbers mean matching experiences.

## Run

Open `index.html` in a modern browser, or serve this directory with any static web server. There is no build step, dependency, account, storage, or network request. Worksheet entries remain in the current page and are cleared on reload. Do not type sensitive individual answers into a comparison worksheet.

## Checks

The implementation uses explicit unknown states, reports incompatible scoring assumptions, escapes user-entered labels, and includes print styles. The calculations and interaction boundaries were checked locally before publication.

## Example to inspect

The page links to the Rice Purity HQ score explanation as an adult-oriented implementation example. The worksheet itself contains no adult checklist items and can be used to compare any compatible checklist. A score is a count under a set of rules, not a measure of personal worth.
