# appengine/guestbook-objectify

<a href="https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/java-docs-samples&page=editor&open_in_editor=appengine-java8/guestbook-objectify/README.md">
<img alt="Open in Cloud Shell" src ="http://gstatic.com/cloudssh/images/open-btn.png"></a>

An App Engine guestbook using Java, Maven, and Objectify.

Data access using [Objectify](https://github.com/objectify/objectify)

Please ask questions on [Stackoverflow](http://stackoverflow.com/questions/tagged/google-app-engine)

## Running Locally

How do I, as a developer, start working on the project?

1. `mvn clean appengine:devserver`

## Deploying

1. `mvn clean appengine:update -Dappengine.appId=PROJECT -Dappengine.version=VERSION`
