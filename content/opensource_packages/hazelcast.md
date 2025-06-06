---
name: Hazelcast
category: Databases - Big-data
description: Hazelcast provides a distributed compute engine and a fast data store in one runtime. It offers better performance and scale for real-time and AI-driven applications.
download_url: https://hazelcast.com/get-started/download/#hazelcast-platform
works_on_arm: true
supported_minimum_version:
    version_number: 5.3.0
    release_date: 2023/05/19


optional_info:
    homepage_url: https://hazelcast.com/
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content:
        partner_content:
        official_docs: https://docs.hazelcast.com/hazelcast/5.4/getting-started/install-hazelcast
    arm_recommended_minimum_version:
        version_number: 5.5.0
        release_date: 2024/07/26
        reference_content: https://docs.hazelcast.com/hazelcast/6.0-snapshot/release-notes/5-5-0
        rationale: Hazelcast 5.5 introduces major new features, including a vector collection data structure, Jet job placement control, and dynamic configuration via REST API. It adds Feast feature store integration and supports Debezium 2.x connectors, expanding stream processing and ML integration capabilities. A key structural change is the introduction of Long-Term Support (LTS) releases. For Java clients, multi-member routing and new cluster-routing options replace the now-deprecated smart-routing configuration. Thread-per-core (TPC) execution now requires cluster-routing, and the CP Subsystem becomes exclusive to the Enterprise Edition.

optional_hidden_info:
    release_notes__supported_minimum: https://docs.hazelcast.com/hazelcast/5.3/release-notes/5-3-0#other-enhancements
    release_notes__recommended_minimum:
    other_info:

---
