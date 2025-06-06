---
name: KubeVirt
category: Miscellaneous
description: Kubernetes Virtualization API and runtime in order to define and manage virtual machines.
download_url: https://github.com/kubevirt/kubevirt/releases
works_on_arm: true
supported_minimum_version:
    version_number: v0.41.0
    release_date: 2021/05/12


optional_info:
    homepage_url: https://kubevirt.io/
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content:  https://community.arm.com/arm-community-blogs/b/tools-software-ides-blog/posts/empowering-software-development-with-works-on-arm-initiative
        partner_content:
        official_docs: https://kubevirt.io/user-guide/operations/installation/#arm64-developer-builds
    arm_recommended_minimum_version:
        version_number: 1.5.1
        release_date: 2025/05/06
        reference_content: https://github.com/kubevirt/kubevirt/releases/tag/v1.5.1
        rationale: This release enables the node-labeller for ARM64 clusters by introducing an architecture abstraction layer (archLabeller interface and implementations). Direct architecture checks (runtime.GOARCH) are replaced by calls to this interface, allowing architecture-specific logic (like handling host features, CPU models, and vendor names) to be encapsulated. The label preparation logic is refactored to use this abstraction, ensuring appropriate labels (including machine types) are applied based on the detected architecture's capabilities. The startup check restricting the labeller to specific architectures is removed.

optional_hidden_info:
    release_notes__supported_minimum: https://github.com/kubevirt/kubevirt/releases/tag/v0.41.0
    release_notes__recommended_minimum:
    other_info: In the [kubevirt documentation](https://kubevirt.io/quickstart_minikube/), it is mentioned that testing is done using the virtctl binary. For the version 0.41, the virtctl binaries are not released for arm64, but in the release notes it is mentioned that kubevirt supports the arm64. From 1.0.0-rc.0 version, virtctl binaries are released for arm64.

---
