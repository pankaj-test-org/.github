# pankaj-test-org

A testing organization for GitHub-Jenkins integration and CI/CD workflows.

## Overview

This organization hosts test repositories used for validating GitHub-Jenkins integrations, CI/CD pipelines, and automation workflows for CloudBees products.

## Repositories

### [marvels-mock](https://github.com/pankaj-test-org/marvels-mock)
**Public** | Java | Topics: `gh-jen-int`, `marvels-mock`

Test repository for CloudBees CI + GitHub integration with ReRunCause testing. Validates that CloudBees GitHub Reporting plugin generates native `ReRunCause` when GitHub's Re-run button is clicked.

- **Purpose:** CBP-31531 fix validation
- **Key Features:** Configurable build failures, ReRunCause verification
- **Status:** Active (last updated April 2026)
- **Forks:** 3

### [potential-train](https://github.com/pankaj-test-org/potential-train)
**Private** | Java | Topics: `gh-jen-int`, `potential-train`

Test repository providing fake APIs for Jenkins integration testing.

- **Purpose:** API mocking for Jenkins test scenarios
- **Language:** Java
- **Status:** Active (last updated December 2025)

## What We Test

This organization serves as a testing environment for:

- **GitHub-Jenkins Integration:** Validating webhook handling, branch indexing, and build triggers
- **CloudBees CI Features:** GitHub Reporting plugin, build causes, check runs
- **CI/CD Pipelines:** Multibranch pipelines, automated builds, deployment workflows
- **GitHub Actions:** Workflow integration with Jenkins, dual CI testing
- **Failure Scenarios:** Controlled build failures, re-run functionality, error handling

## Key Testing Capabilities

### Configurable Build Failures
Repositories support environment-based failure injection:
- **Jenkins:** `JENKINS_FAIL_BUILD` environment variable
- **GitHub Actions:** `GH_CHECK_FAIL` repository variable

### ReRunCause Validation
Verifies CloudBees GitHub Reporting plugin behavior when GitHub checks are re-run, ensuring proper build cause attribution.

## Getting Started

### Clone a Repository
```bash
git clone https://github.com/pankaj-test-org/<repository-name>.git
```

### Access Requirements
- Public repositories: Open to all
- Private repositories: Contact organization owner for access

### Testing Workflow
1. Configure Jenkins multibranch pipeline pointing to the test repository
2. Set environment variables for desired test behavior
3. Trigger builds via GitHub webhooks or manual triggers
4. Verify Jenkins console output and GitHub checks
5. Test re-run functionality and validate build causes

## Topics

Common topics across repositories:
- `gh-jen-int` - GitHub-Jenkins integration
- `marvels-mock` - CloudBees CI testing
- `potential-train` - API mocking

## Contributing

These are test repositories used for integration testing of CloudBees products. Contact the organization owner for access and contribution guidelines.

## Related Projects

- **CloudBees CI:** Enterprise Jenkins distribution
- **CloudBees GitHub Reporting Plugin:** Native GitHub checks integration
- **Platform/Unify Project:** Parent project for some integration work

## Contact

For questions, access requests, or collaboration inquiries, please contact the organization administrators.

---

*Organization for testing GitHub-Jenkins integrations | Last updated: April 2026*
