# Fourier Series Visualization

## Description

This is an interactive web-based application that visualizes the Fourier Series, a fundamental concept in mathematics and signal processing. It demonstrates how complex periodic waveforms (like a square or sawtooth wave) can be approximated by summing up a series of simple sine waves.

The visualization is built entirely with HTML, Tailwind CSS for styling, and plain JavaScript for the animation logic on an HTML Canvas.

## How It Works

The animation shows a series of rotating circles, called "epicycles."
- Each circle represents a single sine wave (a term) in the Fourier series.
- The radius of a circle corresponds to the amplitude of that sine wave.
- The rotation speed of a circle corresponds to the frequency of that sine wave.
- The tip of the final rotating arm draws the resulting waveform over time.

## Features

* **Multiple Waveforms:** Visualize the construction of a Square Wave, Sawtooth Wave, and Triangle Wave.
* **Adjustable Complexity:** Use the "Number of Terms" slider to control how many sine waves are used in the approximation. Observe how the resulting waveform becomes more accurate as you add more terms.
* **Logarithmic Slider:** The slider for the number of terms is logarithmic, allowing for fine control with fewer terms and the ability to quickly jump to a large number of terms (up to 200).
* **Animation Control:** Play and pause the animation to inspect the state of the epicycles at any moment.
* **Resizable Layout:** Drag the central divider to resize the control panel and the visualization canvas.

## How to Use

1.  **Open `index.html`** in any modern web browser.
2.  **Select a Waveform:** Use the "Waveform Type" dropdown to choose between Square, Sawtooth, or Triangle.
3.  **Adjust Terms:** Move the "Number of Terms" slider to see how the complexity affects the resulting wave.
4.  **Play/Pause:** Use the button to start or stop the animation.

