# 0x0C. Web Server

Welcome to the 0x0C. Web Server project! This project is part of the ALX School curriculum for DevOps and SysAdmin roles. It emphasizes the automation of web server configuration using Bash scripting, without any human intervention.

## Project Overview

This repository contains scripts that automatically configure an Ubuntu 16.04 machine to meet specific web server requirements using Nginx. The tasks are designed to teach how to automate manual configuration processes, a valuable skill for Software Reliability Engineers (SREs) managing large-scale server deployments.

## Learning Objectives

By the end of this project, learners should be able to explain, without external resources:
- The main role and function of a web server.
- What a child process is, and the relationship between parent and child processes in web servers.
- Key DNS record types: A, CNAME, TXT, MX.
- The essential HTTP requests types and their purposes.

## Requirements

- **Environment**: Scripts will be tested on Ubuntu 16.04 LTS.
- **Editing**: Use vi, vim, or emacs as text editors.
- **Scripting**:
  - All scripts should start with `#!/usr/bin/env bash`.
  - The second line must be a comment explaining the script's function.
  - Scripts must pass checks by Shellcheck (version 0.3.7) without errors.
  - Scripts should not use `systemctl` for restarting processes.

## Project Tasks

1. **File Transfer**: Create a script to transfer files from a client to the server using SCP.
2. **Nginx Installation**: Write a script to install Nginx and configure it to serve a "Hello World" HTML page.
3. **Domain Setup**: Document the process of setting up a `.tech` domain and point it to your server.
4. **Redirection**: Automate the setup of a 301 redirect in Nginx.
5. **Custom 404 Page**: Configure Nginx to display a custom 404 Not Found page.

## Testing

To ensure that your scripts function correctly:
- Start an Ubuntu 16.04 sandbox.
- Execute your script to see if it meets the project requirements.
- Use `curl` to test HTTP responses from Nginx.

## Resources

- [How the Web Works](#)
- [Understanding Nginx Configuration](#)
- [HTTP Redirection](#)
- [RFC 7231 - HTTP/1.1](https://tools.ietf.org/html/rfc7231)
- [RFC 7540 - HTTP/2](https://tools.ietf.org/html/rfc7540)

## Quiz Answers

### Question #0: A DNS A record translates to
- an IP

### Question #1: The main role of DNS is to
- translate domain name into IP address

### Question #2: The main role of a web server is to
- serve static content

### Question #3: What is TTL within the context of DNS
- a time period when DNS query results are cached

### Question #4: A HTTP POST request is to
- submit data

### Question #5: A HTTP GET request is to
- request data

### Question #6: Why do web servers usually use child processes?
- So that the web server can dynamically change the number of child process to accommodate the volume of requests to be processed

### Question #7: A web server is
- a software

### Question #8: A DNS CNAME record translates to
- a domain

### Question #9: What was one of the most important reasons for which DNS was created?
- because humans are not good at remembering long sequences of numbers (IP address)


May your deployment be smooth and your server loads light!

