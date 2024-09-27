**Change:** 

Any addition, modification or removal of an existing Configuration Item (CI) that affects IT services.

**Purpose of change management:**

- Control the lifecycle of all changes
- Minimise business impact of changes
- Produce successful changes compared to change failures

**Types of changes:**

- Standard change:
    - low risk, frequent
    - eg. Patching of the servers, windows updates.
    - Approval: Pre-approved
- Normal change:
    - Well-planned change
    - eg. Database migration, Replacement of component.
    - Approval: `CAB` approval needed
- Emergency change:
    - Urgent change for high-priority incidents
    - eg. Restoring a Downed Server
    - Approval: `eCAB` approval needed
- Retrospective change:
    - Emergency change documented after implementation
    - eg. Applying patch to mitigate security incident
    - Approval: eCAB approval needed

**High-level change management process:**

- Request for change (RFC)
- Change approval
- Change implementation
- Change validation/testing
- Change closure

**The 7 Rs of change management:**

- Who **Raised** the change
- **Reason** for the change
- **Return** expected from the change
- **Risks** involved
- **Resources** required:
- **Responsible** person for implementation
- **Relationship** to other changes

**Detailed change management process:**

- Request for change (RFC)
    - Raising Change request
    - eg. new feature need to be added in a application
- Prepare for change
    - Participants: SMEs, `CI` owners, vendors, related technical teams)
    - Agenda
        - 7R’s assessment
        - Technical assessment: testing of change in lower environments etc
        - Business Impact
        - Risk/Impact assessment
        - Rollback plan
            - Restore original CI state if anything goes wrong while implementing change or exceeds `change implementation window`.
        - Change Tasks and assignees
            - Finalise tasks/steps in order to implement change and technical teams who will be performing each task
        - Change implementation window
            - decide timeframe to implement change by considering impact on business (off  business hours, holidays, availability of resources etc)
        - Vendor dependency
        - Validate change
        - Submit change for approval
- CAB Meeting
    - Participants: Key stakeholders
    - Agenda: review changes and Get approval from CAB
- Implementation
    - Implement change in Change Implementation window
- Validation and testing
    - successful
        - closure of Change request
        - Documentation
    - Failed
        - Rollback the change
        - Raise problem ticket for Root cause analysis (RCA)

**Change failures can occur due to:**

- Unsuccessful implementation
- Change overrun (exceeding change implementation window)
- Lack of proper backup plan

**Interlock between Incident, Problem and Change Management:**

- Failed changes can trigger incidents
- Problems may be opened to investigate change failures
- Root causes found/ in problem management or Incident management may require changes
