# Ansible Execution Environment: Palo Alto Networks

[![N|Solid](https://www.paloaltonetworks.com/content/dam/pan/en_US/images/logos/brand/primary-company-logo/PANW_Parent_Brand_Primary_Logo_RGB.png?imbypass=on)](https://paloaltonetworks.com/)

## Overview

This project aims to bring the ability to interact with Palo Alto Networks platforms through the construct of an Execution Environment.

### 🐍 `Prep your Python environment`

I have included a Poetry file for anyone saavy enough to take advantage. For the uninitiated, Poetry helps replicate Python environments between users with a single file. You'll need to have Poetry installed on your machine, for most users that will be solved with `pip install poetry`.

1. install Python dependencies

```bash
poetry install
```

2. activate environment

```bash
poetry shell
```

## 🐳 `Executing the build`

build the container image with

```bash
ansible-builder build --tag ghcr.io/cdot65/ansible-ee-paloaltonetworks:latest
```
