Closes: #

<!-- Id number of the GitHub issue this PR addresses. -->

-----

## Manual CI Build:

<!-- You shouldn't merge a PR without an associated CI build. Branch protection rules are in place to make sure of that. -->

Because this repo is a fork, on opening a PR, you'll have to trigger CI manually on it. To do that:
- Navigate to [Buildkite for uCrop](https://buildkite.com/automattic/ucrop).
- Click the [New Build](https://buildkite.com/automattic/ucrop#new) button.
    - Message: You could copy-paste your PR description.
    - Commit: Keep `HEAD`.
    - Branch: Choose the branch associated with your PR.
    - Options: Feel free to ignore the `Environment Variables` and/or `Clean checkout`.
- Click `Create Build` and wait for the CI checks to come into sight.

-----

## Description:

<!-- Take the time to write a good summary. Why is it needed? What does it do? When fixing bugs try to avoid just writing “See original issue” – clarify what the problem was and how you’ve fixed it. -->

-----

## Test Instructions:

<!-- This is your opportunity to break out individual scenarios that need testing (when necessary) and/or include a checklist for the reviewer to go through. Consider documenting the following from your own completed testing: devices used, alternate workflows, edge cases, affected areas, critical flows, areas not tested, and any remaining unknowns. -->
