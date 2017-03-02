[![CircleCI branch](https://img.shields.io/circleci/project/projectcalico/bird/feature-ipinip.svg?label=bird)](https://circleci.com/gh/projectcalico/bird/tree/feature-ipinip)
[![Docker Pulls](https://img.shields.io/docker/pulls/calico/routereflector.svg)](https://hub.docker.com/r/calico/routereflector/)

[![Slack Status](https://slack.projectcalico.org/badge.svg)](https://slack.projectcalico.org)
[![IRC Channel](https://img.shields.io/badge/irc-%23calico-blue.svg)](https://kiwiirc.com/client/irc.freenode.net/#calico)

# Calico BIRD

This is a fork of the [BIRD internet routing daemon](BIRD-README) which provides
the following additional function used by Calico:

-  Support for routing using IP-in-IP
-  A packaged route reflector available as a Docker container image: [`calico/routereflector`](build_routereflector)

