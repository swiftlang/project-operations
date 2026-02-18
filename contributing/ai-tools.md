# Use of AI Tools in Contributions

The Swift project welcomes and encourages the use of AI-assisted tools, such as coding assistants and large language models, to aid contributing. When used thoughtfully, these tools can improve productivity, help contributors learn an unfamiliar codebase, and more.

The [contributing guidelines](/contributing) contain criteria for ensuring that a contribution meets the high-quality standards of the Swift project, regardless of how a contribution was developed. The following guidelines are intended to set expectations around authorship, understanding, and transparency when using AI tools to assist your development workflow.

## Understanding and Responsibility

You are responsible for all of the contributions you submit, including issues, pull requests, and discussions. Using an AI tool does not reduce the expectation that you understand the code or design you are submitting. You are expected to do a self-review and revise your contribution as needed before requesting a PR review from another contributor, and you should be prepared to explain, clean up, and refine the contribution as requested by reviewers until the contribution meets the quality standards of the project.

Examples:

* If a reviewer asks for clarification about AI-generated code in a contribution, you should explain the effect of the code and/or why the chosen approach is the most appropriate solution.
* If you fix a bug and use AI-tools to generate test cases, you should review every test case to ensure that the behavior being tested is what you intend. You should adjust the tests in cases where the expectation is incorrect, and remove any redundant tests.

> **Rationale**: All contributions are expected to adhere to the quality standards of the Swift project, regardless of how the contribution was developed.

## Authorship and Voice

You are expected to use your own voice, ideas, and judgment when producing written materials associated with a contribution, including (but not limited to) forum and GitHub comments, proposal documents, documentation, commit messages, and PR descriptions.

Using AI tools to help draft text is acceptable, such as for editorial refinements or translation help. You are expected to review, adapt, and personalize the text to ensure it accurately represents your understanding and decisions.

Examples:

* You should write your own pull request descriptions and commit messages summarizing and justifying an AI-assisted code change.
* When engaging in discussion with other contributors, such as in code review discussions, GitHub issue threads, or discussion on the forums, you should write your own replies.
* When writing proposal documents, you should write down the ideas you'd like to propose, and use AI tools for editorial changes. You should review all changes made to your text before proposing it, adjust any incorrect or superfluous text, and ensure that the tone of voice is still your own.

> **Rationale**: We’re a community of humans, and we value hearing your ideas, questions, insights, and reasoning in your own words. Writing your own prose is also an important exercise in understanding, summarizing, and taking ownership of the change you're proposing, whether it's a code change or a new evolution proposal.

## AI Attribution

You are encouraged to include a brief AI attribution with your contribution when AI tools assisted your workflow. An attribution should identify:

* The AI tool or coding assistant used
* A short description of how it was used

This attribution can be included in the PR description, marked with `Assisted By:`. AI attribution is intended to be lightweight and informational. It is not used to judge contributions differently or impose additional review requirements.

Examples:

* If you used an AI tool to help add visual structure to a document you wrote, include an AI attribution such as `Assisted By: ChatGPT added section headings and re-formatted text I wrote to make the document easier to follow`.
* If you used an AI tool to generate test cases for a code contribution, include an AI attribution such as `Assisted By: Claude Code generated test cases based on my explanation of the bug I fixed and the intended behavior.`

> **Rationale**: Sharing useful prompting techniques that you discover throughout your development process will help the community adapt their workflows as we learn how to make the most effective use of AI tools together.
