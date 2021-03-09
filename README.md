# ansible-releng-scripts

Misc. scripts that help with releasing ansible{,-base,-core}.

Env. var assumptions:

* `GITHUB_TOKEN` - a GitHub personal access token
* `ANSIBLE_AZP_PAT` - an Azure Pipelines personal access token with scope to execute builds

Scripts:

#### `ansible-releng-run-pipeline <branch>`

Triggers a CI run for the given branch at the branch's HEAD.
