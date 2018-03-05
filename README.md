# Ovetime App

## Key requirement: comapany needs documentation that salaried employees did or did not get ovetime each week

## Models
- X Post -> date:date rationale:text
- X User -> Devise
- X AdminUser -> STI
- Auditlog

## Features:
- Approval Workflow
- SMS Sending -> link to approval or overtime input
- X Administrative admin dashboard
- X Block non admin and guest users
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI:
- X Bootstrap -> formatting
- X Icons from glyphicons
- X Update the styles for forms

## Refactor TODOS:
- X Refactor user association integration test in post_spec
- X Refactor posts/_form for admin user with status
- X Fix post_spec.rb:82 to user factories
- X Fix post_spec.rb:52 to have correct user reference and not require update