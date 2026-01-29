# Contributor Ladder

This contributor ladder defines the roles you might gain while contributing to Swift on GitHub. Each role has privileges associated, which requires building trust with the community of contributors. We recognize there are many different types of contributors to Swift and we appreciate every single one! Everyone who has participated in the open source Swift project is a *Contributor*: This can be by writing code, answering questions on the forums, reporting or triaging bugs, or participating in the Swift evolution process.

As you climb the contributor ladder by contributing to Swift on GitHub, you gain new privileges but also gain trust and responsibilities that you are expected to fulfill. If a contributor violates this trust and these responsibilities, the Core Team may give them a notice and upon repeated infringements revoke their level. We believe in a healthy community and hope this action will never be necessary.

## Member

A *Member* has constructively contributed to Swift multiple times. This role is held across the entire organization, becoming a *Member* allows you to trigger CI on all repositories in the swiftlang organization on GitHub.

- Requirements
  - Make multiple constructive contributions to the Swift projects. This can be in the form of PRs, engagement on the Swift Forums, filing valuable issue, triaging them, or similar.
- Privileges
  - Ability to trigger CI testing
  - Show your membership in the swiftlang organization on your GitHub profile
- Nomination
  - If you would like to become a *Member*, please send a message to [the code-owners group](https://forums.swift.org/g/code-owners) on the Swift forums that includes your contribution and the GitHub user name that you want to use
- Growth
  - Show that you use the privileges constructively and continue contributing to gain commit access.

## Code Merger

A *Code Merger* has made several high-quality contributions, has enough knowledge to review PRs in their area, and is trusted to merge changes after getting approvals. The *Code Merger* level is granted on a per-repository basis.

- Requirements
  - Author 5 small to medium-sized, non-trivial, high-quality PRs (or equivalent) that needed little guidance.
- Responsibilities
  - Provide PR reviews, answer questions, and triage issues in your area.
- Privileges
  - Merge PRs in the repository that you’re a *Code Merger* of, including PRs authored by other contributors. You are expected to only merge PRs after you have received an approving review from a *Code Owner*. *Code Owners* might approve with comments, with the expectation that you, as a *Code Merger*, will re-request a review if you make major adjustments after the approving review and ensure that the comments are addressed in a timely manner.
  - Ability to label/triage issues and assign them to contributors.
- Nomination
  - Like for a *Member*, please send a message to [the code-owners group](https://forums.swift.org/g/code-owners) on the Swift forums that includes your contributions, the GitHub user name that you want to use and the repositories you want to become a *Code Merger* for. At the digression of the code owner list, you may also be granted the *Code Merger* role for repositories that you have not contributed to but that are conceptually linked to your contributions, like `swift-syntax` and `swift-driver` after having contributed to the compiler.
- Growth
  - As an *Code Merger*, you are trusted not just with your own work but with helping others. In reviews, you can show that you are able to take care of a code area to become a *Code Owner*.

## Code Owner

A *Code Owner* has the expertise to decide whether a PR affecting their area should be merged.

* Requirements
  * As a *Code Owner*, you must have detailed knowledge of your area. You should be able to review PRs, be confident to judge whether they have the necessary quality to be merged and be able to assess the risk of a change, and to decide whether it should be cherry-picked to a release branch.
* Responsibilities
  * Ensure that PRs get reviewed in a timely manner.
  * Be a point of contact for any questions and issues regarding your area.
  * Fix issues in your area or have the capacity to delegate the issues to somebody else.
  * Upkeep a high-quality bar for contributions.
  * Help *Code Mergers* grow by providing actionable feedback on their PR reviews.
  * Encourage active *Code Mergers* who fulfill the *Code Owner* requirements to nominate themselves as a *Code Owner*.
* Nomination
  * Send a private message to the existing *Code Owners* of the area you want to own on the [Swift Forums](https://forums.swift.org), communicating your intent.
  * After you have received positive feedback, formalize your nomination by creating a pull request that modifies the `.github/CODEOWNERS` file to add your username to the area you want to own and request a review from all existing *Code Owners* of that area. The request must be approved by at least one and must not be declined by any other of these *Code Owners*. All *Code Owners* of the area should have one week to formally reply to the nomination.
  * The position of a *Code Owner* is voluntary and can be resigned at any time.
