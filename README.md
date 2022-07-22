# cicod-db-design-challange

Entity relationship diagram for a sample worklfow application, with focus on showing the entities, attributes, relationship and cardinality.

## Assumptions
- One user cannot belong to more than one department
- Requests would be mapped to a preconfigured workflow as opposed to user's specifying approvers on request initiation
- There could be different approval workflows configured, hence one can either be set as default for all request (per department), or user selects one of many pre-configured workflow (for his/her department) per request
- An approval workflow would not have more than 9 steps
- Any user can be an approver subject to workflow configuration
