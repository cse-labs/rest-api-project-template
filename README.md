# REST API Bootstrap Template

This is a template repository for quickly creating REST APIs using .NET Core, altought it can be reused on other languages and technologies the main focus is .NET Core. It provides out-of-the-box ready to use CI/CD, a well-structured repository, best practices, and engineering fundamentals to help customers accelerate their project's start.

## Features

* CI/CD pipeline: The template includes a pre-configured CI/CD pipeline using GitHub Actions. This pipeline automatically build, test and deploys your API on every push to the master branch. It also provide workflows to validate PRs, API contracts and push the images to ACR.
* Repository structure: A well-structured repository makes it easy for you and your team to collaborate and maintain the codebase. The template follows industry-standard practices for project organization.
* Dockerfiles and GitHub Codespaces. It provides container configurations for deploying the app, and also starting working in the project on the cloud by using a pre-configured GitHub Codespace environment.
* Load testing. It provides options to do basic load testing for verification.
* System and integration testing. Provides a configured project to do common system and integration testing. It also provides tools to generate code coverage.
* API Contract. It provides tools and guidance on how to design your API contracts and generate the OpenApi specs. This is based in [Microsoft TypeSpec](https://microsoft.github.io/typespec/).

## Out of scope

This template does not provide any opinion or guidance in:

* Code samples (including controllers, models, etc.)
* API guidelines
* Logging, exception handling, input validation. 
* Code conventions (ex. StyleCop rules).
* Design patterns or code best practices (ex. separation of concerns, dependency injection).
* Unit Testing.


The API sample project is generated using `dotnet new` command without any modification. It provides load testing for a quick verification, but a production-ready project would benefit of other tools like [Apache JMeter](https://jmeter.apache.org/) or [Azure Load Testing](https://learn.microsoft.com/en-us/azure/load-testing/overview-what-is-azure-load-testing) for testing specific scenarios.

If you are interesting in help in the out-of-scope areas we recommend to follow [Azure API guidelines](https://github.com/microsoft/api-guidelines/), KiC samples, and [Microsoft Learn](https://learn.microsoft.com).

## Getting Started

To use this template, click the "Use this template" button at the top of the repository page. This will create a new repository with the same structure and files as this template. From there, you can customize the code and configure the CI/CD pipeline to meet your needs.

## References

* REST APIs have become increasingly popular in recent years due to their simplicity, scalability, and flexibility. According to [API Fortress](https://saucelabs.com/products/api-testing), the global API market is expected to grow from $613.8 million in 2019 to $1.7 billion in 2024.
* A study by [SmartBear](https://smartbear.com/learn/api-design/what-is-an-api-economy/) found that 85% of companies surveyed have an API strategy in place, and 75% of companies believe APIs will play a strategic role in their business growth.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
