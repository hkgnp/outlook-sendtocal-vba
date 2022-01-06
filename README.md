# Overview

This script captures the default calendar, and filters out only the next 3 months, and sends it as a `.ical` file to an email of your choice (set in line `47`), when a specific event is triggered.

# Installation

1. Navigate to `Options`.
2. Go to `Customise Ribbon`.
3. Under Main Tabs (on the right) click on `Developer` and ensure that it's checked.
4. Go back to the main ribbon and click the `Developer` tab.
5. Click on `Visual Basic` (icon on the far left).
6. Copy and paste the code from [here](https://github.com/hkgnp/outlook-sendtocal-vba/blob/master/VbaProject.OTM) to the window that is open and click save.
7. Go to your calendar and set up an appointment. The script will be triggered when the appointment happens. So if you want the calendar to be sent to you every evening at 5pm, set up a recurring 5pm appointment.
8. Before clicking `Save & Close`, **you must assign the appointment to the category `cal`**. If the category has not been created, go ahead to create it. You can do so by clicking on the `Categorise` button and clicking `All Categories`. Click `New`, and create a category `cal`. Any color is fine. Click `Ok`, and click on `Categorise` again and assign the appointment to the category `cal`.
