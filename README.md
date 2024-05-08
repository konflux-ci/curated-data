# curated-data

This is a fork of [clearlydefined/curated-data](https://github.com/clearlydefined/curated-data) which we set up as a place where [konflux-ci people interested in licenses](https://github.com/orgs/konflux-ci/teams/license-people) can manage license declarations that we aim to contribute back to clearlydefined.

You are currently looking at the [configuration](https://github.com/konflux-ci/curated-data/tree/configuration) branch, where this README exists and some [github actions](https://github.com/konflux-ci/curated-data/tree/configuration/.github/workflows/) for syncing the [upstream](https://github.com/konflux-ci/curated-data/tree/upstream) branch of our fork with the upstream repo [clearlydefined/curated-data](https://github.com/clearlydefined/curated-data).

Notably, we are syncing [clearlydefined/curated-data](https://github.com/clearlydefined/curated-data) to the [upstream](https://github.com/konflux-ci/curated-data/tree/upstream) branch on this fork.  Ultimately, the [downstream](https://github.com/konflux-ci/curated-data/tree/downstream) branch of this repo is where we are trying to land content, for use in konflux-ci.

## Workflow

Make a commit declaring a new license or source detail, like [d43bb6](https://github.com/konflux-ci/curated-data/commit/d43bb60d5114f3c8d57536344bbc9c7b3acb0c4f). Then, open **two** pull requests. One to the origin repo at clearlydefined/curated-data, and a second one to the [downstream](https://github.com/konflux-ci/curated-data/tree/downstream) branch on [this repo].

For example, commit [d43bb6](https://github.com/konflux-ci/curated-data/commit/d43bb60d5114f3c8d57536344bbc9c7b3acb0c4f) was submitted upstream as [clearlydefined/curated-data!27350](https://github.com/clearlydefined/curated-data/pull/27350) and [downstream] as [konflux-ci/curated-data!2](https://github.com/konflux-ci/curated-data/pull/2).
