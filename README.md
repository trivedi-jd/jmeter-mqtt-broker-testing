# MQTT Broker testing using JMeter
Performing various tests on an MQTT broker to tests in performance when faced with bigger number of clients, requests or messages.

## Prerequisites
- JMeter 3.2 or above
- MQTT Jmeter plugin installed
- MQTT Broker (Public/Private)

## Directory Structure
Under the [tests](/tests/) directory, sub-directories are created for the test. For example, [Fan In Tests](/tests/fan_in/).

## Using the tests
### Opening the tests in Jmeter
Once the Jmeter and the MQTT plugin is installed follow below steps to open a .jmx file for testing MQTT Broker:\
- Open Jmeter -> File ->  Open -> Browse the .jmx file -> Open  

### Executing the tests in Jmeter
Once the file is opened in the Jmeter follow below steps to start executing the tests:\
- Enter values for the `server` & `port` variables -> Press the Green `Start` button on the toolbar to start the tests.

### Results
Once the test execution is over, Jmeter provides options for different listeners that can be added to the test plan. The tests results are collected by them.

## Helpful Links
- [Install Jmeter on ubuntu](https://www.geeksforgeeks.org/how-to-install-apache-jmeter-on-linux/)
- [MQTT Jmeter Plugin Repo](https://github.com/emqx/mqtt-jmeter)
- [HiveMQ Public Broker](https://www.hivemq.com/mqtt/public-mqtt-broker/)
- [More on MQTTx](https://mqtt.org/)