# Contributing to Dyna Labs

This is an **internal contribution model inspired by open source**, not an invitation for public contributions.

## Before you start
1. Confirm the lab has a named **content owner** and **technical reviewer**.
2. Check for an existing lab or issue to avoid duplicates.
3. Open a **Lab proposal** issue describing audience, learning objectives, dependencies and delivery mode.
4. Coordinate with the appropriate subject-matter expert before developing product-specific guidance.

## Make a change
1. Create a branch; do not commit directly to the protected default branch.
2. Follow the [lab metadata template](templates/lab-metadata.yml) and [author checklist](docs/lab-author-checklist.md).
3. Keep content and implementation in version control. Future UI authoring should write to a branch and use the same review gates.
4. Run available framework checks and document any tests that cannot yet run automatically.
5. Open a pull request using the PR template, link the issue, and request reviews.

## Approval expectations
- **Content/domain owner or delegated SME:** accuracy, teaching quality, and continued maintenance commitment.
- **Technical maintainer:** framework compatibility, infrastructure, security-relevant implementation and automated validation.
- **Repository maintainers:** enforce checks and merge policy; they do not inherit ownership of authored lab content.

Until CODEOWNERS teams and enforcement are confirmed, these are **proposed requirements**, not claims of configured GitHub protection.

## After publication
Creators/content owners address failures and user-reported inaccuracies. If a broken lab is not repaired within an agreed timeframe, it may be unpublished from the supported profile. The exact SLA is pending a decision.

## Contributor License Agreement

Contributions to this project must be accompanied by a Contributor License
Agreement. You (or your employer) retain the copyright to your contribution;
this simply gives us permission to use and redistribute your contributions as
part of the project.

You generally only need to submit a CLA once, so if you've already submitted one
(even if it was for a different project), you probably don't need to do it
again.
