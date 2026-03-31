# Work with Workflow Artifacts

_Learn how to upload, preview, download, and reuse workflow artifacts in GitHub Actions._

## Welcome

- **Who is this for**: Developers and DevOps engineers who want to learn how to use workflow artifacts in GitHub Actions to store and share data across jobs and workflows.
- **What you'll learn**: How to upload workflow artifacts, use direct single-file uploads, download artifacts in downstream jobs and workflows, and gate deployments with environments.
- **What you'll build**: A CI/CD workflow setup that publishes test reports as artifacts, reuses a build artifact for deployments, and includes an optional production approval gate.
- **Prerequisites**:
  - Basic familiarity with GitHub Actions workflows
  - Recommended GitHub Skills exercises:
    - [Hello GitHub Actions](https://github.com/skills/hello-github-actions)
    - [Test with Actions](https://github.com/skills/test-with-actions)

- **How long**: This exercise takes less than an hour to complete.

In this exercise, you will:

1. Create a CI workflow that uploads a coverage report as a workflow artifact.
1. Upload a Playwright HTML report as a direct single-file artifact that opens in the browser.
1. Build once and reuse that build artifact in a downstream deployment job.
1. Download artifacts across workflows and add an optional production approval gate.

### How to start this exercise

Simply copy the exercise to your account, then give your favorite Octocat (Mona) **about 20 seconds** to prepare the first lesson, then **refresh the page**.

[![](https://img.shields.io/badge/Copy%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=skills&template_name=workflow-artifacts&owner=%40me&name=skills-workflow-artifacts&description=Exercise:+Work+with+Workflow+Artifacts&visibility=public)

<details>
<summary>Having trouble? 🤷</summary><br/>

When copying the exercise, we recommend the following settings:

- For owner, choose your personal account or an organization to host the repository.

- We recommend creating a public repository, since private repositories will use Actions minutes.

If the exercise isn't ready in 20 seconds, please check the [Actions](../../actions) tab.

- Check to see if a job is running. Sometimes it simply takes a bit longer.

- If the page shows a failed job, please submit an issue. Nice, you found a bug! 🐛

</details>
