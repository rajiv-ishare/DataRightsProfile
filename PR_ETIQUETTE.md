# 🤝 Pull Request Etiquette

This guide provides best practices for both contributors and reviewers to ensure smooth collaboration and efficient reviews.

---

## 🧑‍💻 For Contributors

Before submitting a pull request (PR), please follow these guidelines:

### 📚 Prepare Before You Code
- Read through the [contributing guidelines](CONTRIBUTING.md).
- Open a [discussion](https://github.com/eclipse-dataspace-drp/DataRightsProfile/discussions/new) or [issue](https://github.com/eclipse-dataspace-drp/DataRightsProfile/issues/new) to share your idea before starting. This gives others a chance to offer feedback early. 
- It's helpful to `@mention` committers for visibility. PRs without prior discussion may be delayed or declined.

### 🎯 Keep It Focused
- Address **one** issue or feature per PR.
- Avoid submitting massive, multi-topic changes—these "PR bombs" are hard to review and likely to be rejected.

### 📝 Write a Great PR Description
- Clearly explain **what** your PR does and **why**.
- Summarize the key changes so reviewers understand the scope at a glance.

### ✅ Meet the Technical Requirements
- Ensure all tests pass before marking your PR `"Ready for review"`.
- Only mark as “Ready for review” when the work is complete. Additional changes should only address reviewer feedback.
- Resolve merge conflicts by rebasing on `main` and force-pushing your branch **before** requesting a review.

### 🙋‍♂️ Request Reviews Thoughtfully
- If your PR is still a draft but needs feedback, `@mention` the relevant reviewer and explain what needs their input.
- When ready, request a review from at least one [project committer](https://projects.eclipse.org/projects/technology.dataspace-drp/who). Others may review, but only committers can approve merges.
- After making changes based on feedback, re-request a review to help track progress.

### 🧠 Communicate & Collaborate
- You’re welcome to push back on feedback — discussion is encouraged!
- However, if consensus isn’t reached, be prepared to either accept the final decision or withdraw the PR.

### 🤝 Be Respectful
- Maintain a professional, constructive tone.
- Absolutely no profanity, insults, or abusive behavior.

### 🏷️ Use the Right PR Title Format
- Follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/):
  ```
  <type>(<optional scope>): <description>
  ```
  - Examples of valid types: `feat`, `fix`, `docs`, `refactor`, `test`, `ci`, `style`, `build`, `chore`, `perf`, `revert`
  - Keep titles under **80 characters**.

---

## 👀 For Reviewers

### 🕐 Timely Reviews
- Aim to review within **five business days**.
- If you’re unavailable or unsure of the topic, leave a comment and unassign yourself. Recommend a suitable replacement if possible.

### 🤓 Review With Care
- Don’t rubber-stamp PRs. Take time to review thoroughly.
- Avoid nitpicking minor issues unless they significantly impact clarity or quality.
- Don’t challenge established project-wide principles unless previously discussed.

### 🙌 Encourage Contributions
- Provide respectful, constructive feedback.
- Uphold a welcoming environment for contributors—especially first-timers!

### ✅ Merging Criteria
- A PR can be merged by a committer **after approval from at least one other committer**, as long as there are no outstanding objections.
