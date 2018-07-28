# StormBit NG

### Contents

1. (Contents)[#contents]
2. (Why?)[#why]
3. (Components)[#ccomponents]

### Why?

The purpose of this project is to try and answer the question: "What does a minimum-viable scalable IRC network look like?"

### Components

 - [svc-registry]() - A minimal service registry designed to distribute updates, track overall health and perform basic self-healing actions.
 - [ircd-svc-sidekick]() - An application designed to run alongside a given IRCd, to register and subscribe it within an instance of `ircd-svc-registry`.
 - [ircd-healthcheck]() - A CLI utility and library built by StormBit in Golang to monitor the connectivity of an IRCd.

