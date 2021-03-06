## Satisgo SDK

[![Go Report Card](https://goreportcard.com/badge/github.com/drymonsoon/satisgo)](https://goreportcard.com/report/github.com/drymonsoon/satisgo)
[![Build Status](https://travis-ci.org/drymonsoon/satisgo.svg?branch=master)](https://travis-ci.org/drymonsoon/satisgo)
[![Docs](https://img.shields.io/badge/docs-current-brightgreen.svg)](https://godoc.org/github.com/drymonsoon/satisgo)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/drymonsoon/satisgo/blob/master/LICENSE.md)



This is an SDK for the Satispay Business API.

It's not ***production*** ready but all the functions are there.

Obviously since every call has go to the the Satispay endpoint, making an https request, this cannot be done syncronously with you page loading, but it can be done asyncrounous and nothing bad can happen.

## Roadmap

- [ ] Strengthen security with `http.Transport` & `tls.Config` structs. The fundation work has been done, PR welcomed
- [ ] Shorten methods name
- [ ] Make it thread safe
- [ ] Create middleware for popular web-framework (gin/echo/martini...)

## Installation

```bash
go get github.com/drymonsoon/satisgo
```

## Usage

- examples are coming


## Documentation

- https://godoc.org/github.com/drymonsoon/satisgo
- [Satispay API](https://s3-eu-west-1.amazonaws.com/docs.online.satispay.com/index.html)

## Warning

This library is licenced MIT: everyone can use, improve it, change it and make a lot of money on it.
You cannot sue me if something goes wrong, you take all the responsability using this.
