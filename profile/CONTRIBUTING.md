# Contributing to Finley Labs

Welcome to **Finley Labs**.

We appreciate your interest in contributing to our projects. Whether you're fixing a bug, improving documentation, reproducing an experiment, proposing an idea, or building a new feature, your contribution can help improve the work we share with the community.

> **Research. Build. Experiment. Share.**

These guidelines provide a general contribution process for Finley Labs repositories. Individual repositories may have additional requirements, so always check the repository's documentation before contributing.

---

## How to Contribute

We welcome contributions in many forms, including:

- Code
- Documentation
- Bug fixes
- Tests
- Research implementations
- Experiment reproductions
- Data analysis
- Security research
- Feature proposals
- Performance improvements
- Tutorials and examples
- Technical reviews

### 1. Find a Project

Explore the [Finley Labs repositories](https://github.com/Finley-Labs) and find a project that interests you.

Before starting work, check:

- The repository `README.md`
- Existing issues
- Open pull requests
- Project documentation
- Contribution guidelines
- License
- Security policy, where applicable

If you're planning a significant change, consider opening an issue or discussion first so the approach can be discussed before substantial work begins.

---

### 2. Fork the Repository

If you are not a repository collaborator, fork the repository to your GitHub account.

Then clone your fork:

```bash
git clone https://github.com/YOUR-USERNAME/REPOSITORY.git
cd REPOSITORY
```

Add the upstream repository:

```bash
git remote add upstream https://github.com/Finley-Labs/REPOSITORY.git
```

---

### 3. Create a Branch

Create a dedicated branch for your work.

```bash
git checkout -b feature/your-feature-name
```

Use a descriptive branch name that clearly communicates the purpose of the change.

See the [Branch Naming](#branch-naming) section below for recommended conventions.

---

### 4. Make Your Changes

Make your changes while following the conventions established by the repository.

Aim for contributions that are:

- Clear
- Focused
- Maintainable
- Well documented
- Tested where appropriate
- Consistent with the existing project

Avoid combining unrelated changes into a single pull request.

---

### 5. Test Your Changes

Run the project's existing tests and validation tools before submitting your contribution.

Depending on the project, this may include:

- Unit tests
- Integration tests
- Linters
- Formatters
- Type checking
- Build processes
- Security checks
- Research experiment validation
- Benchmarking

If you introduce new functionality, add appropriate tests where practical.

If you cannot run a particular test or experiment, explain the limitation in your pull request.

---

### 6. Commit Your Changes

Write clear and meaningful commit messages.

For example:

```bash
git commit -m "Add authentication middleware"
```

Good commit messages should describe **what changed**, rather than simply saying:

```text
Update files
Fix stuff
Changes
```

For larger contributions, consider using multiple focused commits rather than one very large commit.

---

### 7. Push Your Branch

Push your branch to your fork:

```bash
git push origin feature/your-feature-name
```

---

### 8. Open a Pull Request

Open a pull request against the appropriate branch of the Finley Labs repository.

Your pull request should explain:

- What you changed
- Why you made the change
- How you implemented it
- How you tested it
- Any limitations or known issues
- Any relevant issues or discussions

Keep pull requests focused and reasonably sized whenever possible.

---

## Pull Request Guidelines

A strong pull request should make it easy for maintainers to understand and review the proposed change.

### Pull Request Checklist

Before submitting, make sure:

- [ ] The change addresses a specific problem or objective.
- [ ] The code follows the repository's conventions.
- [ ] Tests have been added or updated where appropriate.
- [ ] Existing tests pass.
- [ ] Documentation has been updated where necessary.
- [ ] No unnecessary files or generated artifacts have been committed.
- [ ] Commit messages are clear.
- [ ] The pull request description explains the change.
- [ ] Security-sensitive information such as credentials or private keys has not been committed.

---

## Code Contributions

When contributing code:

- Follow the project's existing architecture and conventions.
- Prefer simple and maintainable solutions.
- Keep functions and modules focused.
- Avoid unnecessary dependencies.
- Handle errors appropriately.
- Add tests for meaningful behavior.
- Document non-obvious decisions.
- Avoid introducing unrelated refactoring.

If a repository provides a specific formatter, linter, or style guide, follow that project's requirements.

---

## Documentation Contributions

Documentation is an important part of Finley Labs projects.

You can contribute by:

- Fixing errors
- Improving explanations
- Adding examples
- Improving installation instructions
- Adding tutorials
- Documenting APIs
- Improving research methodology
- Clarifying experiment reproduction steps

Documentation should be accurate, concise, and accessible to its intended audience.

---

## Research Contributions

Some Finley Labs repositories contain research experiments, simulations, datasets, benchmarks, or implementations of published work.

When contributing to research-oriented projects, prioritize **reproducibility and transparency**.

Where applicable, document:

- Dataset sources
- Data preprocessing
- Experimental configuration
- Dependencies
- Hardware requirements
- Random seeds
- Evaluation methodology
- Baselines
- Relevant papers
- Known limitations

If reproducing published research, clearly distinguish between:

1. The original methodology.
2. Your implementation.
3. Any modifications or assumptions.
4. Your experimental results.

Do not present reproduced or experimental results as original findings unless they genuinely are.

---

## Security Contributions

Security issues should **not** be publicly disclosed through ordinary GitHub issues when doing so could expose a vulnerability before it can be addressed.

If a repository contains a `SECURITY.md` file, follow the security reporting procedure described there.

For security-sensitive research, use responsible disclosure practices and avoid publishing operational details that could unnecessarily enable abuse.

---

## Reporting Bugs

If you discover a bug, open an issue in the appropriate repository unless the issue is security-sensitive.

A useful bug report should include:

- A clear description of the problem
- Steps to reproduce it
- Expected behavior
- Actual behavior
- Relevant error messages
- Operating system
- Runtime or language version
- Relevant dependency versions
- Logs or screenshots where useful

A minimal reproducible example is especially helpful.

---

## Feature Requests

Before proposing a significant feature, consider opening an issue or discussion.

Explain:

- The problem you are trying to solve
- Why the problem is important
- The proposed solution
- Alternative approaches considered
- Potential use cases
- Any trade-offs or limitations

Feature proposals should focus on solving a problem rather than simply adding functionality.

---

## Branch Naming

Use descriptive branch names.

Recommended conventions:

| Branch | Purpose |
| --- | --- |
| `feature/description` | New functionality |
| `fix/description` | General bug fixes |
| `hotfix/description` | Urgent fixes |
| `docs/description` | Documentation changes |
| `refactor/description` | Code restructuring |
| `test/description` | Test-related changes |
| `research/description` | Research or experimental work |
| `experiment/description` | Experimental implementations |

Examples:

```text
feature/user-authentication
fix/data-loader-error
docs/update-installation
research/malware-classification
experiment/model-comparison
```

---

## Keeping Your Fork Updated

Before beginning new work, synchronize your local repository with upstream:

```bash
git fetch upstream
git checkout main
git merge upstream/main
```

Then create your feature branch:

```bash
git checkout -b feature/your-feature-name
```

If the repository uses a different default branch, follow that repository's instructions.

---

## Review Process

All contributions are subject to review.

Maintainers may request:

- Code changes
- Additional tests
- Documentation updates
- Clarification
- Experimental validation
- Performance evaluation
- Security review
- Changes to the proposed approach

Please treat review as part of the collaborative development process.

The goal is not simply to merge code, but to maintain the quality, reliability, and long-term value of the project.

---

## Community Standards

Contributors are expected to communicate respectfully and constructively.

We welcome people with different levels of experience and backgrounds.

Please:

- Be respectful.
- Assume good intentions.
- Give constructive feedback.
- Focus criticism on ideas and implementations rather than individuals.
- Avoid harassment or discriminatory behavior.
- Respect project maintainers and other contributors.

Participation in Finley Labs projects is subject to the applicable **[Code of Conduct](CODE_OF_CONDUCT.md)**.

---

## Licensing

Each Finley Labs repository may have its own license.

Before contributing, review the repository's `LICENSE` file.

Unless otherwise stated by the project, contributions should be compatible with the project's existing licensing terms.

By submitting a contribution, you agree that the contribution may be distributed under the license applicable to the repository to which you contributed.

If you are unsure about the licensing implications of a contribution, open a discussion with the project maintainers before submitting it.

---

## Questions and Discussions

If you are unsure about how to contribute, start a discussion or open an issue in the relevant repository.

For project-specific questions, always prefer the repository's own issue tracker or discussion area so that future contributors can benefit from the conversation.

Visit **[finleylabs.cc](https://finleylabs.cc)** to learn more about Finley Labs and our ongoing work.

---

## Thank You

Thank you for contributing to Finley Labs.

Whether you contribute a line of code, improve a sentence in the documentation, reproduce an experiment, report a problem, or share an idea, your contribution helps make the projects better.

**Research. Build. Experiment. Share.**

— **Finley Labs**