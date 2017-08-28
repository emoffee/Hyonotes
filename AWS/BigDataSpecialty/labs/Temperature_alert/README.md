# Temperature Alert

The main goal of this lab is to run a IoT simulator on a EC22 instance, to send data to IoT device gateway, to query data against it and publish it as a notification to an SNS topic when a predefined event triggers.

Steps:
  * Create IoT cert & keys
  * Create simulation file and run it
  * Subscribe to the SNS topic 
  * Confirm data is flushed in
  * Create a IoT rule/event
  * Associate the notification action with the rule/event
  * Publich a state change to the device shadow
