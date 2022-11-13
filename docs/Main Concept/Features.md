# Features

There are seven types of features available in Allxon Octo SDK — **Properties**, **States**, **Metrics**, **Events**, **Commands**, **Alerts** and **Configs**. Once a plugin is registered with the Agent, a new tab appears on the Portal. As shown in the screenshot below, each applicable feature has a corresponding “card” to display details.

![screen_telgrastates](../_img/screen_tegrastates.png)

## Properties
The **Properties **card displays the device information that is not frequently changed. By default, the information on this card is only updated when a plugin is registered for the first time.



![screen_properties](../_img/screen_properties.png)

:::tip Example device information:

- Hardware model name
- Firmware version
- Serial number
- Customer support contact

:::

:::info  Supported display types:

- String
- Table (a pop-up window)
- Link (URL or IP address)

:::

## States
The **States** card displays the device information that is frequently updated. Only the latest state is displayed and kept on the server.

![screen_states](../_img/screen_states.png)

:::tip Example device information:

- CPU/ GPU/ RAM utilization
- System temperature
- Power consumption

:::

:::info Supported display types:

- String
- Table (a pop-up window)
- Link (URL or IP address)

:::

## Events

The **Events** card displays the history of activities and events defined by the plugin. It allows users to view records over the last 90 days.

![screen_events](../_img/screen_events.png)

:::tip Example activities/events:

- Device health status
- Cyber threat activity
- Intrusion detection record

:::

## Metrics
The **Metrics** feature brings time-series data to the **Charts** card on the Portal. The Charts card displays time-series data in a trend. It allows users to drag the scrollbar to zoom in or zoom out on a time interval and view data over the last 90 days.


![screen_charts](../_img/screen_charts.png)

:::tip Example data types:

- System temperature
- Humidity
- Voltage

:::

## Alerts
The **Alerts** feature allows users to set thresholds for plugin-predefined alerts and then apply the settings to edge devices. If the threshold on an edge device is reached, the device plugin triggers alerts to Allxon Cloud to send notifications to the users.

![screen_alert_settings](../_img/screen_alert_settings.png) 

:::tip Example alerts

- CPU/GPU loading is higher than 95 %
- Battery level is lower than 10%

:::

:::info Supported Parameter Types:

- String ​
- Date/ time​
- Switch ​
- Check box​
- List (dropdown)
- Temperature (Fahrenheit/ Celsius)

:::

## Commands
The **Commands** feature allows users to send commands supported by the device plugin. Users can also set parameters for the commands on the Portal.

![screen_commands](../_img/screen_commands.png)

:::tip Example commands

- Power Switch/On/Off
- Set CPU/GPU Frequency Boundary

:::

:::info Supported Parameter Types:

- String ​
- Date/ time​
- Switch ​
- Check box​
- List (dropdown)
- ToS  (Term of Service)

:::

## Configs
The **Configs** feature allows users to configure device settings and set rules to automate operations.

![screen_configs](../_img/screen_configs.png)

:::tip Example configuration
- Scheduling power on at 9 am and power off at 6 pm
- Adjust GPU frequency to 16,000,000 Hz when the temperature reaches 96 degrees

:::

:::info Supported Parameter Types:
- String ​
- Date/ time​
- Switch ​
- Check box​
- List (dropdown)
- Temperature (Fahrenheit/ Celsius)

:::
