# renovate-config

Shared [Renovate](https://docs.renovatebot.com/) preset for the GitHub-canonical
`meltforce` repositories. A repository uses it with:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>meltforce/renovate-config"]
}
```

Updates arrive as pull requests and merge through GitHub auto-merge once the
repository's required checks pass. Majors, Go minors and Python minors wait for
the checkbox in the repository's dependency dashboard issue.

Renovate runs as the Mend Renovate GitHub App, installed for selected
repositories; a repository is added to the installation when it adopts the
preset.
