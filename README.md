# Continuous Integration Comparison

A comparison of various continuous delivery options.

## Table of contents

- [Self Hosted vs Hosted](#self-hosted-vs-hosted)
- [Platform Options](#platform-options)
- [Platform Reviews](#platform-reviews)


## Self Hosted vs Hosted

| Type | Pros          | Cons  |
|------|:-------------|:-------------|
| Self-Hosted |<ul><li>Absolute control over every aspect of build process</li></ul>|<ul><li>Time consuming</li><li>Huge barrier for new projects</li></ul>|
|Hosted | <ul><li>No maintenance</li><li>Minimal setup for new projects</li><li>Easy integrations</li></ul> | <ul><li>Cost</li></ul> |

<b>TL;DR</b> Hosted saves us time. Self-hosted gives us flexability.


## Platform Options

All of these meet minimum requirements:
- headless browser support
- deployment pipeline support
- github and bitbucket integration
- flexible scripting
- build badges
- parallel tests



| Name | Hosting |  Pros | Cons | Price |
|------|:----------:|:-------------|:-----------|:-----:|
|[Codeship](https://codeship.com/) | Hosted |<ul><li>BitBucket support</li><li>Dependency caching</li><li>Parallel test running</li><li>Debug builds via ssh</li></ul> |  | $199/month |
|[Jenkins](https://jenkins-ci.org/) | Self |<ul><li>Free</li><li>Lots of plugins</li><li>Highly customizable</li></ul> | <ul><li>Hard to debug</li><li>Have to manage server</li><li>Outdated tech</li><li>Not congruent with devops practices</li><li>Outdated interface</li></ul> | Free |
|[Go CD](http://www.go.cd/) | Self |<ul><li>Free</li><li>Very flexible w/ environments</li><li>[Fan-in/fan-out dependency management](http://support.thoughtworks.com/entries/22229668-Go-s-Dependency-Management)</li></ul> | | Free |
|[Travis CI](https://travis-ci.org/) | Both | <ul><li>Dependency caching</li><li>Simple/Easy UI</li><li>Tests/Deployment in single file</li><li>Concurrent builds</li><li>Secrets encryption</li></ul> | <ul><li>No bitbucket support</li><li>No parallel tests</li></ul> | $250/month |
|[Robot Sweatshop](https://github.com/JScott/robot_sweatshop) | Self |<ul><li>Test on every environment</li></ul> | <ul><li>Time sink</li><li>No community support</li></ul> | Free |
|[Circle CI](https://circleci.com/) | Hosted |<ul><li>SSH debugging</li><li>Automatic parallelization</li><li>[Fast test magic](https://circleci.com/docs/what-happens)</li></ul> | <ul><li>Very Expensive with scale</li><li><b>No bitbucket support</b></li></ul> | $269/mo for 6 containers |
|[Drone](https://drone.io/) | Both | <ul><li>Built on docker containers</li><li>Easy self hosting</li><li>Inexpensive</li></ul> | <ul><li>Limited feature set</li></ul>  | $50/month |
|[Solano CI](https://www.solanolabs.com/) | Both | <ul><li>SSH Debug</li><li>Parallel builds</li></ul> |  | $125/month |


## Platform Reviews

### Codeship

| Reviewer | Review |  Liked | Didn't Like |
|------|:----------:|:-------------|:-----------|:-----:|
| Patrick Zhang |  | <ul><li></li></ul> | <ul><li></li></ul> |


### Travis

| Reviewer | Review |  Liked | Didn't Like |
|------|:----------:|:-------------|:-----------|:-----:|
| Name |  |  | |

### Jenkins

| Reviewer | Review |  Liked | Didn't Like |
|------|:----------:|:-------------|:-----------|:-----:|
| Name |  |  | |

### GoCD

| Reviewer | Review |  Liked | Didn't Like |
|------|:----------:|:-------------|:-----------|:-----:|
| Name |  |  | |
