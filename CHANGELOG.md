# Changelog

All notable changes compare to upstream will be documented in this file.

## [2.1.0-nordix1] - 2024-04-03

This release is based on https://github.com/ninenines/gun/releases/tag/2.1.0
with the following PRs included:

- "Use GOAWAY reason NO_ERROR in client-initiated graceful shutdown"
  https://github.com/ninenines/gun/pull/312

- "Add state (current state name) info field in gun:info/1"
  https://github.com/ninenines/gun/pull/293

- "Respect remote concurrency limit."
  https://github.com/ninenines/gun/pull/280

  which depends on https://github.com/ninenines/cowlib/pull/123
  included in https://github.com/Nordix/cowlib/releases/tag/2.13.0-nordix1
