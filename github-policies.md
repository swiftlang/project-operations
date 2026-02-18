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
- Projects are either released as part of the Swift Toolchain or as Swift packages.
- Projects released through the Swift Toolchain follow the Swift Toolchain Release Process.
- For projects released as Swift packages:
  - Package versions **must** follow [Semantic Versioning](https://semver.org).
  - Packages **should** support the **latest patch releases** of the **last three minor** official Swift releases.
    - For example, if the currently latest Swift release is `6.2.1` then a package would be expected to support `6.2.1`, `6.1.3` and `6.0.3`.
    - As an exception, new packages are free to start with only supporting the latest official Swift release.
    - The expected Swift support should be tested on every pull request using the continuous integration provided by [swiftlang/github-workflows](https://github.com/swiftlang/github-workflows).
    - Changes to the minimum supported Swift version should be enforced by [setting the Swift tools version](https://docs.swift.org/swiftpm/documentation/packagemanagerdocs/settingswifttoolsversion).
  - Packages **should** support all [official supported Swift platforms and all their supported versions](https://www.swift.org/platform-support/).
    - As an exception, if a package is meant to support a limited set of platforms, it should document what platforms it supports in the package's README.
    - For packages that support Apple platforms, they should support the **latest minor and patch** Xcode release **aligned** with each **supported Swift minor version**.
      - For example, if the current latest Xcode release is `26.3.0` (containing Swift `6.3.0`) then a package would be expected to support:
        - `26.3`, aligned with Swift `6.3`
        - `26.2`, aligned with Swift `6.2`
        - `16.4`, aligned with Swift `6.1`
      - As an exception, newly released package projects are free to start with only supporting the latest official Xcode release.
      - As with Swift version support, support within Xcode should be tested on every pull request using the continuous integration workflows provided by [swiftlang/github-workflows](https://github.com/swiftlang/github-workflows).
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

