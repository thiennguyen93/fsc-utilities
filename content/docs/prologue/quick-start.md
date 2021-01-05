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

## Start a new mileage profile

What is a mileage profile?
- A mileage profile (or profile in short) is used to store a set of mileages and the application do not have the limitation on the number of profiles that can be created. 
- Each profile contains a set of mileages (06 drivers, extra 02 presets and a minimum mileage). Each one couples together a pair of values, which is one-way 
miles and annual mileage

### Create a new profile

To create a new profile, simply click the New button on the main tab. Then, enter your desired profile name and click OK.
![create-new-profile]({{< ref "/" >}}images/create-new-profile.png)

### Input driver's mileage to current profile

You can input mileage for each driver or get the number directly from FSC Rater. To import from FSC Rater, please follow these steps
- Open your quote in FSC Rater, then change to **Vehicle View**.
- Make sure that you have entered the corect One Way Miles and Annual Milage for each driver.
- Hold *Shift* key and click on a driver to import one way miles and annual mileage of the selected driver.
- Repeat the previous step to import mileages for other drivers.

{{< alert icon="ℹ" text="<strong>Important note</strong>: The mileage will be compared to the <strong>MIN</strong> value, whichever is higher is imported. In case you want to skip the comparison and get the exact mileages, hold <em>Control + Shift</em> key instead of <em>Shift<em> key." >}}

{{< img-simple src="input-milage-directly.png" alt="Square" class="border-0 rounded-circle" >}}


### Transfer mileage from application to FSC Rater

The application is able to link and identify which driver is asigned to each vehicle in order to match and transfer the correct mileages of that driver. To do this, please follow the simple steps
- Select the profile that you want to use.
- Hold *Ctrl* key and Click on the vehicle → The One way miles and Annual mileage of the assigned driver is transfered to FSC Rater.
- Repeat the previous step to fill mileage for other drivers.
{{< alert icon="👉" text="If you change the driver/vehicle assignment in FSC Rater, repeat the steps above to update the new mileages" >}}
