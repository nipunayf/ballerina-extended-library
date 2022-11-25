# The Ballerina Extended Library

The [Ballerina](https://ballerina.io/) extended library includes useful libraries that are not shipped with core Ballerina 
distribution. When building Ballerina applications these extensions are commonly used. 

*Connectors* take a major part of the extended library. They are useful to call external SaaS applications within Ballerina 
program you write. The connectors we have cover a wide spectrum of SaaS applications from databases to ERP, CRM, CMS and social media platforms. These libraries enable Ballerina application developers to do various application integrations, trigger notifications and automation of solutions. The connectors are deeply integrated with Ballerina language itself so that output of one connector can be transformed easily in the way your next connector needs. They are "Ballerina Stubs" for various APIs out there. 

All connectors and other libraries are made available on [Ballerina Central](https://central.ballerina.io/). 

## Repository Organization

This is the Parent repository of the Ballerina Extended Library and used to report bugs, request new features, start new discussions, view project boards, etc. 

### Connectors
To enable independent releases of each connector, we have made the following repository arrangement. 

1. Independently developed connectors.
     - each connector code is separated into a child repository. Therefore to go through the code, please refer to the relevant child repository. 
2. Open API generated connectors. 
     - We have developed a tool to generate Ballerina connector out of a given Open API specification called [ballerina-openapi](https://github.com/ballerina-platform/ballerina-openapi). The connectors generated out of this tool reside at the repository [ballerinax-openapi-connectors](https://github.com/ballerina-platform/ballerinax-openapi-connectors). Please check in the directory `openapi`. 

All above repositories are owned and maintained by the Ballerina Ecosystem Team who is responsible for governing, ensuring security and quality, doing timely releases, maintaining backward compatibility, etc.

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. To start contributing, read these [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md) for information on how you should go about contributing to our project.

Check the issue tracker for open issues that interest you. We look forward to receiving your contributions.

## Code of Conduct

All contributors are encouraged to read the [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## License

Ballerina code is distributed under [Apache license 2.0](https://github.com/ballerina-platform/ballerina-lang/blob/master/LICENSE).

## Useful links

* Chat live with us on our [Discord server](https://discord.gg/ballerinalang).
* Technical questions should be posted on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
* Ballerina performance test results are available [here](performance/benchmarks/summary.md).

## Status Dashboard

### Connectors

|Connector| Latest Version | Build | Bugs | Open Pull Requests |
|:---:|:---:|:---:|:---:|:---:|
[GitHub](https://github.com/ballerina-platform/module-ballerinax-github) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-github.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-github/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-github/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-github/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgithub&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgithub) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-github.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-github/pulls)
[Twilio](https://github.com/ballerina-platform/module-ballerinax-twilio) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-twilio.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-twilio/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-twilio/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-twilio/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Ftwilio&label=&color=yellow&logo=github)](https://github.com/ballerina-platform/ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Ftwilio) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-twilio.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-twilio/pulls)
[GSheet](https://github.com/ballerina-platform/module-ballerinax-googleapis.sheets) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-googleapis.sheets.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.sheets/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-googleapis.sheets/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-googleapis.sheets/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgsheet&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgsheet) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-googleapis.sheets.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.sheets/pulls)
[Gmail](https://github.com/ballerina-platform/module-ballerinax-googleapis.gmail) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-googleapis.gmail.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.gmail/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-googleapis.gmail/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-googleapis.gmail/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgmail&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgmail) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-googleapis.gmail.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.gmail/pulls)
[Slack](https://github.com/ballerina-platform/module-ballerinax-slack) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-slack.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-slack/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-slack/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-slack/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fslack&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fslack) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-slack.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-slack/pulls)
[Google Calendar](https://github.com/ballerina-platform/module-ballerinax-googleapis.calendar) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-googleapis.calendar.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.calendar/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-googleapis.calendar/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-googleapis.calendar/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgcalendar&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgcalendar) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-googleapis.calendar.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.calendar/pulls)
[Salesforce](https://github.com/ballerina-platform/module-ballerinax-sfdc) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-sfdc.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-sfdc/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-sfdc/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-sfdc/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fsalesforce&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fsalesforce) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-sfdc.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-sfdc/pulls)
[Netsuite](https://github.com/ballerina-platform/module-ballerinax-netsuite) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-netsuite.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-netsuite/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-netsuite/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-netsuite/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fnetsuite&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fnetsuite) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-netsuite.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-netsuite/pulls)
[Google Drive](https://github.com/ballerina-platform/module-ballerinax-googleapis.drive) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-googleapis.drive.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.drive/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-googleapis.drive/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-googleapis.drive/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgdrive&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgdrive) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-googleapis.drive.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.drive/pulls)
[Azure EventHub](https://github.com/ballerina-platform/module-ballerinax-azure.eventhub) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-azure.eventhub.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure.eventhub/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-azure.eventhub/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-azure.eventhub/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fazure-eventhub&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fazure-eventhub) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-azure.eventhub.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure.eventhub/pulls)
[CosmosDB](https://github.com/ballerina-platform/module-ballerinax-azure-cosmosdb) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-azure-cosmosdb.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure-cosmosdb/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-azure-cosmosdb/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-azure-cosmosdb/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fcosmosdb&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fcosmosdb) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-azure-cosmosdb.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure-cosmosdb/pulls)
[Azure Service Bus](https://github.com/ballerina-platform/module-ballerinax-azure-service-bus) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-azure-service-bus.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure-service-bus/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-azure-service-bus/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-azure-service-bus/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fazure-servicebus&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fazure-servicebus) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-azure-service-bus.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure-service-bus/pulls)
[Azure Storage Service](https://github.com/ballerina-platform/module-ballerinax-azure-storage-service) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-azure-storage-service.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure-storage-service/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-azure-storage-service/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-azure-storage-service/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fazure-storageservice&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fazure-storageservice) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-azure-storage-service.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure-storage-service/pulls)
[MongoDB](https://github.com/ballerina-platform/module-ballerinax-mongodb) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-mongodb.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-mongodb/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-mongodb/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-mongodb/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmongodb&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmongodb) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-mongodb.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-mongodb/pulls)
[Redis](https://github.com/ballerina-platform/module-ballerinax-redis) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-redis.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-redis/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-redis/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-redis/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fredis&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fredis) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-redis.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-redis/pulls)
[AWS S3](https://github.com/ballerina-platform/module-ballerinax-aws.s3) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-aws.s3.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.s3/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-aws.s3/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-aws.s3/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Faws-s3&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Faws-s3) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-aws.s3.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.s3/pulls)
[AWS SQS](https://github.com/ballerina-platform/module-ballerinax-aws.sqs) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-aws.sqs.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.sqs/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-aws.sqs/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-aws.sqs/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Faws-sqs&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Faws-sqs) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-aws.sqs.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.sqs/pulls)
[Google People API](https://github.com/ballerina-platform/module-ballerinax-googleapis.people) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-googleapis.people.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.people/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-googleapis.people/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-googleapis.people/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgoogle-peopleapi&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fgoogle-peopleapi) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-googleapis.people.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-googleapis.people/pulls)
[MS OneDrive](https://github.com/ballerina-platform/module-ballerinax-microsoft.onedrive) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-microsoft.onedrive.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.onedrive/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-microsoft.onedrive/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-microsoft.onedrive/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmicrosoft-onedrive&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmicrosoft-onedrive) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-microsoft.onedrive.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.onedrive/pulls)
[MS Excel](https://github.com/ballerina-platform/module-ballerinax-microsoft.sheets) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-microsoft.sheets.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.sheets/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-microsoft.sheets/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-microsoft.sheets/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmicrosoft-excel&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmicrosoft-excel) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-microsoft.sheets.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.sheets/pulls)
[Twitter](https://github.com/ballerina-platform/module-ballerinax-twitter) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-twitter.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-twitter/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-twitter/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-twitter/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Ftwitter&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Ftwitter) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-twitter.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-twitter/pulls)
[MS Teams](https://github.com/ballerina-platform/module-ballerinax-microsoft.teams) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-microsoft.teams.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.teams/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-microsoft.teams/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-microsoft.teams/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmicrosoft-teams&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmicrosoft-teams) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-microsoft.teams.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.teams/pulls)
[Azure AD](https://github.com/ballerina-platform/module-ballerinax-azure.ad) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-azure.ad.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure.ad/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-azure.ad/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-azure.ad/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fazure-ad&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fazure-ad) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-azure.ad.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-azure.ad/pulls)
[Outlook Calendar](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.calendar) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-microsoft.outlook.calendar.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.calendar/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.calendar/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.calendar/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Foutlook-calendar&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Foutlook-calendar) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-microsoft.outlook.calendar.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.calendar/pulls)
[Outlook Mail](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.mail) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-microsoft.outlook.mail.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.mail/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.mail/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.mail/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Foutlook-mail&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Foutlook-mail) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-microsoft.outlook.mail.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.outlook.mail/pulls)
[MS OneNote](https://github.com/ballerina-platform/module-ballerinax-microsoft.onenote) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-microsoft.onenote.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.onenote/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-microsoft.onenote/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-microsoft.onenote/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmicrosoft-onenote&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmicrosoft-onenote) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-microsoft.onenote.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-microsoft.onenote/pulls)
[SnowFlake Driver](https://github.com/ballerina-platform/module-ballerinax-snowflake.driver) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-snowflake.driver.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-snowflake.driver/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-snowflake.driver/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-snowflake.driver/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fsnowflake&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fsnowflake) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-snowflake.driver.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-snowflake.driver/pulls)
[AWS SES](https://github.com/ballerina-platform/module-ballerinax-aws.ses) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-aws.ses.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.ses/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-aws.ses/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-aws.ses/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Faws-ses&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Faws-ses) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-aws.ses.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.ses/pulls)
[AWS-SNS](https://github.com/ballerina-platform/module-ballerinax-aws.sns) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-aws.sns.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.sns/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-aws.sns/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-aws.sns/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Faws-sns&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Faws-sns) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-aws.sns.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.sns/pulls)
[AWS-DynamoDB](https://github.com/ballerina-platform/module-ballerinax-aws.dynamodb) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-aws.dynamodb.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.dynamodb/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-aws.dynamodb/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-aws.dynamodb/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmodule/aws-dynamodb&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmodule/aws-dynamodb) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-aws.dynamodb.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.dynamodb/pulls)
[AWS-SimpleDB](https://github.com/ballerina-platform/module-ballerinax-aws.simpledb) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-aws.simpledb.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.simpledb/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-aws.simpledb/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-aws.simpledb/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmodule/aws-simpledb&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmodule/aws-simpledb) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-aws.simpledb.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-aws.simpledb/pulls)
[PeopleHR](https://github.com/ballerina-platform/module-ballerinax-peoplehr) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/module-ballerinax-peoplehr.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-peoplehr/releases) | [![Build](https://github.com/ballerina-platform/module-ballerinax-peoplehr/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerinax-peoplehr/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmodule/peoplehr&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Amodule%2Fmodule/peoplehr) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/module-ballerinax-peoplehr.svg?label=)](https://github.com/ballerina-platform/module-ballerinax-peoplehr/pulls)



**Generated Connectors**

|Type| Latest Version | Build | Bugs | Open Pull Requests |
|:---:|:---:|:---:|:---:|:---:|
[Open API Connectors](https://github.com/ballerina-platform/ballerinax-openapi-connectors) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/ballerinax-openapi-connectors.svg?label=)](https://github.com/ballerina-platform/ballerinax-openapi-connectors/releases) | [![Build](https://github.com/ballerina-platform/ballerinax-openapi-connectors/actions/workflows/daily-build.yml/badge.svg)](https://github.com/ballerina-platform/ballerinax-openapi-connectors/actions/workflows/daily-build.yml) | [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Aconnectors%2Fopenapi&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Aconnectors%2Fopenapi) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/ballerinax-openapi-connectors.svg?label=)](https://github.com/ballerina-platform/ballerinax-openapi-connectors/pulls)

**Connector Generator Tools**

|Tool Name| Latest Version | Bugs | Open Pull Requests |
|:---:|:---:|:---:|:---:|
[Open API](https://github.com/ballerina-platform/ballerina-openapi) | [![GitHub Release](https://img.shields.io/github/release/ballerina-platform/ballerina-openapi.svg?label=)](https://github.com/ballerina-platform/ballerina-openapi/releases)| [![Bugs](https://img.shields.io/github/issues-search/ballerina-platform/ballerina-extended-library?query=is%3Aopen+label%3AType%2FBug+label%3Atools%2Fopenapi&label=&color=yellow&logo=github)](https://github.com/ballerina-platform//ballerina-extended-library/issues?q=is%3Aopen+label%3AType%2FBug+label%3Atools%2Fopenapi) | [![GitHub pull-requests](https://img.shields.io/github/issues-pr/ballerina-platform/ballerina-openapi.svg?label=)](https://github.com/ballerina-platform/ballerina-openapi/pulls)