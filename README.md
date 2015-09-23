# Continuous Integration Comparison

A comparison of various continuous delivery options.

## Table of contents

- [Self Hosted vs Hosted](#self-hosted-vs-hosted)
- [Platforms](#platforms)

## Self Hosted vs Hosted

| Type | Pros          | Cons  |
|------|:-------------|:-------------|
| Self-Hosted |<ul><li>Absolute control over every aspect of build process</li></ul>|<ul><li>Time consuming</li><li>Huge barrier for new projects</li></ul>|
|Hosted | <ul><li>No maintenance</li><li>Minimal setup for new projects</li><li>Easy integrations</li><li>Build badges</li></ul> | <ul><li>Cost</li></ul> |

<b>TL;DR</b> Hosted saves us time. Self-hosted gives us flexability.


## Platforms

All of these have the minimum requirements needed for a CI server:
- headless browser support
- deployment pipelines
- github and bitbucket integration


| Name | Pros | Cons | Price |
|------|:-------------|:-----------|:-----:|
|[Codeship](https://codeship.com/) | <ul><li>BitBucket support</li><li>Dependency caching</li><li>Parallel test running</li><li>Debug builds via ssh</li></ul> | <ul><li>UI is complicated</li></ul> | $199/month |
|[Travis CI](https://travis-ci.org/) | <ul><li>Dependency caching</li><li>Simple/Easy UI</li><li>Tests/Deployment in single file</li><li>Concurrent builds</li><li>Secrets encryption</li></ul> | <ul><li>No bitbucket support</li><li>No parallel tests</li></ul> | $250/month |
|[Jenkins](https://jenkins-ci.org/) | <ul><li>Free</li><li>Lots of plugins</li><li>Highly customizable</li></ul> | <ul><li>Hard to debug</li><li>Have to manage server</li><li>Outdated tech</li><li>Not congruent with devops practices</li><li>Outdated interface</li></ul> | Free |
|[Robot Sweatshop](https://github.com/JScott/robot_sweatshop) | <ul><li>Test on every environment</li></ul> | <ul><li>Time sink</li><li>No community support</li></ul> | Free |
|[Go CD](http://www.go.cd/) | <ul><li>Free</li><li>Very flexible w/ environments</li><li>[Fan-in/fan-out dependency management](http://support.thoughtworks.com/entries/22229668-Go-s-Dependency-Management)</li></ul> | | Free |
|[Circle CI](https://circleci.com/) | <ul><li>SSH debugging</li><li>Automatic parallelization</li><li>[Fast test magic](https://circleci.com/docs/what-happens)</li></ul> | <ul><li>Very Expensive</li></ul> | $269/mo for 6 containers |
|[Drone](https://drone.io/) | <ul><li>Ideal platform for Docker integration</li></ul> | | $50/month |

