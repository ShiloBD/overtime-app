# Ovetime App

## Key requirement: comapany needs documentation that salaried employees did or did not get ovetime each week

## Models
- X Post -> date:date rationale:text
- X User -> Devise
- X AdminUser -> STI

## Features:
- Approval Workflow
- SMS Sending -> link to approval or overtime input
- Administrative admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI:
- Bootstrap -> formatting

## Refactor TODOS:
- Refactor user association integration test in post_spec