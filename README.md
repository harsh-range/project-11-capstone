# Project 11: Infra Changes with Branching Policy

## Overview
This project demonstrates Git branching and Pull Request workflow using the existing **Project 7 repository (capstone-project7)**.

## Steps Performed
- Created feature branch: `feature/update-infra`
- Updated Terraform configuration
- Committed and pushed changes
- Created Pull Request (PR)
- Reviewed and merged PR into `main`

## Infrastructure Change

```hcl
resource "null_resource" "example" {
  triggers = {
    project = "Project11"
  }
```