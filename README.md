# README

This repository is configured with a **Development Container**. You can run this project in the cloud using GitHub Codespaces or locally using Docker.

## Quick Start with GitHub Codespaces

The easiest way to start is to run this project in the cloud:

1. Click the **Code** button at the top of this repository.
2. Select the **Codespaces** tab.
3. Click **Create codespace on main**.
4. Wait for the environment to build (this will automatically install Rust and the necessary VS Code extensions).

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/brnnwon/rust-setup-codespace)


## Local Development

If you prefer to work locally:

1. Ensure you have **Docker Desktop** and **VS Code** installed.
2. Install the **Dev Containers** extension in VS Code.
3. Clone this repository and open the folder in VS Code.
4. When prompted with "Reopen in Container", click **Reopen**.

## Verifying the Setup

Once the terminal opens (inside the container), run the following command to ensure Rust is ready:

```bash
cargo --version
```