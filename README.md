Water Leak Warning Blueprint
Purpose:
This blueprint is designed to monitor a water leak sensor and provide warnings through speakers and mobile notifications every hour if water is detected. Additionally, it sends a notification if the sensor becomes unavailable.

Features:

Hourly Checks: The automation triggers every hour to check the water leak sensor's status.
Water Detection Alerts: If water is detected, it will:
Play a warning sound on a selected speaker.
Announce a warning message using Google Translate TTS.
Send a mobile notification with critical sound.
Display a popup message on a specified device.
Sensor Unavailability Alerts: If the sensor is unavailable, it will send a mobile notification indicating the sensor's status.
Configuration Options:

Water Leak Sensor: Select the sensor to monitor for water leaks.
Speaker: Choose the speaker to use for playing the warning sounds.
Notification Device: Select the device to receive mobile notifications.
Repeat Count: Set the number of times the warnings should be repeated.
Media Content ID: URL to the media file to play as the warning sound.
Volume Level: Adjust the volume level for the warning sound.
How to Use:

Import the Blueprint:
Create a new file warning_vvs.yaml in the config/blueprints/automation/vvs_warning/ directory of your Home Assistant configuration.
Paste the blueprint code into the file.
Restart Home Assistant: Go to Configuration -> Server Controls and restart Home Assistant.
Create an Automation:
Go to Configuration -> Automations & Scenes.
Click on + New Automation and select Blueprint.
Choose the "Water Leak Warning" blueprint.
Fill in the required fields (sensor, speaker, notification device, etc.) and save the automation.
This blueprint ensures that you are promptly alerted to any water leaks and notified if the sensor is not functioning, helping you take immediate action to prevent potential water damage.

Installation:

Installation:
Don't forget to add in configuration.yaml
browser_mod:
And download in HACKS: browser_mod 2
