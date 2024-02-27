# Workflow Scripting

The Workflow Editor is an inferface for creating and modifying workflows by arranging and connecting activites to drive processes.

## Workflow Activity: if condition

The If activity checks a condition or script to determine if a yes or no transition should be takern if the workflow creator specifies both the condition and the advanced script, both must evaluate succeffully for activity to take the Yes transition.

## Workflow Activity: Wait for condition

The wait for condition activity causes the workflow to wait at this activity until the current record matches the specified condition. The workflow evaluates the wait for condition activity each time the current record is updated. USE this activity to pause a workflow indefinitely until a particular criteria is met by a record update

## Use Cases

Dynamically assign approvals to a specific group of users

Trigger a web service call via a workflow activity

