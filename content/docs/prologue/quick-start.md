---
title: "Quick Start"
description: "One page summary of how to start a new Doks project."
lead: "This instruction manual will help you get started with the basic features that the application has to offer."
date: 2020-11-16T13:59:39+01:00
lastmod: 2020-11-16T13:59:39+01:00
draft: false
images: []
menu: 
  docs:
    parent: "prologue"
weight: 110
toc: true
---

## Requirements

{{< alert icon="👉" text="Vertafore FSC Rater™ is required." >}}

Minimum system requirements:

- 1 gigahertz (GHz) or faster 32-bit or 64-bit processor.
- 2 gigabyte (GB) RAM (32-bit) or 4 GB RAM (64-bit).
- 1 GB available hard disk space.
- Network card

## Installation

{{< alert icon="👉" text="FSC Utilities Plugin is a stand-alone application and can be run without the need for installation procedure" >}}

## Start a new mileage profile

What is a mileage profile?
- A mileage profile (or profile in short) is used to store a set of mileages and the application do not have the limitation on the number of profiles that can be created. 
- Each profile contains a set of mileages (06 drivers, extra 02 presets and a minimum mileage). Each one couples together a pair of values, which is one-way 
miles and annual mileage

### Create a new profile

To create a new profile, simply click the New button on the main tab. Then, enter your desired profile name and click OK.
![](https://fsc-utilities-plugin.netlify.app/images/create-new-profile.png)

### Change directories

{{< btn-copy text="cd my-doks-site" >}}

```bash
cd my-doks-site
```

### Install npm packages

{{< btn-copy text="npm install" >}}

```bash
npm install
```

### Start development server

{{< btn-copy text="npm run start" >}}

```bash
npm run start
```

Doks will start the Hugo development webserver accessible by default at `http://localhost:1313`. Saved changes will live reload in the browser.

## Other commands

Doks comes with commands for common tasks. [Commands →]({{< ref "commands" >}})
