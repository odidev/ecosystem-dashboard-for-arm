---
name: Eclipse Temurin (Eclipse Adoptium)
category: Runtimes
description: Eclipse Adoptium provides high-quality runtimes and related technology to use within the Java ecosystem. The Eclipse Adoptium project is a continuation of the original AdoptOpenJDK mission, and Eclipse Temurin is the OpenJDK distribution from Adoptium.
download_url: https://adoptium.net/temurin/releases/
works_on_arm: true
supported_minimum_version:
    version_number: 8.0.412+8
    release_date: 2024/04/18


optional_info:
    homepage_url: https://projects.eclipse.org/projects/adoptium
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content:
        partner_content:
        official_docs: https://adoptium.net/installation/linux/
    arm_recommended_minimum_version:
        version_number: 21
        release_date: 2024/08/09
        reference_content: https://adoptium.net/news/2024/08/adoptium-reproducible-verification-builds
        rationale: Eclipse Temurin JDK 21+ releases are now fully reproducible for many platforms, including Linux Aarch64. This ensures nothing malicious or unexpected is embedded in the binaries. This is a major milestone for transparency, security, and trustworthiness, especially for environments like Linux/Arm64 where deterministic builds can reduce platform-specific bugs.

optional_hidden_info:
    release_notes__supported_minimum:
    release_notes__recommended_minimum:
    other_info: There are no release notes available for Linux/ARM64. The minimum supported version in Temurin for AArch64 is 8.

---
