# Changelog

All notable changes compare to upstream will be documented in this file.

## 2.1.0-nordix3 (2024-12-19)

This release is based on https://github.com/ninenines/gun/releases/tag/2.1.0
with the following PRs included:

- "Add gun:ping/2,3 for user-initiated ping for HTTP/2"
  https://github.com/ninenines/gun/pull/343

- All PRs included in 2.1.0-nordix2.


## 2.1.0-nordix2 (2024-05-14)

This release is based on https://github.com/ninenines/gun/releases/tag/2.1.0
with the following PRs included:

- "Include event handler state in gun:info/1 result"
  https://github.com/ninenines/gun/pull/336

- All PRs included in 2.1.0-nordix1.

The cowlib dependency is updated to:
https://github.com/Nordix/cowlib/releases/tag/2.13.0-nordix2


## 2.1.0-nordix1 (2024-04-03)

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
