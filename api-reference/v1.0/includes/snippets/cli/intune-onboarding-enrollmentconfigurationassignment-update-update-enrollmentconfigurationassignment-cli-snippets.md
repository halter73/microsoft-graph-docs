---
description: "Automatically generated file. DO NOT MODIFY"
---

```bash

mgc device-management device-enrollment-configurations assignments patch --device-enrollment-configuration-id {deviceEnrollmentConfiguration-id} --enrollment-configuration-assignment-id {enrollmentConfigurationAssignment-id} --body '{\
  "@odata.type": "#microsoft.graph.enrollmentConfigurationAssignment",\
  "target": {\
    "@odata.type": "microsoft.graph.configurationManagerCollectionAssignmentTarget",\
    "collectionId": "Collection Id value"\
  }\
}\
'

```