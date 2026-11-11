# AI-Powered Ethical Hacking Automation with Shell-GPT

## Overview

This internship lab project explored Shell-GPT as a command-line AI assistant to support a practical ethical-hacking workflow in a controlled lab environment. The documented workflow covered reconnaissance, vulnerability scanning, web content discovery, authentication testing, SQL injection, payload generation, and Bash automation.

## Objectives

- Explore AI-assisted command generation in a Linux terminal.
- Practise reconnaissance and service discovery in a lab.
- Understand vulnerability-scanning and web-content-discovery workflows.
- Study authentication testing and SQL injection using intentionally vulnerable lab systems.
- Explore Bash scripting for subdomain-enumeration workflow automation.

## Lab environment

The source documentation describes a Linux environment and lab exercises using Metasploitable 2 and DVWA.

## Activities documented

### 1. Shell-GPT setup
Configured Shell-GPT with Python 3 and an API key, then explored terminal assistance and command-generation modes.

### 2. Reconnaissance and service discovery
Used AI-assisted prompts to explore Nmap host discovery, port scanning, service identification, and selected NSE script categories.

### 3. Vulnerability assessment
Explored Nikto and Nmap vulnerability-related scripts to understand how scanners identify potentially exposed services and weaknesses.

### 4. Web content discovery and fuzzing
Reviewed SecLists and used Gobuster and Feroxbuster to understand directory discovery, fuzzing, recursive scanning, and HTTP response filtering.

### 5. Authentication testing
Practised Hydra workflows using lab services and DVWA. These exercises illustrated the risks of weak credentials and insufficient login protections.

### 6. SQL injection testing
Used SQLMap against DVWA in a deliberately vulnerable local application to understand SQL injection detection and database-enumeration concepts.

### 7. Payload generation
Explored Windows and Android payload-generation concepts using MSFvenom and Metasploit in the lab environment.

### 8. Bash automation
Explored an AI-assisted Bash script concept for checking and invoking subdomain-enumeration tools such as Subfinder, Amass, Assetfinder, Findomain, and dnsenum.

## Tools and technologies

- Shell-GPT
- Python 3 and Linux shell
- Nmap and NSE
- Nikto
- SecLists
- Gobuster
- Feroxbuster
- Hydra
- DVWA
- SQLMap
- Metasploit Framework and MSFvenom
- Bash

## Learning outcomes

- Understood stages of a basic ethical-hacking workflow.
- Used AI assistance to draft and understand shell commands.
- Developed familiarity with automated scanning and web content discovery.
- Explored authentication-testing and web-application security concepts in intentionally vulnerable labs.
- Recognised that AI-generated commands require human review and validation.

## Lab scope and responsible use

The activities described are lab exercises using Metasploitable 2 and DVWA. Testing outside the controlled lab must be performed only on systems owned by the tester or covered by explicit written authorisation.

## Public PDF version

The full 27-page version is retained. All instructional wording, explanations, commands, figures, screenshots, and sections are preserved. Only exposed credential values are masked: the API-key values shown in setup screenshots and PHP session-cookie values shown in DVWA examples. No page or instructional section has been omitted from the full-length public copy.
