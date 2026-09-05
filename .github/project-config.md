# Defect Triage Board - Project Setup Guide

## Project Name
**Defect Triage Board**

## Custom Statuses
The following statuses should be configured in the GitHub Project:

1. **New** - Newly reported defects awaiting initial triage
2. **In Progress** - Defects currently being investigated or resolved
3. **For Retest** - Defects fixed and ready for quality assurance retesting
4. **Done** - Completed defects (resolved or closed)

## How to Create the Project

### Steps:
1. Go to your repository: https://github.com/Justinako/IT414-Defect-Triage-Group
2. Click the **Projects** tab
3. Click **New project** button
4. Select **Table** layout (recommended for defect tracking)
5. Name it: **Defect Triage Board**
6. Click **Create project**
7. Configure the custom statuses:
   - Click on **Status** field settings
   - Add the four statuses listed above
   - Optionally set default view columns: Issue, Assignee, Labels, Status

## Mapping to Labels
- Issues with `status-new` → Status: New
- Issues with `status-in-progress` → Status: In Progress
- Issues with `status-for-retest` → Status: For Retest
- Issues with `duplicate`, `deferred`, or `not-a-defect` → Status: Done

## Field Recommendations
- **Priority**: priority-high, priority-medium, priority-low
- **Severity**: severity-critical, severity-high, severity-medium, severity-low
- **Assignee**: Team member responsible for the defect
- **Status**: New, In Progress, For Retest, Done
