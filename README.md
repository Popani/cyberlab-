CyberLab — Personal Cybersecurity Training & Vulnerability Lab
Overview

CyberLab is a personal cybersecurity learning environment built to develop practical skills in Linux, web application security, vulnerability discovery, security testing, and system hardening.

The project is being developed in a controlled local environment using Termux on Android. The goal is to build intentionally vulnerable applications, test them safely, document the findings, and progressively improve their security.

Project status: In Progress

Current Environment
Termux
Linux command-line environment
Python
Git
GitHub
HTML
Local Python web server
Project Structure
cyberlab/

├── .gitignore
├── README.md
├── permission-lab/
│   └── test.txt
└── vulnalab/
    └── web/
        └── index.html
		
Completed Work
Linux & File Permissions

The project includes practical exercises involving:

Linux directory navigation
File and directory creation
File permissions
Ownership and permission inspection
Understanding executable, readable, and writable permissions
Basic command-line administration
Git & Version Control

Git has been configured for the CyberLab project.

The repository uses:

main as the primary branch
.gitignore to prevent unnecessary or sensitive files from being tracked
Git commits to document project progress
GitHub as the remote repository
VulnLab

VulnLab is an intentionally vulnerable local web application created for cybersecurity training.

The current application contains an Upload Portal designed to become part of the security-testing environment.

The initial interface includes a multipart file-upload form that submits to:

/upload

The application is currently being developed. The upload backend and security-testing functionality have not yet been implemented.

Security Testing Approach

As development continues, VulnLab will be used to study vulnerabilities in a controlled environment.

The general workflow will be:

Build a vulnerable component.
Understand how the component works.
Identify the security weakness.
Test the weakness against the local lab.
Document the findings.
Apply a security fix.
Test the fix.
Record the lessons learned.

All testing is intended for systems owned or explicitly authorized for testing.

Planned Development

Future work may include:

Implementing the upload backend
Input validation
File-type validation
Secure file handling
Authentication and authorization exercises
Logging and monitoring
Vulnerability testing
Security remediation
Documentation of findings
GitHub project documentation
Additional intentionally vulnerable components
Learning Objectives

This project is being used to develop practical understanding of:

Linux
Git and version control
Web applications
HTTP requests
File uploads
Authentication and authorization
Input validation
Vulnerability discovery
Secure coding
Vulnerability remediation
Security documentation
Disclaimer

CyberLab is an intentionally vulnerable training environment created for educational purposes.

Security testing should only be performed against systems that are personally owned or where explicit authorization has been provided.

Project Status

Current stage: Initial repository and VulnLab setup

The project is actively being developed and additional functionality will be added as the lab progresses.

						
