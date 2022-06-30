# Go CLI Template

## Overview

This is my template for a well formed CLI in Go.

* [rs/zerolog](https://github.com/rs/zerolog) for logging (this is new to me, replacing logrus)
* [spf13/cobra](https://github.com/spf13/cobra) to plumb the CLI
* [spf13/viper](https://github.com/spf13/viper) for configuration
  * CLI parameters can be done via file, command line, or environment variables (precidence in that order)
* Functions and code blocks are timed and logged
* Testing

The methodologies and patterns coded herein are not the only way to craft a well-formed CLI, and there is plenty of room to discuss whether
it is actually "well-formed". This is just _my_ way.
Use this as you see fit. Replace the pieces that don't work for you. Let me know if you have "better" ways of doing things.
I'm not dogmatic about this; in fact, I'm always excited to see (other|easier|better|different) ways of doing things.
Sometimes those things will wrap around my brain better than what I'm doing now. This is progress! I may modify
this template in the future as I learn more and as new modules become available.

## Quick Start

## Testing

## See Also

* [pete0emerson/go-rest-api-template](https://github.com/pete0emerson/go-rest-api-template) is a similar project for a well-formed REST API in Go.

## TODOs

* Make sure go install works
* Allow user to use brew to install