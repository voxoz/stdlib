BASE: Erlang Base Library
=========================

[![Actions Status](https://github.com/voxoz/base/workflows/mix/badge.svg)](https://github.com/voxoz/base/actions)
[![Hex pm](http://img.shields.io/hexpm/v/base.svg?style=flat)](https://hex.pm/packages/base)

Features
--------

* Erlang kernel replacement (not fully compatible)
* Simple and clean design
* Remoting protocol implementation
* Mnesia implementation
* Application, Supervisor and Server

Idea
----

The idea is to have refreshed legacy kernel and stdlib applications,
which serve us good, but have some drawbacks:

* Old-fashioned design
* Buggy and messy codebase, that nobody wants to touch
* Sometimes bugs in gen_server appeared in OTP releases
* Mnesia limitations
* Remote protocol limitations

