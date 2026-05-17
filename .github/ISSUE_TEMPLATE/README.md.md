

Ad 📺	https://github.com/MahakaalGH/infra_workflows/issues/281
Bug 🐞	https://github.com/MahakaalGH/infra_workflows/issues/261
Checklist ✅	https://github.com/MahakaalGH/infra_workflows/issues/262
Content 📝	https://github.com/MahakaalGH/infra_workflows/issues/263
Credential 🔑	https://github.com/MahakaalGH/infra_workflows/issues/264
Data 💾	https://github.com/MahakaalGH/infra_workflows/issues/265
Epic 🏔️	https://github.com/MahakaalGH/infra_workflows/issues/266
Event 🗓️	https://github.com/MahakaalGH/infra_workflows/issues/267
Feature 🧩	https://github.com/MahakaalGH/infra_workflows/issues/268
Flag 🚩	https://github.com/MahakaalGH/infra_workflows/issues/295
Goal 🏁	https://github.com/MahakaalGH/infra_workflows/issues/269
Incident 🚨	https://github.com/MahakaalGH/infra_workflows/issues/270
Measure 📈	https://github.com/MahakaalGH/infra_workflows/issues/282
Prompt 🤖	https://github.com/MahakaalGH/infra_workflows/issues/271
Publish 📢	https://github.com/MahakaalGH/infra_workflows/issues/272
Scenario ➡️	https://github.com/MahakaalGH/infra_workflows/issues/280
Security 🛡️	https://github.com/MahakaalGH/infra_workflows/issues/273
Story 🌟	https://github.com/MahakaalGH/infra_workflows/issues/274
Task 📀	https://github.com/MahakaalGH/infra_workflows/issues/275
Test 🧪	https://github.com/MahakaalGH/infra_workflows/issues/294
Training 🏋	https://github.com/MahakaalGH/infra_workflows/issues/276
Upgrade 🧬	https://github.com/MahakaalGH/infra_workflows/issues/277
Workflow 🔄	https://github.com/MahakaalGH/infra_workflows/issues/278
# Github Issues

To manage all issue types and its connected project details for this org.

## 1. Default Issue Types

| No. | Type          | Description                             | Color  | Project Name  | Project ID | Apply to |
| :-- | :------------ | :-------------------------------------- | :----- | :------------ | :--------- | :------- |
| 01  | Ads 📺        | Advertising campaign or placement       | gray   | Any           | 68         | Org      |
| 02  | Bug 🐞        | Unexpected problem or behavior          | red    | Product ✨    | 43         | Org      |
| 03  | Checklist ✅  | Stepwise process or review              | gray   | Checklist ✅  | 63         | Org      |
| 04  | Content 📝    | Documentation or copy update            | gray   | Product ✨    | 43         | Org      |
| 05  | Credential 🔑 | Auth or access credentials              | gray   | Credential 🔑 | 17         | Org      |
| 06  | Data 💾       | Data records or info management         | gray   | Any           |            | Org      |
| 07  | Epic 🏔️       | Large work split into smaller tasks     | orange | Epic 🏔️       | 66         | Org      |
| 08  | Event 🗓️      | A planned event, activity, or milestone | gray   | Calendar 🗓️   | 21         | Org      |
| 09  | Feature 🧩    | A request, idea or new functionality    | green  | Product ✨    | 43         | Org      |
| 10  | Goal 🏁       | Outcome or objective definition         | pink   | Goal 🏁       | 28         | Org      |
| 11  | Incident 🚨   | Urgent operational disruption           | red    | Product ✨    | 43         | Org      |
| 12  | Measure 📈    | Metrics and analytics tracking          | gray   | Measure 📈    | 42         | Org      |
| 13  | Offering 📦   | Product or service details              | gray   | Offering 📦   | 69         | Org      |
| 14  | Prompt 🤖     | Instruction for AI-driven process       | gray   | Prompt 🤖     | 51         | Org      |
| 15  | Publish 📢    | Marketing workflow tracking             | gray   | Publish 📢    | 54         | Org      |
| 16  | Scenario ➡️   | User scenario or use case               | gray   | Scenario ➡️   | 43         | Org      |
| 17  | Security 🛡️   | Vulnerability or risk mitigation        | red    | Product ✨    | 43         | Org      |
| 18  | Story 🌟      | User-focused narrative or journey       | yellow | Product ✨    | 43         | Org      |
| 19  | Task 📀       | Single, trackable work activity         | gray   | Any           |            | Org      |
| 20  | Time Block 🕒 | Scheduled time slot                     | gray   | Any           |            | Org      |
| 21  | Training 🏋   | Learning or practice to improve skills  | gray   | Training 🏋   | 62         | Org      |
| 22  | Upgrade 🧬    | Requirements or code updates            | purple | Product ✨    | 43         | Org      |
| 23  | Workflow 🔄   | Process or sequence of tasks            | gray   | Workflow 🔄   | 65         | Org      |

## 2. Custom Issue Types

| No.  | Type          | Description                             | Color  | Project Name  | Project ID | Apply to |
| :-- | :------------ | :-------------------------------------- | :----- | :------------ | :--------- | :------- |
| 01  | Feedback 💬   | Suggestions or user input               | gray   | Product ✨    | 67         | Org      |
| 02  | Org 🏢        | An organization or company              | gray   | Org 🏢        | 58         | Org      |
| 03  | Person 👤     | A person, team member, or individual    | gray   | Person 👤     | 59         | Org      |
| 04  | Profile ℹ️    | User profile, account, or identity      | gray   | Profile ℹ️    | 57         | Org      |
| 05  | Asset 🖥️      | Physical or digital asset               | gray   | Asset 🖥️      | 34         | Org      |
| 06  | IP 🛡️        | Intellectual property management       | gray   | IP 🛡️        | 61         | Org      |

## Workflow Steps

This workflow automates updating GitHub organization issue types.

1. **Create Issue Types**: Creates issue types for organizations except `StaytunedLLP`.

> **Important:** Script deletes issue types. Review first. Needs `gh` and `jq`, login with `gh auth login`.

### Automation Script

`src/handbook/engineering/_refs/scripts/github/create_issue_types.sh`

How to run the script:

Copy and paste the following command in your terminal from the root of the repository:

```bash
cd src/handbook/engineering/_refs/scripts/github && ./create_issue_types.sh
```
