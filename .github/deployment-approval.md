Deployment Approval requested from {{ payload.sender.login }}.

Comment "Approved" to kick the deployment off.

=== DON'T CHANGE BELOW THIS LINE

{
    "runNumber":  {{ env.RUNNUMBER }},
    "environment": "{{ env.ENVIRONMENT }}"
}
