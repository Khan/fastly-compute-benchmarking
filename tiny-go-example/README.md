# TinyGo Starter Kit for Go

[![Deploy to Fastly](https://deploy.edgecompute.app/button)](https://deploy.edgecompute.app/deploy)

Get to know the Fastly Compute environment with a basic starter that demonstrates routing, simple synthetic responses and code comments that cover common patterns.

**For more details about other starter kits for Compute, see the [Fastly developer hub](https://developer.fastly.com/solutions/starters)**

## QuickStart

- Install `tinygo` globally using instructions from https://tinygo.org/getting-started/install/
- `fastly compute serve` to run the service locally

## Features

* Allow only requests with particular HTTP methods
* Match request URL path and methods for routing
* Build synthetic responses at the edge

## Understanding the code

This starter is intentionally lightweight, and requires no dependencies aside from the [`"github.com/fastly/compute-sdk-go/fsthttp"`](https://github.com/fastly/compute-sdk-go) repo. It will help you understand the basics of processing requests at the edge using Fastly. This starter includes implementations of common patterns explained in our [using Compute](https://developer.fastly.com/learning/compute/go/) and [VCL migration](https://developer.fastly.com/learning/compute/migrate/) guides.

The starter doesn't require the use of any backends. Once deployed, you will have a Fastly service running on Compute that can generate synthetic responses at the edge.

It is recommended to use the [Fastly CLI](https://github.com/fastly/cli) for this template. The template uses the `fastly.toml` scripts, to allow for building the project using your installed Go compiler. The Fastly CLI should also be used for serving and testing your build output, as well as deploying your finalized package!

## Security issues

Please see our [SECURITY.md](SECURITY.md) for guidance on reporting security-related issues.
