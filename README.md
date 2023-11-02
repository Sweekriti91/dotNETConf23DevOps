# dotNETConf23DevOps

Resources for the .NET Conf Talk Build .NET MAUI Apps with DevOps

## DevOps Pipelines from Demo 

- Build a .NET Maui Class Lib
    - [GitHub Actions Pipeline](MauiClassLibDevOps/GitHubActions/main.yml)
    - [Azure DevOps Pipeline](MauiClassLibDevOps/AzureDevOps/build.yml)

- Build a .NET MAUI App and .NET MAUI Blazor App
    - GitHub Actions Pipeline
        - [Mac Hosted Agent](MauiAppDevOps/GitHubActions/build_mac.yml)
        - [Windows Hosted Agent](MauiAppDevOps/GitHubActions/build_windows.yml)

    - Azure DevOps Pipeline
        - [Mac Hosted Agent](MauiAppDevOps/AzureDevOps/build_mac.yml)
        - [Windows Hosted Agent](MauiAppDevOps/AzureDevOps/build_windows.yml)


## Useful Links 

- [Getting Started with DevOps and .NET MAUI](https://devblogs.microsoft.com/dotnet/devops-for-dotnet-maui/)
- [GitHub Actions Task Test Reporter](https://github.com/marketplace/actions/test-reporter)
- [Azure DevOps Task Publish Test Results](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/publish-test-results-v2?view=azure-pipelines&tabs=trx%2Ctrxattachments%2Cyaml)
- [Azure DevOps Task Publish Code Coverage](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/publish-code-coverage-results-v1?view=azure-pipelines)
- [Using FastLane with GitHub Actions](https://docs.fastlane.tools/best-practices/continuous-integration/github/)
- [Azure DevOps Publish to Google Play](https://marketplace.visualstudio.com/items?itemName=ms-vsclient.google-play)
- [Azure DevOps Publish to Apple App Store](https://marketplace.visualstudio.com/items?itemName=ms-vsclient.app-store)
- [Dotnet nuget Task Documentation](https://learn.microsoft.com/en-us/azure/devops/pipelines/ecosystems/dotnet-core?view=azure-devops&tabs=dotnetfive)
