# ETHTPS

*Without getting into too much detail, there was code involved...*

## Disclaimer

##### Please note that this document is a work in progress and the information provided here is subject to change, in addition to the fact that trying to follow these instructions will be a complete waste of your time *unless* you have access to the private repos.

## Environment setup instructions

### Prerequisites

Before starting, make sure you have the following installed:

#### Mandatory

- git

- [nvm](https://github.com/nvm-sh/nvm)

- [dotnet SDK - latest RC](https://dotnet.microsoft.com/en-us/download)

- [docker](https://docs.docker.com/install/)

- [docker-compose](https://docs.docker.com/compose/install/)

#### Recommended

- [Visual Studio Code](https://code.visualstudio.com/)

- [Azure Data Studio](https://learn.microsoft.com/en-us/azure-data-studio/) - for working with SQL Server

#### Optional

- [Postman](https://www.getpostman.com/) - for testing APIs

### Setup

There are a *lot* of things that need to configured in order to run ETHTPS. Thankfully, we have a tool for this. Check out [ethtpsctl](https://github.com/ethtps/ethtpsctl).