# on-pr-use-compare-sha

Example repository showcasing different workflows:

* trigger on a pull request by default (checking out the PR merge branch, see [docs](https://help.github.com/en/actions/reference/events-that-trigger-workflows#pull-request-event-pull_request))
* trigger on a pull request checking out the head ref checking out for using the compare branch's SHA rather than the merge commit.
* trigger on a push where `github.ref` contains pull
