The source for the lodash package in the update PRs is user configured one instead of the official source url for the lodash package.
ie. we replaced the official source url using package rules.

As expected it broke the change log fetching as well since the source url now being used fetches changes for the renovate package instead of lodash.
