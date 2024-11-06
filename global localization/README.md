# Global Localization

These samples show how to use the ZED SDK Global Localization module for **global scale localization on a real-world map**.

<p align="center">
  <img src="https://user-images.githubusercontent.com/32394882/230602944-ed61e6dd-e485-4911-8a4c-d6c9e4fab0fd.gif" />
</p>

## Overview

The samples provided using the Global Localization API are organized as follows:

- [Live](./live/) The Live sample demonstrates how to use the Global Localization API using both the ZED camera and an external GNSS sensor. It displays the corrected positional tracking in the ZED reference frame on an OpenGL window and the geo-position on a real-world map in a browser.

- [Recording](./recording/): The Recording sample demonstrates how to **record data** from both a ZED camera and an external GNSS sensor. The recorded data is saved in an SVO file and a JSON file, respectively. This sample provides the necessary data to be used by the Playback sample. 

- [Playback](./playback/): The Playback sample shows how to use the Global Localization API for global scale localization on a real-world map. It takes the data generated by the Recording sample and uses it to display geo-positions on a real-world map.

- [Map Server](./map%20server/): The Map Server Sample is utilized by other samples to display location data in a web browser.
