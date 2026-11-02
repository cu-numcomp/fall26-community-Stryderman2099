# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: NOOP

NOOP is an offline, open-source companion app for WHOOP fitness straps (4.0 and 5.0),
with experimental Oura Ring support. It connects to the strap over Bluetooth, stores all
data locally in SQLite, and computes heart rate variability (HRV), recovery, strain, and
sleep stages on the device instead of in WHOOP's cloud. The numerical core is the
`StrandAnalytics` Swift package, which handles noisy heart-rate/RR-interval signals,
personal baselines, and sleep scoring, and includes a benchmark (`Tools/SleepBench`,
`Tools/SleepPSG`) against polysomnography data. Its main audience is WHOOP owners who want
their data without a subscription or cloud account, plus privacy-minded users and hobbyist
developers interested in wearable signal processing. I also have been personally running and
using the software throughout the last several months because I have a WHOOP and used to pay 
for a subscription.

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL | https://github.com/ryanbr/noop |
| Main/documentation website | https://github.com/ryanbr/noop/wiki and `docs/` in the repo |
| Year project was started | 2026 (first commit June 2026) |
| Number of contributors in the past year | ~77  |
| Number of contributors in the lifetime of the project | ~77 commit authors (55 on GitHub's contributor list) |
| Number of distinct affiliations | 1 (mostly independent hobbyists, no institutional backing) |
| Where do development discussions take place? | GitHub issues and PRs, Discord, r/NoopBand |
| Typical number of emails/comments per week? | ~150 issue/PR comments; ~55 new issues/PRs per week |
| Typical number of commits per week? | ~90 |
| Typical commit size | ~4 files, ~80 lines changed (median) |
| How does the project accept contributions? | GitHub pull requests |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes (GitHub Actions) |
| Does the project have an AI contribution policy? | No formal policy, but [AGENTS.md](https://github.com/ryanbr/noop/blob/main/AGENTS.md) and [CLAUDE.md](https://github.com/ryanbr/noop/blob/main/CLAUDE.md) give instructions for AI coding agents |
| Are any legal/licensing steps required to contribute? | No CLA; opening a PR means agreeing to the project license (see below) |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [Yes] I have installed the software
- [Yes] I have run at least one example
- [Yes] I have run the test suite
- [Yes] The test suite passes

### Notes/concerns/risks

Please comment on any anomalies or known risks to following this
project, if you were unable to answer any questions above, or
otherwise have concerns about the appropriateness of the software.  If
the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
