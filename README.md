# Tessel RFCs

For feature additions to the Tessel platform that require some aspect of design or discussion, an RFC (Request For Comment) is necessary. This helps the community collaborate to build robust, thoughtful, and effective additions to the platform. Our hope is to keep the process as light as possible while preserving the reliability and forward-looking nature of Tessel.

Some things don't require RFCs! These are things like documentation fixes or additions or simple bug fixes. If you're not sure, open an issue and ask or pose the question on [the Tessel Slack channel](tessel-slack.herokuapp.com).

## Active RFCs
|🚀| Proposal                                                                                             | Champion      | Stage
|---|------------------------------------------------------------------------------------                 |-------------- | ------|------
|

## How to create an RFC
Our RFC process is heavily inspired by the ECMA/TC39 RFC process. The process is as follows:

### 1. Create a repo for the feature
One or more champions propose a new feature by creating a repo dedicated to that feature
Example: https://github.com/rwaldron/exponentiation-operator

The feature is free to describe all aspects of the platform that it interacts with and is described as thoroughly as possible in the readme.md of the repo. Using a repo is convenient for adding and removing fellow feature contributors.

### 2. Post about it on the Forums
We strongly encourage new RFCs to be posted on [the Forums](forums.tessel.io) for the sake of including as many people as possible.

### 3. Create issues and pull requests on that repo
Feedback, discussion and development of the proposal is done by filing issues and pull requests. This ensures that all of the history of a particular feature is preserved. Issues allow creating trackable bullet lists of action items, these are useful for defining milestones.
Example: https://github.com/rwaldron/exponentiation-operator/issues

Additions and modifications to the feature's proposal are contributed as pull requests (again, great historic record here).
Example: https://github.com/arv/ecmascript-object-observe/pull/12/files

The repo may include reference implementations, tests, API mockups, use cases, diagrams, illustrations, presentations, pdfs, slide decks, etc. The idea is that the "art" is preserved in a single location.
Example: https://github.com/tc39/Array.prototype.includes/tree/master/reference-implementation

### 4. Update this central repo with progress

Each proposal is presented in 4 stages which are defined [here](https://docs.google.com/document/d/1DWcHGNI6na1ybcdrUR_wLcz0n5rNJzEbQMGd7sXVjRc/edit?usp=sharing)

The feature proposal is added to this central repo (under "Active RFCs") which keeps a public record of the feature's current stage. Do this via a PR on this repo.
Example: https://github.com/tc39/ecma262

Each stage of progress is presented to Tessel Team Members by tagging one on your repo. Current Team Members can be found [here](https://github.com/tessel/project/blob/master/COLLABORATORS.md) The feature either advances to the next stage or continues being developed at the current stage, incorporating new feedback.

### 5. Merging Code
Once the feature is complete and all the relevant code has been merged into the relevant repos, this central repo is updated by a Team Member to indicate that the feature is merged.

