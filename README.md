# ww1
Smart Home Energy Analysis – Week 1

This project analyzes Smart Home energy usage recorded every 15 minutes across different appliances and activities.

✔ Dataset Overview

The dataset contains:

10 homes

12 months data

5 appliances (AC, TV, Washer, Fridge, Light)

Logs every 15 mins

Main columns:
timestamp, device_type, activity, power_watt, indoor_temp, outdoor_temp, status, user_present

✔ Key Steps Completed (Week 1)
✔ Data Preparation

Loaded CSV

Converted timestamp → datetime

Checked datatype

Verified missing values (no nulls)

Verified timestamp interval (15 mins gap)

✔ Feature Created

energy_kWh = (power_watt * 0.25) / 1000

✔ Exploratory Analysis Done

Energy per device

Energy per activity

Energy vs user presence

Device status analysis

Hour & Weekday patterns

✔ Balanced Sampling

Balanced datasets created for:

status

user_present

activity

Saved as CSV and plotted.

📊 Outputs

All charts available in /outputs/
