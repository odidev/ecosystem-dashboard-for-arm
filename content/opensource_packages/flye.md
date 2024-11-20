---
name: Flye
category: Miscellaneous
description: Flye is an assembler for single-molecule sequencing reads, and is designed for a wide range of datasets, from small bacterial projects to large mammalian-scale assemblies.
download_url: https://github.com/mikolmogorov/Flye/releases
works_on_arm: FALSE
supported_minimum_version:
    version_number:
    release_date:


optional_info:
    homepage_url: https://github.com/mikolmogorov/Flye
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content:
        partner_content:
        official_docs: https://github.com/mikolmogorov/Flye/blob/flye/docs/INSTALL.md
    arm_recommended_minimum_version:
        version_number:
        release_date:

optional_hidden_info:
    release_notes__supported_minimum:
    release_notes__recommended_minimum:
    other_info: Install docs mentions how to install flye for Linux/ARM64, but the build from source fails since there is a [uname check](https://github.com/mikolmogorov/Flye/blob/flye/Makefile#L14) in the Makefile that fails for arm64. There is an open issue ticket available for the same. Kindly find it [here](https://github.com/mikolmogorov/Flye/pull/691).

---
