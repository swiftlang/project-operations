# Swiftlang GitHub Policies and Administration

## Swiftlang

Swift project repositories in the Swiftlang GitHub organization are highly relevant to Swift's general-purpose programming language mission.
This GitHub organization is a supporting piece to a broader ecosystem.
All repositories in this organization are sponsored by a Steering Group or the Core Team.
The Swiftlang organization is meant to be the underlying pillar of the ecosystem where the ecosystem should grow around it.

In this GitHub organization, you'll find:

- Official tools, programs, and components that are part of the Swift toolchain or play a role in developing the Swift toolchain.

- Projects that meet the Swift projects [organizational principles](#principles).

- Packages that serve as the canonical solution, provide a critical reason for their existence within the language as advised by Steering Groups/Core Team, or otherwise highlight their necessity for maintaining the health of the ecosystem.

  - Packages may be accepted if it's beneficial for the community to agree on one common solution, such as:

   - Libraries that define currency types that are essential for the ecosystem to communicate between APIs.
   - Libraries that provide barebones APIs for streamlining getting started with Swift.

- Official documentation repositories:

  - The swift.org website.
  - Project operations and governance.
  - User documentation, examples, and samples relating to one of the repositories already included.

- A fork or mirror of a major direct dependency that is coming from another high-trust GitHub repository and/or organization as determined by the Core Team.

## Principles

- The code provided in the [Swiftlang GitHub Organization](https://github.com/swiftlang) is largely licensed through Apache 2.0. We will not approve other licenses without discussion first through the Core team.
- All projects in this org adhere to:
  - [the Swift Code of Conduct](https://www.swift.org/code-of-conduct/)
  - [the Swift Security process](https://www.swift.org/support/security.html) unless otherwise noted in the projects approved SECURITY.md at the root.
- All projects agree to open and active development.
  - Follows the Swift Toolchain Release Process; if not, there is a documented process document.
      - For projects that are packages:
        - There should be a statement in the README on how those packages handle versioning.
        - The package supports the latest official Swift release and one prior.
  - Active CODEOWNERS are defined.
  - Accept the GitHub membership and code committers policy.
  - Accept pull requests and issues (unless it's a fork, clone, or mirror with a specific purpose detailed on the README).
  - Have a documented process in place for changes to be proposed, reviewed, and approved, as part of the “evolution” of the project. For some projects, that will be “Swift Evolution” for changes that have deep implications on the language and ecosystem, and for others, it will be through less formal processes as determined by Steering Groups/Core Team.
  - Adopt [basic contributing guidelines](swift.org/contributing) with a contribution statement in the README or a custom CONTRIBUTING.md file is present.
  - Value incremental development.
  - Adopt Swift API Design Guidelines.

## Use of a 'swift-*'' prefix - guidance for the repository name.
- If it's a rewrite, keep `swift*`.
- If it has a proper brand name, remove `swift*`.

## Creating a new repository.

Steering Groups should work with their Core Team representative to start a new repository request.

## Transferring a repository into github.com/swiftlang.

The Core Team is actively working on a process.
Please check back for more information.
The process will also start at the Steering Group level for sponsorship.

