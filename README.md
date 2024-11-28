# Azure Functions in Rust using Axum with CI/CD

Azure Function with custom handler invoking a binary compiled from code written in Rust with the Axum framework.
This axum project is built and deployed automatically on repository pushes with GitHub Actions Workflows.
Azure resources are provisioned with Terraform.

## Requirements

* x86-64
* Linux/Unix
* [Rust](https://www.rust-lang.org/tools/install)

