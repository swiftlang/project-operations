# Use of AI Tools in Contributions

The Swift project welcomes and encourages the use of AI-assisted tools, such as coding assistants and large language models, to aid contributing. When used thoughtfully, these tools can improve productivity, help contributors learn an unfamiliar codebase, and more.

The [contributing guidelines](/contributing) contain criteria for ensuring that a contribution meets the high-quality standards of the Swift project, regardless of how a contribution was developed. They also contain development best practices for ensuring that a contribution is easy for maintainers to review. Ease of review is especially critical with AI-assisted contributions, because maintainers have a higher volume of changes to review. Please carefully read the contribution guidelines and ensure that you follow them for your AI-assisted changes, including keeping PRs small and focused without unrelated changes, separating refactoring from functional changes, limiting the number of PRs you have open at once, etc. Maintainers have a right to request changes on PRs that do not follow these guidelines.

The following guidelines are intended to set expectations around authorship, understanding, and transparency when using AI tools to assist your development workflow.

## Understanding and Responsibility

You are responsible for all of the contributions you submit, including issues, pull requests, and discussions. Using an AI tool does not reduce the expectation that you understand the code or design you are submitting. You are expected to do a self-review and revise your contribution as needed before requesting a PR review from another contributor, and you should be prepared to explain, clean up, and refine the contribution as requested by reviewers until the contribution meets the quality standards of the project.

Examples:

* If a reviewer asks for clarification about AI-generated code in a contribution, you should explain the effect of the code and/or why the chosen approach is the most appropriate solution.
* If you fix a bug and use AI-tools to generate test cases, you should review every test case to ensure that the behavior being tested is what you intend. You should adjust the tests in cases where the expectation is incorrect, and remove any redundant tests.

> **Rationale**: All contributions are expected to adhere to the quality standards of the Swift project, regardless of how the contribution was developed.

## Authorship and Voice

You are expected to use your own ideas, judgment, and voice when producing written materials associated with a contribution, including (but not limited to) forum and GitHub comments, proposal documents, documentation, commit messages, and PR descriptions.

Using AI tools to help draft text is acceptable, such as for editorial refinements or translation help, and you are expected to review, adapt, and personalize the text. Before posting AI-assisted text, ask yourself: does this accurately reflect my own understanding and reasoning? If a reviewer asked you to elaborate on a point in your PR description, could you do so in your own words? If not, the text needs more of your own thinking before it's ready.

Examples:

* What counts as acceptable AI assistance for written materials:
  * Fixing grammar, spelling, or punctuation
  * Suggesting clearer phrasing for an idea you've already articulated
  * Translating text you wrote in another language
* What is not in the spirit of this policy:
  * Generating the reasoning or justification for a design decision
  * Producing your position in a technical debate
  * Writing a proposal's motivation or alternatives sections from scratch
  * Responding to reviewer feedback with AI-generated replies

> **Rationale**: We're a community of humans, and we value hearing your ideas, questions, insights, and reasoning in your own words. When you write your own prose, you are forced to clarify your own thinking, surface gaps in your understanding, and take genuine ownership of what you're proposing. A PR description or forum reply that was generated rather than written tells reviewers and collaborators less about your reasoning, and makes it harder for the community to engage meaningfully with your contribution.

## Learning-oriented contributions

Some contributions are made primarily as a learning experience, such as working on GitHub issues labeled with `Good First Issue`, or participating in mentorship programs like Google Summer of Code and the Swift Mentorship Program. These contributions are especially valuable not just for their outcomes, but for the growth and understanding they foster.

Using AI tools to support your learning can be helpful, such as for exploring unfamiliar areas of a new codebase. However, you are expected to use these tools in a way that supports — rather than replaces — your own learning and problem-solving. Over-reliance on AI risks undermining the very growth opportunities these programs are designed to provide.

Examples:
* You should take the time to understand the code you are modifying, even if AI tools can quickly suggest a working solution. This includes exploring how your changes fit into the broader system, even if this slows down your pace of writing more code.
* You should treat AI-generated code as a starting point, and rewrite or adapt it as needed to ensure you understand how and why it works.
* You should be able to explain your implementation decisions and reasoning to reviewers without relying on AI-generated explanations.
* You should expect to iterate on your changes based on feedback, and use that feedback as part of the learning process.
* You should not _only_ ask questions to a coding assistant or LLM chat -- please ask questions to your mentor and other contributors in the Swift community!

> **Rationale**: Mentorship programs are designed to help you 1. build a foundational understanding of a new technical area, and 2. get to know other contributors in the Swift community. While AI tools can accelerate progress, over-reliance on them can bypass important learning opportunities. Taking the time to engage deeply with the code, write and refine your own implementation, and engage with other contributors will help you get the most value out of these experiences for both your technical understanding and getting to know the community.
