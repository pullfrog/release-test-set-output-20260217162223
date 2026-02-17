# release test repo

this repository validates a CI workflow that:

- detects `package.json` version changes on `main`
- asks `pullfrog/pullfrog` to generate a changelog
- requires the agent to call `gh_pullfrog/set_output`
- creates a GitHub release with the generated changelog body
