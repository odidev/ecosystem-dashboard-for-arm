---
name: Cloud Custodian
category: Security applications
description: Rules engine for cloud security, cost optimization, and governance, DSL in yaml for policies to query, filter, and take actions on resources.
download_url: https://github.com/cloud-custodian/cloud-custodian/releases
works_on_arm: true
supported_minimum_version:
    version_number: 0.8.2
    release_date: 2016/04/17


optional_info:
    homepage_url: https://cloudcustodian.io/
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content:
        partner_content:
        official_docs: https://cloudcustodian.io/getting-started/
    arm_recommended_minimum_version:
        version_number: 0.9.21.0
        release_date: 2022/12/15
        reference_content: https://github.com/cloud-custodian/cloud-custodian/releases/tag/0.9.21.0
        rationale: This version introduced changes to the code to make custodian lambdas aws graviton compatible.

optional_hidden_info:
    release_notes__supported_minimum:
    release_notes__recommended_minimum:
    other_info: Cloud Custodian is not architecture-specific and any wheels are released on [PyPI](https://pypi.org/project/c7n/#files).

---
