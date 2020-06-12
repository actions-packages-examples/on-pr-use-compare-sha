# on-pr-use-compare-sha

This is an example repository showcasing different workflows:

* trigger on a pull request by default (checking out the PR merge branch, see [docs](https://help.github.com/en/actions/reference/events-that-trigger-workflows#pull-request-event-pull_request))
* trigger on a push or pull request event, checking out the head ref checking out for using the compare branch's SHA rather than the merge commit.
