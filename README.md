Cyber-Training-Pipeline
Project BLUF

This repository documents the end-to-end development of a personal cybersecurity training lab, from initial workstation configuration through infrastructure deployment and ongoing maintenance.

The goal is to provide a repeatable, documented build process that allows the environment to be reconstructed from the ground up by following the procedures and configurations maintained in this repository. Documentation is written with the assumption that the operator may need to reproduce the environment without relying on undocumented steps or prior knowledge.

Environment Prerequisites

Before beginning the procedures documented in this repository, the host workstation should have the following tools configured:

Visual Studio Code (VS Code) with the Markdown All in One extension
Git command-line tools
SSH key pair configured for GitHub authentication
GitHub account with access to this repository
Any additional software, utilities, or dependencies introduced during later phases of the project

Installation and configuration procedures for project-specific tools are documented in 00_Docs_and_Tools/.

Repository Structure

The project is organized into numbered modules to provide a logical progression from documentation and tooling through local environment configuration and future infrastructure development.

00_Docs_and_Tools/

Contains reference documentation, setup guides, configuration procedures, and notes for tools used throughout the project.

Examples include:

SSH key generation and GitHub authentication
Git configuration and workflow
VS Code configuration
Markdown documentation standards
Troubleshooting procedures
Other tools and references introduced during project development
01_Local_Environment/

Contains documentation, configuration files, scripts, and procedures related to building and maintaining the local workstation and cybersecurity lab environment.

Additional modules will be added as the project progresses.

Documentation Philosophy

This project follows a document-as-you-build approach. Procedures, configurations, lessons learned, and troubleshooting steps should be recorded as the environment develops rather than reconstructed afterward.

The objective is to maintain enough documentation that a future operator — including a future version of myself — can understand what was done, why it was done, and how to reproduce it without relying on undocumented knowledge.

