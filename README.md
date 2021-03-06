# Ovetime App

## Key requirement: comapany needs documentation that salaried employees did or did not get ovetime each week

## Models
- X Post -> date:date rationale:text
- X User -> Devise
- X AdminUser -> STI
- X Auditlog

## Features:
- X Approval Workflow
- X SMS Sending -> link to approval or overtime input -> integrate with Heroku scheduler
- X Administrative admin dashboard
- X Block non admin and guest users
- Email summary to managers for approval
- X Needs to be documented if employee did not log overtime
- X Create audit log for each text message
- X Need to update end_date when confirmed
- X Need to update the audit log status when an ovetime rejected
- X Home Icon
- X Update buttons on employee homepage so they show on mobile
- X Update buttons to include time span
- X Update button sort order on employee homepage
- X Remove unnecessary nav bar buttons for managers
- X Fix admin dashboard bug
- Implement honeybadger for error reporting
- Implement new Relic for keeping the site alive

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