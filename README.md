# forglemmigej-report

Data for the public [model report](https://b-pasztor.github.io/forglemmigej/) of
[forglemmigej](https://github.com/b-pasztor/forglemmigej), a self-hosted Danish
spaced-repetition tutor with an MLOps loop around its memory model.

The nightly training job on the homelab commits `report.json` here; the page itself
lives in the main repository (`report/`) and is published by its `pages` workflow.
The history of this repository is the history of the report.

It holds only weekly aggregates (log loss, calibration, recall rates, the gate's
evidence): no cards, words, answers or single reviews. The data lives in its own
repository so that the token the homelab uses can write here and nowhere else.
