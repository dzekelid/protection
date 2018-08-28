swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 1
info:
  title: AWS Auto Scaling API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetInstanceProtection:
    get:
      summary: Set Instance Protection
      description: Updates the instance protection settings of the specified instances.
      operationId: setInstanceProtection
      x-api-path-slug: actionsetinstanceprotection-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the group
        type: string
      - in: query
        name: InstanceIds.member.N
        description: One or more instance IDs
        type: string
      - in: query
        name: ProtectedFromScaleIn
        description: Indicates whether the instance is protected from termination
          by Auto Scaling when scaling in
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Protection