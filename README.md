# This functionality is now in the core Bot Framework SDK

This functionality has been moved into the core Bot Framework SDK. You should update your Bot Framework SDK to version 4.6 rather than using this SDK.

This SDK will be deprecated, and will not receive further updates.

# Bot Builder Microsoft Teams Extensions

 [![Build status](https://ci.appveyor.com/api/projects/status/504dr2qv99ee2ide/branch/master?svg=true)](https://ci.appveyor.com/project/RamjotSingh/botbuilder-microsoftteams/branch/master)


The Microsoft Bot Builder SDK Teams Extensions allow you to build bots for Microsoft Teams quickly and easily. **[Review the documentation](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/bots/bots-overview)** to get started!

> Note that the Bot Builder Extensions does **NOT** yet work with Bot Framework SDK 4.x. It currently only works with Bot Framework SDK 3.x.

# This SDK allows you to easily...

* Fetch a list of channels in a team
* Fetch profile info about all members of a team
* Fetch tenant-id from an incoming message to bot
* Create 1:1 chat with a specific user
* Mention a specific user
* Consume various events like channel-created, team-renamed, etc.
* Accept messages only from specific tenants
* Write Compose Extensions
* _and more!_

# Installing

If you are building your bot in .NET, simply grab the [Microsoft.Bot.Connector.Teams](https://www.nuget.org/packages/Microsoft.Bot.Connector.Teams) nuget.

If you are using Node, grab the [botbuilder-teams](https://www.npmjs.com/package/botbuilder-teams) NPM instead.

# Get started quickly with our samples:

* Sample bot [C#](https://github.com/OfficeDev/BotBuilder-MicrosoftTeams/tree/master/CSharp/Samples/Microsoft.Bot.Connector.Teams.SampleBot)
* Sample bot [Node](https://github.com/OfficeDev/BotBuilder-MicrosoftTeams/tree/master/Node/samples)

# Questions, bugs, feature requests, and contributions
Please review the information [here](https://docs.microsoft.com/en-us/microsoftteams/platform/feedback).

# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
