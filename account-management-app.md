# Account Management App

The target audiences of this app are elder friends or somebody that are unable to use or unfamiliar with modern applications that need authentication, also might be the one who is reluctant or lazy to remember any passwords

## System design

This app needs to resolve the following design issues

### QPS?

This app should not concern with this kind of information, as it should not be centralized and used in public network

### What kinds of applications that bothering target audiences most?

1. finance account
2. one-off cloud accounts for learning administrating cloud platform, like GCP, AWS and start-up cloud platform that provide free subscriptions

etc...

### Security

#### How do we make sure account information secured?

1. Use third-party secured storage?
2. Import on-demand account information and only allow user access it within internal network?

etc...

### UX

1. How do we avoid to open and install all kinds of apps?
2. How do we make this app smart enough to know what account is user searching for?, since he may not know the platform which he is looking for

etc...
