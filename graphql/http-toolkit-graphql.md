# HTTP Toolkit GraphQL Schema

## Title
HTTP Toolkit GraphQL API

## Description
HTTP Toolkit is an open-source HTTP debugging and interception tool for Windows, Linux, and Mac. While HTTP Toolkit's primary server interface is REST-based (exposed at `http://localhost:45456`), its data model is rich and well-suited for GraphQL representation. The httptoolkit-server and httptoolkit-ui components communicate via a structured model of HTTP exchanges, interception rules, proxy sessions, and application integrations.

This schema is a conceptual GraphQL representation of the HTTP Toolkit data model, derived from the open-source codebase at https://github.com/httptoolkit and the documented API surface at https://httptoolkit.com/docs/.

## Endpoint / Docs URL
- Documentation: https://httptoolkit.com/docs/
- Server source: https://github.com/httptoolkit/httptoolkit-server
- UI source: https://github.com/httptoolkit/httptoolkit-ui

## Notes on GraphQL Support
HTTP Toolkit does not expose a native GraphQL API endpoint. The local server (`httptoolkit-server`) provides a REST API over localhost for controlling the proxy, managing interception rules, and launching applications. The `httptoolkit-ui` is an Electron-based frontend that communicates with this local server.

This schema is a **conceptual GraphQL schema** that faithfully models the HTTP Toolkit domain as understood from:
- The REST API definitions in `httptoolkit-server/src/api/`
- The TypeScript types and store models in `httptoolkit-ui/src/model/`
- The Mockttp library (https://github.com/httptoolkit/mockttp) which underpins the proxy rules engine

The types cover: HTTP exchange lifecycle (request, response, body, headers), proxy sessions, interception rules and matchers, rule actions (passthrough, mock, breakpoint), interceptors (browsers, applications, Docker, Android), certificates, and API integrations.

If HTTP Toolkit ever exposes a GraphQL endpoint, this schema would be a reasonable starting foundation.
