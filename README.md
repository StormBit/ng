# StormBit NG

### Contents

1. [Contents](#contents)
2. [Why?](#why)
3. [API](#api)
4. [Components](#ccomponents)

### Why?

The purpose of this project is to try and answer the question: _"What does a minimum-viable, scalable IRC network look like?"_
As we learn, this living document will evolve.

#### Design Principles

 - **Minimising operational complexity.** We are a globally distributed team of varying talents, and so want to make sure that as much time spent on our network is useful.
 - **Democratising.** We can all make valuable contributions, and so we want to make it as easy to contribute to the platform as possible.
 - **Avoid buying things we don't need.** Some simpler solutions come with a hefty price-tag, whereas our budget is relatively small.
 - **Opening doors.** There is no rush to deliver, so we can spend time improving our options for the future. Our immediate priorities are to remove the complexity and bottlenecks around making changes so we can react quicker.

### API

[API Documentation can be found here](https://ng-docs.stormbit.net/api/)

### Components

 - [svc-registry](https://github.com/StormBit/svc-registry) - A minimal service registry designed to distribute updates, track overall health and perform basic self-healing actions.  Currently this powers the NG API.
 - [ircd-svc-sidekick](https://github.com/StormBit/ircd-svc-sidekick) - An application designed to run alongside a given IRCd, to register and subscribe it within an instance of `ircd-svc-registry`.
 - [ircd-healthcheck](https://github.com/StormBit/ircd-healthcheck) - A CLI utility and library built by StormBit in Golang to monitor the connectivity of an IRCd.

