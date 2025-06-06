---
name: Yarn
category: Databases - Big-data
description: Yarn is a package manager that doubles down as project manager. Whether user work on simple projects or industry monorepos, whether users are an open source developer or an enterprise user.
download_url: https://github.com/yarnpkg/berry/releases
works_on_arm: true
supported_minimum_version:
    version_number: 3.1.0
    release_date: 2021/10/25


optional_info:
    homepage_url: https://yarnpkg.com/
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content:
        partner_content:
        official_docs: https://yarnpkg.com/getting-started/install
    arm_recommended_minimum_version:
        version_number: 4.0.0
        release_date: 2023/10/23
        reference_content: https://yarnpkg.com/blog/release/4.0
        rationale: This version drops support for Node.js <18 and replaces yarnPath with Corepack for simpler version management. It introduces a new JavaScript-based constraints engine, replacing Prolog, and now includes all official plugins by default. A new Hardened Mode boosts lockfile security, especially in public GitHub PRs. UI has been revamped, with clearer install logs and config output. Performance sees a major leap—installs are up to 3x faster than Yarn 3.6, thanks to improved metadata caching.


optional_hidden_info:
    release_notes__supported_minimum: https://yarnpkg.com/blog/release/3.1
    release_notes__recommended_minimum:
    other_info: From version 3.1, Linux/ARM64 support is included in the .yarnc.yml (The user will be able to configure Yarn's internal settings in this file), kindly refer [here](https://yarnpkg.com/configuration/yarnrc#supportedArchitectures)

---

