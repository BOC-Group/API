---
docid: release_notes
description: An overview of the release notes
slug: /release-notes
---

# Developer Portal Release Notes R28

| Product | Version |
| ------- | :-----: |
| ADOXX   |  28.0   |
| ADONIS  |  13.0   |
| ADOIT   |  14.0   |

## General

- Dropped support for IE 11!
- Improved Stability and Security
- Customer & Project Feedback
- For in-depth details see [What's New in ADONIS](https://docs.boc-group.com/adonis/en/docs/13.0/news/)


## REST API

- New `version 2.1` was introduced. All changes listed below are available only for 2.1 version
- Possibility to add own REST extensions using ADOxx REST framework features
- Read APIs to <a href="https://developer.boc-group.com/adoxx/en/REST-API/API-Reference/Repository-API/API-modelling-objects" target="_self">get relations of modelling instances.</a>
- <a href="https://developer.boc-group.com/adoxx/en/REST-API/Authentication/apis-authentication-tokenbased" target="_self">Token based configuration</a> is now optional
- HATEOAS links can be disabled in configuration and can be managed per request using Prefer header
- New attribute parameter in <a href="https://developer.boc-group.com/adoxx/en/REST-API/API-Reference/Repository-API/API-repository-read/#/Objects/getObjectgroup" target="_self">object groups</a> (to control which of the visible attributes should be retrieved)
- New <a href="https://developer.boc-group.com/adoxx/en/REST-API/API-Reference/Users/API-users" target="_self">/me</a> endpoint to get information about current user (only available when using Basic authentication or OAuth 2.0)
- New <a href="https://developer.boc-group.com/adoxx/en/REST-API/API-Reference/Scenarios/Scenarios" target="_self">/scenarios</a> endpoint to get list of scenarios enabled for current security context
- New <a href="https://developer.boc-group.com/adoxx/en/REST-API/API-Reference/Repository-API/API-models/#/Repository%20read%20APIs/getModel" target="_self">addBoundingBox</a> parameter when retrieving SVG model images to additionally retrieve information about artefact keys for each item in SVGs
- Language independent name for ENUM and ENUMLIST attributes is now returned
- New <a href="https://developer.boc-group.com/adoxx/en/REST-API/API-Reference/Views/Views" target="_self">View-specific</a> endpoints
- Better RWF support (addition of chainID and RWF metastate in results)
