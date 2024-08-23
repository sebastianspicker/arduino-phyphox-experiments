# Arduino and Phyphox Experiments

This repository contains a collection of Phyphox experiment files designed for integration with Arduino projects. These experiments enable real-time data collection and visualization using the Phyphox app on your smartphone. Each file corresponds to a different type of sensor or input that can be connected to an Arduino microcontroller.

## Files

The following Phyphox files are included in this repository:

- **accelerometer_plot_v1-2.phyphox**: This file is designed for experiments involving the measurement and visualization of acceleration data. It can be used to monitor movements and detect changes in orientation.

- **analog_input_plot_v1-2.phyphox**: This file enables the capture and display of analog inputs. It's perfect for projects that involve sensors like potentiometers, light-dependent resistors (LDR), or any other analog sensors connected to the Arduino.

- **gyroscope_plot_v1-2.phyphox**: This file allows you to measure and visualize rotational motion using a gyroscope sensor. It’s useful for experiments that require tracking the angular velocity or the orientation of an object.

- **light_plot_v1-2.phyphox**: Use this file to measure ambient light intensity. It’s ideal for projects where the comparison of light levels under different conditions is required.

- **magnetometer_plot_v1-2.phyphox**: This file facilitates the measurement and visualization of magnetic fields, which can be used for experiments in magnetism or for detecting the presence of metallic objects.

- **pressure_plot_v1-2.phyphox**: This file is designed for the measurement and visualization of pressure data. It’s particularly useful in experiments that study air pressure changes or in environmental monitoring projects.

- **temperature_plot_v1-2.phyphox**: This file allows for the measurement and display of temperature data. It’s perfect for monitoring temperature changes in different environments or in experiments that involve thermal properties.

## How to Use

To use these files in your Arduino projects:

1. **Download the Phyphox App**: Make sure you have the Phyphox app installed on your smartphone. It is available on both Android and iOS platforms.

2. **Download the `.phyphox` Files**: Choose the relevant `.phyphox` file from the `phyphox_files` directory in this repository and download it to your smartphone.

3. **Set Up Your Arduino**:
    - Connect the appropriate sensor to your Arduino according to the experiment you want to perform. For example, connect an accelerometer for the accelerometer experiment, a light sensor for the light experiment, and so on.
    - Ensure that your Arduino is properly programmed to send the sensor data to your smartphone via Bluetooth or a serial connection that Phyphox can interpret.

4. **Import the `.phyphox` File**: Open the Phyphox app, navigate to the 'Import' section, and select the file you downloaded. This will load the pre-configured experiment, ready to interact with your Arduino setup.

5. **Start Your Experiment**:
    - Begin data collection by running the experiment in the Phyphox app.
    - Observe the real-time data visualizations directly on your smartphone. Each experiment is pre-configured to plot the data in a way that is most useful for that particular type of sensor.

6. **Analyze the Results**: After completing the data collection, you can analyze the recorded data within the Phyphox app or export it for further analysis in other tools like Excel or MATLAB.

## Detailed Project Information

For step-by-step guides, detailed circuit diagrams, Arduino code examples, and explanations of each experiment, please visit the original project page on [astro-lab.app](https://astro-lab.app/arduino-und-phyphox/). This page provides comprehensive instructions on how to integrate these experiments into your own projects.

## License

This project is licensed under the GPL-3.0 license. See the `LICENSE` file for more information.
