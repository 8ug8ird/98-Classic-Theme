# Contributing to Classic 98

Contributions are accepted through issues and pull requests.

By submitting a pull request, you are responsible for the correctness, completeness, and testing of your contribution.

## Bug Reports

Open a [Bug Report](https://github.com/8ug8ird/98-Classic-Theme/issues/new?template=bug_report.yml).

Include, when applicable:

- Classic 98 version
- BetterDiscord version
- Discord version
- Affected interface element or area
- Description of the issue and expected appearance
- Screenshots showing the issue

Incomplete reports may be difficult to investigate.

## Feature Requests

Open a [Feature Request](https://github.com/8ug8ird/98-Classic-Theme/issues/new?template=feature_request.yml).

Describe the proposed change, the problem it addresses, and any relevant use cases.

For substantial changes, discuss the proposed approach before starting implementation.

## Code Contributions

Fork the repository, make the required changes, and open a pull request.

Pull requests should:

- Address a single change or a closely related set of changes.
- Clearly explain what changed and why it is needed.
- Preserve the existing visual style unless a change is explicitly intended.
- Avoid unrelated modifications and unnecessary restructuring.
- Include all necessary CSS and documentation changes.
- Be ready for review rather than relying on the maintainer to complete the implementation or identify basic issues through repeated review cycles.

For larger changes, open an issue before submitting a pull request to discuss the proposed approach.

## Testing Requirements

Contributors are responsible for testing their changes before requesting review.

For pull requests that modify the theme:

- Test the final version in a real Discord desktop client with BetterDiscord installed.
- Verify that the affected interface elements render correctly.
- Check for visual regressions in relevant areas of the interface.
- Verify compatibility with the existing theme and check for conflicts with other custom CSS where applicable.
- Check the DevTools console for errors when relevant.
- Retest after addressing review feedback. Previous test results do not automatically validate subsequent changes.

Include a test plan in the pull request description. List the relevant scenarios, steps performed, results, and any remaining limitations. Attach screenshots when they help demonstrate the results.

Only mark a test as completed if it was actually performed. If a scenario could not be tested, state that clearly.

Testing claims and supporting evidence must correspond to the commit being reviewed. Static analysis and CSS validation are useful, but they do not replace testing the theme in Discord.

Pull requests with incomplete testing or unresolved visual issues may be returned for further work before review continues.

## AI-Assisted Contributions

AI coding tools are permitted, but their output must be reviewed, understood, and verified before submission.

Regardless of whether AI tools were used, the contributor is responsible for every change submitted, including its correctness, compatibility, and unintended side effects.

Contributors using AI tools are expected to:

- Understand the submitted changes and be able to explain their implementation.
- Review the complete diff instead of relying on AI-generated explanations or summaries.
- Verify selectors, properties, and other assumptions against the actual Discord interface and relevant documentation.
- Check for conflicting rules, unused declarations, unintended overrides, and visual regressions.
- Run appropriate tests and report the actual results without presenting assumptions as evidence of successful testing.
- Address review feedback by correcting the underlying issues rather than making superficial changes.

AI-assisted contributions are held to the same standards as any other submission. Using AI does not reduce the contributor's responsibility for testing or debugging their changes.

## CSS Guidelines

Follow the existing CSS structure and conventions used by the theme.

Changes should:

- Preserve the Windows 98-inspired visual design.
- Avoid unnecessary duplication and conflicting selectors.
- Keep modifications limited to their intended scope.
- Avoid unrelated formatting changes and restructuring.
- Remain compatible with the existing interface wherever possible.

Changes that introduce inconsistent styling, visual regressions, or unnecessary modifications may be rejected.

## Review Process

The maintainer may request changes, ask for additional tests, or close a pull request that is incomplete, insufficiently tested, outside the project's scope, or unsuitable for inclusion.

Review is intended to evaluate a contribution, not to replace the contributor's implementation, debugging, or testing work.

Submit changes that you have reviewed and tested to the best of your ability. Clear communication about limitations is preferable to claiming that unverified behavior works.
