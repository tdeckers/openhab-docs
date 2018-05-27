---
layout: documentation
title: SW-ZCS-1 - ZWave
---

{% include base.html %}

# SW-ZCS-1 Cord Switch
This describes the Z-Wave device *SW-ZCS-1*, manufactured by *CBCC Domotique SAS* with the thing type UID of ```cbcc_swzcs1_00_000```.

# Overview


## Channels

The following table summarises the channels available for the SW-ZCS-1

| Channel | Channel Id | Category | Item Type |
|---------|------------|----------|-----------|
| Switch | switch_binary | Switch | Switch | 

### Switch

The ```switch_binary``` channel supports the ```Switch``` item and is in the ```Switch``` category.



## Device Configuration

The following table provides a summary of the 1 configuration parameters available in the SW-ZCS-1.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Switch All |  |

### Parameter 1: Switch All



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Disabled |
| 1 | Switch on only |
| 2 | Switch off only |
| 255 | Fully enabled (Default) |

The manufacturer defined default value is 255 (Fully enabled (Default)).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The SW-ZCS-1 supports 2 association groups.

### Group 1: Group 1


This group supports 5 nodes.

### Group 2: Group 2


This group supports 5 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| Linked to BASIC|
| COMMAND_CLASS_SWITCH_ALL_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_ASSOCIATION_V1| |
| COMMAND_CLASS_VERSION_V1| |

---

Did you spot an error in the above definition or want to improve the content?
You can [edit the database here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/236).