# MilMove Browser Benchmarking

This repository contains code written to run browser based performance benchmarking for the [MilMove](https://github.com/transcom/mymove) application.

The browser benchmarking tool relies on [Puppeteer](https://github.com/puppeteer/puppeteer) for automation using the Chrome browser, along with [Lighthouse](https://github.com/GoogleChrome/lighthouse) and the [devtools api](https://chromedevtools.github.io/devtools-protocol/) to gather relevant metrics. 

## License Information

Works created by U.S. Federal employees as part of their jobs typically are not eligible for copyright in the United
States. In places where the contributions of U.S. Federal employees are not eligible for copyright, this work is in
the public domain. In places where it is eligible for copyright, such as some foreign jurisdictions, the remainder of
this work is licensed under [the MIT License](https://opensource.org/licenses/MIT), the full text of which is included
in the [LICENSE.txt](./LICENSE.txt) file in this repository.

## Overview

The benchmarking tool previously lived inside of the mymove repository. Documentation for its use are available on the [wiki](https://github.com/transcom/mymove/wiki/How-to-use-the-benchmarking-script-with-Puppeteer-and-Lighthouse).

## Setup

The benchmarking tool is written in Javascript so it requires Node to be installed (version specified in `.node-version` currently matches what's in mymove) along with Yarn for managing dependencies.

If you've already setup the mymove app you should already have these pre-requisites.

To install the required packages simply run `yarn install` in your terminal from this directory.