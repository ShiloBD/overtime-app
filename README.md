# Ovetime App

## Key requirement: comapany needs documentation that salaried employees did or did not get ovetime each week

## Models
- X Post -> date:date rationale:text
- X User -> Devise
- X AdminUser -> STI
- X Auditlog

## Features:
- X Approval Workflow
- SMS Sending -> link to approval or overtime input -> integrate with Heroku scheduler
- X Administrative admin dashboard
- X Block non admin and guest users
- Email summary to managers for approval
- X Needs to be documented if employee did not log overtime

## UI:
- X Bootstrap -> formatting
- X Icons from glyphicons
- X Update the styles for forms

## TODOS:
- X Refactor user association integration test in post_spec
- X Refactor posts/_form for admin user with status
- X Fix post_spec.rb:82 to user factories
- X Fix post_spec.rb:52 to have correct user reference and not require update
- X Integrate validation for phone attr in User:
    # No space or dashes
    # Exactly 10 characters
    # All characters have to be a number