# coap-mux [![Build Status](https://travis-ci.org/dereulenspiegel/coap-mux.svg)](https://travis-ci.org/dereulenspiegel/coap-mux)

This package provides basic support for routing based on path and method for
CoAP server.

## Installation

`go get github.com/dereulenspiegel/coap-mux`

## Usage

Create a new router with `NewRouter()` and add routes with `NewRoute()`,
`Handle(path, handler)` or `Path(string)`. The returned route object can be
configured further.