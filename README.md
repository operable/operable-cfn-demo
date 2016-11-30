# Operable CloudFormation Demo

Cog's `cfn` bundle allows you to interact with AWS CloudFormation from chat
while continuing to embrace best practices around security and version control.
Rather than maintaining its own database or relying on AWS metadata as the
source of truth, your resource configuration is stored in a standard Git
repository.

You can use the same tools and workflow that you normally would to manage
the content of the repository. In addition, you can also work with many of the
resources directly from Cog -- with those changes reflected in the repository.

This repository contains a sample data set that was used when constructing a
screencast exploring the features of the `cfn` bundle.

## Directory Structure

```
.
├── README.md
├── defaults
├── definitions
└── templates

3 directories, 1 file
```
