# Standalone Branch Router

This adds a basic standalone branch Session Smart Router to your configuration. 

## Step 1 - Platform
Begin by selecting from one of the SSR [certified+ platforms](https://www.juniper.net/documentation/us/en/software/session-smart-router/docs/about_certified_platforms) listed.

## Step 2 - WANs
Select the number of WAN interfaces to be used on the device (1-3). If LTE is available on your platform, choose if it should be enabled in your configuration.

## Step 3 - Interfaces
Set available options for your interfaces.

## Step 4 - Generate Config
Select the generate config icon at the top of the page, and proceed to configuration. Validate and commit to finish adding the new router to running configuration.

## Port Details
This template assumes WAN1 on your device will be connected to a network providing it DHCP address assignment, and with connectivity to your conductor.

It will configure a LAN interface providing a DHCP server to connected endpoints. From the LAN, the router local GUI and CLI will be accessible at `192.168.128.1`, unless explicitly disabled in your LAN interface inputs.

For each device, below are the ports that will be assigned.

### Juniper SSR120

![Juniper SSR120](https://raw.githubusercontent.com/128technology/interfacemaps/master/img/Juniper%20SSR120.jpg)

### Juniper SSR130

![Juniper SSR120](https://raw.githubusercontent.com/128technology/interfacemaps/master/img/Juniper%20SSR130.jpg)

### Silicom Madrid 90500-0151-G61

![Silicom Madrid 90500-0151-G61](https://raw.githubusercontent.com/128technology/interfacemaps/master/img/Silicom%20Madrid%2090500-0151-G61.jpg)

### Lanner 1515-128T

![Silicom Madrid 90500-0151-G61](https://raw.githubusercontent.com/128technology/interfacemaps/master/img/Lanner%201515-128T.jpg)