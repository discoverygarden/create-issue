# Create Issue

GitHub action to create Jira issues and send Slack notifications for pull requests.

## Usage

### Inputs

- `project`: The Jira project to add the issue to.
- `summary`: The summary of the isssue.
- `description`: A description of the isssue.
- `transition`: Transtion to apply to the issue.
- `test-case`: Instructions on how to test the issue.
- `deployment-instructions`: Instructions on how to deploy the issue.
- `pull-url`: The URL of the pull request to create the issue about.

- `jira-url`: Base URL the Jira instance.
- `jira-user`: Email of the Jira API user.
- `jira-token`: API token of the Jira API user.
- `github-token`: GitHub access token
- `slack-webhook`: Optional Slack webhook URL to receive notifications.
