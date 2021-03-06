# Test HRV

A Garmin app that measures [HRV](https://en.wikipedia.org/wiki/Heart_rate_variability)(Heart Rate Variability) in a 3 minute test. Saves the output as a Connect IQ activity.

![TestHrvDemo](TestHrvDemo.gif)

## [Download](https://apps.garmin.com/en-US/apps/0bdc0e75-9baa-417a-8c9f-e976662a5d2e)

Link to the Garmin Connect IQ app store.

## Measurements

- [HRV](https://en.wikipedia.org/wiki/Heart_rate_variability) (Heart Rate Variability)
    - RMSSD - Root Mean Square of Successive Differences (beat-to-beat intervals)
    - pNN20 - % of successive beat-to-beat intervals that differ by more than 20 ms
    - pNN50 - % of successive beat-to-beat intervals that differ by more than 50 ms
    - beat-to-beat interval - reading coming directly from the watch sensor
    - HRV Successive Differences - difference between current and previous beat-to-beat intervals
    - SDRR - [Standard Deviation](https://en.wikipedia.org/wiki/Standard_deviation) of beat-to-beat intervals      
    - HRV RMSSD 30 Sec Window - RMSSD calculated for consecutive 30 second intervals    
    - HR from heartbeat - beat-to-beat interval converted to HR
- HR (Heart Rate)
  - minimum
  - average
  - maximum

## Viewing Results in Garmin Connect

Results are saved as a Garmin Connect activity category **Other** named **Test HRV**: ![TestHrvActivity](./Screenshots/TestHrvOverviewActivity.png)

The summary data is saved under Stats, section Connect IQ:

![SummaryStats](./Screenshots/SummaryStats.png) 

The extra graphs are shown next to the built-in Garmin graphs:
![Graphs](./Screenshots/Graphs.png)

## Requirements

- Connect IQ 3+ compatible device that tracks Heart Beat Interval data
- Measurements taken from the built-in optical HR sensor on the watch
  - For reliable readings minimise wrist movement
  - No strap required
- HR straps not supported
- The app starts measurements automatically as soon as stable sensor readings are detected 

## Dependencies

- Status Icons - [Font Awesome free](https://fontawesome.com/license) (SIL OFL 1.1 License) 
