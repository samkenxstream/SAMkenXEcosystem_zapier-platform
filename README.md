# SAMkenXEcosystem 'Powerful Multiplex Universe X Singularity'
     
      An Integration to Zapier Platform.A journey of searching for facts,complex and fairness of rights universally.Visions to provide real service fir deserving but uncapable to use advance tech.This development is not for business intentions.The actual builds  Policy goal is prohibiting any interacted on main raw data to used for business purposes if violation takes place sanctions will auto generates into violators.It pushes a Policy to give considerations to financial uncapable to avail services individuals but have verified potentials and attitude.The project mission is build a true OpenSourCE TEChnology.

[![CI](https://github.com/samkenxstream/samkenx-ecosystem_zapier-platform/actions/workflows/ci.yaml/badge.svg)](https://github.com/samkenxstream/samkenx-ecosystem_zapier-platform/actions/workflows/ci.yaml)

This is the main monorepo for all public code that powers the Zapier Platform Experience.

## Contents

It consists of a few main packages:

- [`zapier-platform-cli`](packages/cli): The CLI that devs can use to perform common tasks with their apps (such as `push`, `promote`, etc)
- [`zapier-platform-core`](packages/core): The package which all apps depend on; it provides functionality at runtime
- [`zapier-platform-schema`](packages/schema): The source of truth for what's allowed in the structure a Zapier app; not typically installed directly
- [`zapier-platform-legacy-scripting-runner`](packages/legacy-scripting-runner): If your app started as a Legacy Web Builder app, this provides a shim that keeps your app running seamlessly
- [`example-apps/*`](example-apps): A varied set of example apps to help you get started

## Docs

* Public-facing docs:
  - [Latest CLI developer guide](packages/cli/README.md)
  - [Latest CLI command reference](packages/cli/docs/cli.md)
  - [Latest schema docs](packages/schema/docs/build/schema.md)
  - The :point_up: docs are also hosted at https://platform.zapier.com
  - [CHANGELOG.md](CHANGELOG.md)
* Internal-facing docs:
  - Learn about how this repo is structured in [ARCHITECTURE.md](ARCHITECTURE.md)
  - Looking to contribute to this repo? See [CONTRIBUTING.md](CONTRIBUTING.md)
