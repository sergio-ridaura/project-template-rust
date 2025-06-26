# 🔧 Action Plan v25.6.27

_Copyright (c) 2025. [Sergio Ridaura](https://github.com/sergio-ridaura)._

## Project Template Rust

Base template to quickly and efficiently start Rust projects.

Setting up a [Rust](https://www.rust-lang.org/) project from scratch can be a complex, repetitive, and error-prone task. This initial process consumes valuable time that could be dedicated to developing key functionalities. To address this challenge, we propose a base template that simplifies and optimizes the initial project configuration, promoting good practices from the beginning.

This template is designed to be used with **[Visual Studio Code](https://code.visualstudio.com/)** and integrates seamlessly with **[GitHub](https://github.com/)**, facilitating repository creation and source code management. By adopting this predefined structure, development teams can focus on what really matters: building innovative and high-quality solutions.

## Tasks

The fundamental purpose of this action plan is to provide a robust foundation that streamlines the creation of [Rust](https://www.rust-lang.org/) projects on [GitHub](https://github.com/) using [Visual Studio Code](https://code.visualstudio.com/). It seeks to simplify initial configuration, standardize processes, and foster good practices from project inception. The following tasks are described below:

### GitHub Repository Setup

| Priority | Size | Estimation |
| :------: | :--: | :--------: |
|    P1    |  XS  |     1      |

Set up a GitHub repository to manage version control, based on the [Project Template](https://github.com/sergio-ridaura/project-template) base template.

**Requirements:**

- **Repository Creation:** Create a new GitHub repository based on the [Project Template](https://github.com/sergio-ridaura/project-template) template, selecting the English language. Establish a clear title, precise description, and define appropriate privacy settings.
- **Branch Protection:** Configure the `main` branch to prevent changes without review.
- **Repository Configuration:** Enable `Issues` and, if necessary, configure it as a `Template`

### Base Template Adaptation

| Priority | Size | Estimation |
| :------: | :--: | :--------: |
|    P1    |  L   |     8      |

Starting from the [Project Template](https://github.com/sergio-ridaura/project-template) base template, the purpose is to accelerate and optimize the startup of new software projects.

The goal is to adapt and customize the template to cover the specific requirements of the project, ensuring that all files, configurations, and structures are properly integrated and aligned with development best practices. This will allow teams to focus on implementing key functionalities from the start, reducing errors and improving efficiency.

**Requirements:**

- **Initial Adjustments:** Modify the base template to include necessary files and configurations.

### Rust Dockerfile

| Priority | Size | Estimation |
| :------: | :--: | :--------: |
|    P1    |  S   |     2      |

Create a `Dockerfile` for the Rust project, ensuring that the development environment is consistent and easy to set up. This `Dockerfile` should include necessary dependencies and project-specific configurations.

### Hello World! Rust

| Priority | Size | Estimation |
| :------: | :--: | :--------: |
|    P1    |  S   |     2      |

Create a Rust project that prints "Hello, world!" to the console. This basic exercise will serve as a starting point to verify that the development environment is properly configured and working.

### GitHub Actions CI/CD

| Priority | Size | Estimation |
| :------: | :--: | :--------: |
|    P1    |  M   |     4      |

Configure GitHub Actions to implement a CI/CD workflow that runs tests and automatically deploys the Rust project. This will ensure that code is tested and deployed efficiently and reliably.

### Publish Project to Crates.io

| Priority | Size | Estimation |
| :------: | :--: | :--------: |
|    P1    |  M   |     4      |

Publish the project to [Crates.io](https://crates.io/) to make it available to the Rust community. This will allow other developers to use and contribute to the project, fostering collaboration and community growth.

## Summary

The action plan consists of **6 tasks** with a total estimated effort of **21 points**.
