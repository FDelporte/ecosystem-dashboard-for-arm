---
name: Postgres
category: Database
description: PostgreSQL is an advanced, enterprise class open-source relational database that supports both SQL (relational) and JSON (non-relational) querying.
download_url: https://www.postgresql.org/ftp/source/
works_on_arm: true
supported_minimum_version:
    version_number: 9.6.9
    release_date: 2018/05/07


optional_info:
    homepage_url: https://www.postgresql.org/
    support_caveats: 
    alternative_options: 
    getting_started_resources: 
        arm_content: https://learn.arm.com/learning-paths/servers-and-cloud-computing/postgresql/install_postgresql/
        partner_content:  https://www.percona.com/blog/postgresql-on-arm-based-aws-ec2-instances-is-it-any-good/
        official_docs: https://www.postgresql.org/docs/
    arm_recommended_minimum_version:
        version_number: 
        release_date:
        reference_content:
        rationale:


optional_hidden_info:
    release_notes__supported_minimum:
    release_notes__recommended_minimum:
    other_info: No arm64 specific release notes are present. Installation and testing was done through tar file. Version 10.0 fails to build, whereas version >=11 builds successfully. We can also build the previous versions by using the --disable-spinlock flag(not recommended) while configuring.
---
