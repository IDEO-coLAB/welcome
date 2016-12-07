# Welcome!

Welcome to CoLab engineering! This repo is your entry point into the CoLab ecosystem, and provides links to other useful repos. This repo was specifically created to answer to these questions:

- Does the CoLab have any standard engineering tools, processes, and conventions?
- Where can I start learning and using the above?

<br/>
## Table of Contents

- [Finding Relevant Repos](#find)
- [Managing Code](#mgmt)
- [Starting New Projects](#new)
- [Dev Ops](#devops)
- [Improving Ourselves](#improvement)
- [Discovering New Tools](#tools)
- [Feedback](#feedback)

<br/>
## <a name="find"></a>Finding Relevant Repos

For all core documentation and forkable base repos, CoLab uses a strict naming convention to create namespaces. This allows anyone to search by a certain namespace to filter out unnecessary results. See the examples below.

### `docs-*`

All CoLab documentation repos are prefixed with `docs-*`. You can pull up all CoLab docs by simply searching for `docs-` using the CoLab organization's search bar.

### `forkable-*`

All CoLab forkable base repos are prefixed with `forkable-*`. You can pull up all CoLab forkable base repos by simply searching for `forkable-` using the CoLab the organization's search bar.

### `forkable-[language]-*`

The `forkable-` namespace is succeeded by another namespace to be used for repo's primary language (e.g.: `forkable-js-*`, `forkable-py-*`, etc...). 

For a living example, the CoLab's React template repo is primarily a javascript project. As such, it is named `forkable-js-react-static`, following the `forkable-[language]-*` convention. Now you can find all forkable base repos in in your language of choice!

<br/>
## <a name="mgmt"></a>Managing Code

We use Git, GitHub, and a specific Git branching strategy paired with pull requests to keep production code in a clean state. Learn more about how we use these tools in our Git documentation.

- **Repo Link**: [`docs-git`](https://github.com/IDEO-coLAB/docs-git)

<br/>
## <a name="new"></a>Starting New Projects

We have a number of forkable base repos that you should use if you're creating a longer-lived project that will be built with, or (at some point) handed off and maintained by, CoLab engineering. 

Each repo contains its own install and usage instructions.

*Note how these repos follow the naming conventions mentioned above.*

### New Javascript Projects

#### `forkable-js-base`
- **Repo Link**: [forkable-js-base](https://github.com/IDEO-coLAB/forkable-js-base)
- **Repo Description**: The CoLab's base repo for all new JavaScript projects.
- **When to Use**: Any time you're creating a new JS project for the CoLab, regardless of whether it is client or server side.
  
#### `forkable-js-react-static`
- **Repo Link**: [forkable-js-react-static](https://github.com/IDEO-coLAB/forkable-js-react-static)
- **Repo Description**: The CoLab's base repo for creating new static React sites (This means that the project does not include any server component to it and is expected to be bundled and served from somewhere).
- **When to Use**: Any time you're creating a new static React project for the CoLab.

<br/>
## <a name="devops"></a>Devops
Devops has its own docs repo: [`docs-devops`](https://github.com/IDEO-coLAB/docs-devops)

<br/>
## Improving Ourselves

We use project postmortems to collect and share specific and generalized learnings across the team. Whenever a project phase or build concludes, we take time to synthesize and share any important specific and generalizable learnings with the rest of the team.

- **Repo Link**: [`docs-postmortems`](https://github.com/IDEO-coLAB/docs-postmortems)

<br/>
## <a name="tools"></a>Discovering New Tools

*Coming soon: This will contain links to tools we've found to be extremely helpful in one way or another.*

<br/>
## Feedback

Is something missing? Feel free to let [Reid](https://github.com/ReidWilliams/) or [Gavin](https://github.com/gavinmcdermott) know and they'll be in touch.
