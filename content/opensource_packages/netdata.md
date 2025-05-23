---
name: Netdata
category: Monitoring/Observability
description: Netdata agents are real-time monitoring tools that gather performance metrics every second and display in visually intuitive dashboards, compatible with servers, virtual machines and cloud environments.
download_url: https://github.com/netdata/netdata/releases
works_on_arm: true
supported_minimum_version:
    version_number: 1.32.0
    release_date: 2021/12/01


optional_info:
    homepage_url: https://www.netdata.cloud/
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content:
        partner_content:
        official_docs: https://learn.netdata.cloud/docs/developer-and-contributor-corner/install-the-netdata-agent-from-a-git-checkout
    arm_recommended_minimum_version:
        version_number: 2.2.0
        release_date: 2025/01/22
        reference_content: https://github.com/netdata/netdata/releases/tag/v2.2.0
        rationale: Version 2.2.0 introduced significant performance optimizations targeting Parent-to-Parent streaming deployments, achieving 50% less memory usage across all installations, 50% reduced bandwidth usage, and 20% lower CPU utilization. While these improvements are general, they may benefit Arm-based systems.


optional_hidden_info:
    release_notes__supported_minimum: https://github.com/netdata/netdata/releases/tag/v1.32.0
    release_notes__recommended_minimum:
    other_info:

---
