# SIT223/SIT753 Credit Task Starter Kit

This folder contains ready-to-use templates for:

- Part 1 Task 1 (7-stage mock pipeline)
- Part 1 Task 2 (DevSecOps basics with `nodejs-goof`)
- Part 2 Option A (SonarCloud integration)
- Part 2 Option B (Extended Email Notifications)

## 1) Mandatory: Part 1 Task 1 (Mock 7-stage pipeline)

Use `Jenkinsfile.part1-task1-mock`.

It prints each required stage and a suggested tool, matching the rubric.

## 2) Mandatory: Part 1 Task 2 (DevSecOps basics)

Use `Jenkinsfile.part1-task2-devsecops`.

Before running:

1. Create your GitHub repo: `8.2CDevSecOps`
2. Clone and push `nodejs-goof` into your repo
3. In Jenkins, create a Pipeline job and point to your Jenkinsfile
4. Replace `YOUR_GITHUB_USERNAME` inside the Jenkinsfile

## 3) Choose ONE for Part 2

### Option A: SonarCloud

Use:

- `Jenkinsfile.part2-sonarcloud`
- `sonar-project.properties` (update placeholders)

In Jenkins credentials:

- Add secret text token
- Credential ID must be: `SONAR_TOKEN`

### Option B: Email Notifications

Use:

- `Jenkinsfile.part2-email-ext`

In Jenkins:

1. Install `Email Extension Plugin`
2. Configure SMTP in `Manage Jenkins > Configure System`
3. Replace `your.email@example.com` in the Jenkinsfile

## 4) Suggested order to finish fast

1. Run Part 1 Task 1 pipeline and record short video
2. Run Part 1 Task 2 pipeline and record short video
3. Pick one Part 2 option and run + record
4. Put video links in a submission PDF

## 5) Video checklist (from rubric)

- Include voice
- Say full name + student ID at start
- Show Jenkinsfile + pipeline execution + console output
- Ensure sharing links are accessible by tutor

"auto trigger demo" 
