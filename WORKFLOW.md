# Dev Workflow: Linear + GitHub + AgentMail

## How it works

### 1. Task Intake
- **Linear**: Create an issue in the DEO or ALX team
- **Email**: Send a task to `prajakt-hermes@agentmail.to`
- **WhatsApp**: Message directly

### 2. Implementation
- Hermes picks up the task
- Creates a feature branch: `feat/<ISSUE-KEY>-description`
- Uses Claude Code for implementation
- Commits with conventional commit messages referencing the Linear issue

### 3. Review
- PR opened with description linking to Linear issue
- Prajakt reviews, Hermes addresses feedback
- On merge → Linear issue auto-updates

### 4. Notification
- Email summary sent via AgentMail on completion

## Conventions
- Branch naming: `feat/DEO-<N>-short-desc` or `fix/DEO-<N>-short-desc`
- Commit messages: `feat: description (DEO-8)` 
- PRs always reference the Linear issue URL
