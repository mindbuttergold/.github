<!-- omit from toc -->
# mindbuttergold 🧠 🧈 🏆

<!-- omit from toc -->
## Table of Contents

- [The Vision](#the-vision)
- [The Mission](#the-mission)
- [Guiding Values](#guiding-values)
- [Community Usage](#community-usage)
- [Contributing New Ideas](#contributing-new-ideas)
- [Code Contribution Guidelines](#code-contribution-guidelines)
  - [Commit Requirements](#commit-requirements)
  - [Pull Request Requirements](#pull-request-requirements)
  - [Code Contribution Process](#code-contribution-process)
- [Maintainers](#maintainers)

## The Vision

To help modern best practices become standard practice, across the software industry at large.

## The Mission

To make best practices tangible and accessible by housing production-quality, working demonstrations of software and infrastructure that the community can learn from, enhance, and use.

## Guiding Values

- ### Show, don't tell
  Best practices should be demonstrated through complete, working code setups.  
  Feedback must include clear, actionable methods for how to improve that code.

- ### Usability is expected
  All demonstrations should be applicable to at least a large portion of the community.  
  Community members should be able to use the code with as little friction as possible.

- ### Quality over speed
  Code must be production-quality, well-designed, proven to be working, and aligned with clearly supported best practices.  
  This project's development process is geared towards thoughtful demonstration of best practices, rather than moving fast. 

- ### Debate ideas, not people
  Discussion and debate are encouraged. The best answer wins.  
  Ad hominem arguments, or any form of asshole-ry, are not tolerated.

## Community Usage

This project is fully open source, and all code is freely usable and adaptable. See the LICENSE in each repository.

Each repository in this public organization houses one or more demonstrations of best practices.  
See the README in each repository for how to employ that code in your own projects or work.

## Contributing New Ideas

If you have a new idea for a best practice demonstration, but there is no relevant existing repository:

- Open a new "Idea" post in the [Discussions](https://github.com/orgs/mindbuttergold/discussions) section.
- If the idea receives at least 10 thumbs up, a maintainer will create a public repository for it (Github doesn't allow community members to create repositories directly). This bar is set high, to help promote engagement and ensure best practices demonstrated are valuable to the community at large.
- Once the repository is created, anyone can open a PR to contribute to it.

## Code Contribution Guidelines

Refer to the [CONTRIBUTING doc](../CONTRIBUTING.md). All repositories will also have a link to this doc when you submit your first PR.

Code should be clear, complete, and fully usable in real-world systems. It should align with mindbuttergold's [Guiding Values](https://github.com/mindbuttergold#guiding-values).

All contributions must include a `README.md` that explains how to use the code, including setup, prerequisites, and supporting references about the best practice demonstrated.

**Do not include:**

- Placeholder or unfinished code
- Code copied from other places with a license that does not permit its use in this project
- Redundant or self-evident code comments
- Emojis or other random AI-generated artifacts unrelated to functionality

Submissions that don't meet these expectations will be closed.

### Commit Requirements

All commits should follow [Conventional Commit standards](https://www.conventionalcommits.org/en/v1.0.0/) to allow us to perform automated semantic versioning. 

Also, please use clear and descriptive commit messages.

### Pull Request Requirements

All PRs must garner at least 5 "thumbs up" reactions from members of the community before it will be approved. Final review and approval is required by at least one maintainer before merging.

The number of required thumbs up from the community is intentionally set high, to ensure the contribution meets an agreed upon high-standard - given that the goal of this project is to model best practices.

Maintainers agree to review PRs that meet the contributing guidelines within 1 week of initial submission - to the best of their ability.

Every PR must include:
- A PR title that follows the same [Conventional Commit standards](https://www.conventionalcommits.org/en/v1.0.0/) as commits, and is clear and descriptive. 
- All sections of the PR template filled out. You can put N/A for a section if you feel it is not applicable, but a maintainer may ask you to fill it out prior to review / approval.

### Code Contribution Process

To contribute code to a repository in this project, follow these steps:

**1. Review the [Code Contribution Requirements](../CONTRIBUTING.md)**
**2. Fork the Repository** 

Go to the GitHub page of the repository and click the **"Fork"** button at the top-right corner. This creates a copy of the repository under your GitHub account. See [About Forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks) for more information.

**3. Clone Your Fork** 
  ```bash
  git clone <FORKED_REPO_URL>
  cd <FORKED_REPO_NAME>
  ```

**4. Add the Original Repository as Remote Upstream**

  ```bash
  git remote add upstream <ORIGINAL_REPO_URL>
  
  git remote -v
  ```

**5. Create a Feature Branch**

**6. Make Your Changes**

**7. Commit Your Changes**

Review the [Commit Requirements](#commit-requirements).

**8. Push Your Branch to Your Fork**

**9. Open a Pull Request in the Original Repo** 

Review the [Pull Request Requirements](#pull-request-requirements).

See [Creating a Pull Request From a Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) for more information.

**10. Solicit Community Feedback / Approval**

You can use any forum desired to solicit feedback from the community, such as LinkedIn, or Discussions within the repository or organization.

**11. Respond to Feedback**

Make any requested changes or provide supporting rationale for not making changes. Debate is welcome and encouraged, but abide by the [Code of Conduct](../CODE_OF_CONDUCT.md).

## Maintainers

This project is maintained by:
- [Lisa Stedman-Falls](https://github.com/Lstedmanfalls)
