---
name: Spark
category: Databases - Big-data
description: Apache Spark is an open-source, distributed processing system used for big data workloads. 
download_url: https://spark.apache.org/downloads.html
works_on_arm: true
supported_minimum_version:
    version_number: 3.0.0
    release_date: 16/06/16


optional_info:
    homepage_url: https://spark.apache.org/
    support_caveats:
    alternative_options:
    getting_started_resources:
        arm_content: https://learn.arm.com/learning-paths/servers-and-cloud-computing/spark/
        partner_content:  https://aws.amazon.com/what-is/apache-spark/
        official_docs: 
    arm_recommended_minimum_version:
        version_number: 
        release_date: 


optional_hidden_info:
    release_notes__supported_minimum: 
    release_notes__recommended_minimum: 
    other_info: ARM64 architecture is not specifically mentioned in the release notes for spark, and the binary for ARM64 is not available either. The only available file is the tar file. Using the tar file, I tested some versions of spark on the ARM64 N1 architecture and found that version 3.0.0 is the minimum version. Take reference from [here](https://github.com/aws/aws-graviton-getting-started/tree/main?tab=readme-ov-file#transitioning-to-graviton) that indicates v3.0+ is supported on ARM64 architecture.

---

