*Without getting into too much detail, there was code involved...*

## Hello there!

Welcome to ETHTPS. This is the place for the second version of ethtps.info, a website that provides information about Ethereum network's the number of transactions per second and their complexity.

The website is currently under construction and a public alpha will follow soon. The first version of the website can be found [here](https://ethtps.info/).

You can check out our public repos [here](https://github.com/orgs/ethtps/repositories). Here are some quick links to the most important ones:

- [backend](https://github.com/ethtps/ethtps.backend) (API)

## Disclaimer

##### ⚠️ Please note that this document is a work in progress and the information provided here is subject to change, in addition to the fact that trying to follow these instructions will be a complete waste of your time *unless* you have access to the private repos.

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