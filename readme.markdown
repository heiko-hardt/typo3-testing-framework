# TYPO3-testing-framework

This framework is designed for:
- Collecting tools and frameworks depending on TYPO3 version
- Dynamic test instances (forwarded to default typo3-testing-framework)
- Static test instances (Bootstraping test instance in a predefined directory and database)

This framework (uhm wrapper) was mainly written for local testings.
I really like the original testing-framework (since TYPO3 v.6) and thanks a lot to all contributors.

## Why writing yet-another-testing-framework?
Currently, functional- and acceptance- test are done in a temporary directory (dynamic).
Seperated by an instance-name a bunch of test-instances are published in multiple subdirectories and databases.
For ci-server this may be the best choice. \
For local testings I prefer a single directory/database instance (static).
This framework should give me the choice ... dynamic (like default) or static (uncontrollable magic)

## versioning/tagging
- TYPO3 6.2 LTS => 1.x.x
- TYPO3 7.6 LTS => 2.x.x
- TYPO3 8.7 LTS => 3.x.x
- TYPO3 9.5 LTS => 4.x.x
- TYPO3 10.4 LTS => 5.x.x
