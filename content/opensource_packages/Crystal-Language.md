---
name: Crystal Language
category: Languages and Frameworks
description: Crystal is a programming language designed for efficiency and performance, with a syntax similar to Ruby.
download_url: https://github.com/crystal-lang/crystal/releases
works_on_arm: true
supported_minimum_version:
    version_number: 0.20.0
    release_date: 2016/11/22


optional_info:
    homepage_url: https://crystal-lang.org/
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content:
        partner_content:
        official_docs: https://crystal-lang.org/reference/1.12/getting_started/index.html
    arm_recommended_minimum_version:
        version_number: 1.4.0
        release_date: 2022/04/06
        reference_content: https://github.com/crystal-lang/crystal/releases/tag/1.4.0
        rationale: This version introduced intrinsics.pause for aarch64, which is useful for busy loops inside a spinlock or a mutex implementation, and should provide some speedup in very high contention cases. Kindly refer [here](https://github.com/crystal-lang/crystal/pull/11742) for more.


optional_hidden_info:
    release_notes__supported_minimum: https://github.com/crystal-lang/crystal/releases/tag/0.20.0
    release_notes__recommended_minimum:
    other_info:

---
