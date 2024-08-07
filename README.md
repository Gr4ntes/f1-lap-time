# f1-lap-comparison

This repository contains a python application that can compare two F1 drivers' qualifying laps by plotting speed/distance graphs. The telemetry data is retrieved from the Fastf1 python package. The user is free to choose any session and any two drivers.

## Used environment

- Python == 3.8 
- fastf1 == 3.3.9
- PyQt6 == 6.7.0

## Usage and Screenshots

1. You should first choose a season: *this can be done by typing the year in the "Season" input field, "2024" for example.*
2. Next, the application might need some time to download the season schedule, when it is ready, the grand prix list will show in corresponding combo box.
3. After choosing the session, it will take a while to download the session info. When the download is finished, you can choose desired drivers and their colors from the list. The default colors correspond to the driver's team, but user can change this by clicking the color rectangle.
4. After pressing the "See Results" button, the result might look as shown below.

![Results-Image](images/results-image.png)
