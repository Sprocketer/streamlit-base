# Streamlit Base

## Intended Use

### Gist

This is a *template repository*, so its intended use is to create other repositories which **build off of this web app template**.

### Use cases

Set up by default with an **authentication system** - this is suited for general websites, but of course also works for data display apps.

## Dependencies

### Pip Packages

All pip requirements are listed in *`requirements.txt`*

**Make sure you upgrade the Streamlit requirement to the version you develop with**

## Authentication

### Authentication Widgets

Uses streamlit-authenticator library for authentication widgets

### Credentials

Credentials are stored in *`config.yaml`*

## Config && Secrets

### Config

Configuration for Streamlit is stored in *`/.streamlit/config.toml`*

### Secrets

Secrets for Streamlit environment are stored in *`/.streamlit/secrets.toml`*

*Warning: Never hardcode secrets - use GitHub secrets*

## Github Actions

### Pylint

Default Pylint Github Action is set up in *`/.github/workflows/pylint.yml`*

## Licensing

### None (ish)

Unlicensed using **`https://unlicense.org/`** - see *`UNLICENSE`* file
