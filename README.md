# ![調ゲーム Shiragame](site/logo.svg)

**Release**

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/SnowflakePowered/shiragame/Publish%20new%20Shiragame%20database)&nbsp;[![GitHub release (latest by date)](https://img.shields.io/github/v/release/SnowflakePowered/shiragame)](https://github.com/SnowflakePowered/shiragame/releases/latest)

**API**

 [![Stone](https://img.shields.io/badge/stone-10.0.0-brightgreen.svg)](https://github.com/SnowflakePowered/stone)&nbsp;[![version](https://img.shields.io/badge/schema-2.0.0-blue.svg)](https://github.com/SnowflakePowered/shiratsu/blob/2.0.0/spec.md)&nbsp;![license](https://img.shields.io/github/license/snowflakepowered/shiragame.svg?maxAge=2592000)

## About

shiragame is a games database that allows you to look up game titles by ROM hash, or serial. Unlike other games databases, shiragame is updated consistently twice every week with the newest updates from its contributing cataloguing organizations. The latest release is always available at [https://git.io/JfFij](https://github.com/SnowflakePowered/shiragame/releases/latest/download/shiragame.zip).

shiragame also guarantees a semantically versioned schema for the convenience of its users. See [shiratsu](https://github.com/SnowflakePowered/shiratsu) for the database schema specification. 

A new revision of shiragame is published twice weekly, once at 00:00 UTC every Sunday, and 00:00 UTC every Wednesday. DAT file retrieval and database generation is automated with the help of [atsumare](https://github.com/SnowflakePowered/atsumare) and [shiratsu](https://github.com/SnowflakePowered/shiratsu) as a scheduled GitHub Action.

## Legal

The compiled data is courtesy of Redump, No-Intro, The Old School Computing Centre, and their respective contributors. shiragame or Snowflake is not affiliated with any of the aforementioned organizations.

Logs and database releases are released under the terms of the MIT license.
