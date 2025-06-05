# Contributing Note: Security UI

The following are contents for the Developers who want to fire up the Development Environment to contribute on this repository. This is only a UI Repository, so all you need is to fire up the JavaScript environment to start working.

## Pre-requisites

* **NodeJS** v16.15+ &mdash; [<kbd>🛠 Install</kbd>](https://nodejs.org/en/)

## Installation

```bash
git clone git@gitlab.com:technovistaltd/most.gov.bd/idsdp_most/web-ui/securityui.git security-ui \
    && cd security-ui
```

**Note:** If you don't have SSH to the server, you can use the HTTP version of the repository URL

### Without Docker

```bash
npm install \
    && npm start
```

This will install all the listed dependencies and fire up the development environment.

## Setup

```bash
cp src/constants/config.constant.ts.example src/constants/config.constant.ts
```

Now set the several URL values from the development team after knowing their belongings.

## Troubleshooting

Nothing to inform yet.
