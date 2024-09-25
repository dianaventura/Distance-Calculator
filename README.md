# Distance Calculator 

## Overview

This guide will walk you through the steps to run a Python script using Google Colab that calculates the driving distance (in miles) between postcodes and Robert Gordon University (Garthdee House). This process involves using the Google Maps API.

## Prerequisites

1. A Google account
2. Access to the Excel file containing the postcodes
3. A Google Maps API key (instructions on how to obtain this are below)

## Step-by-Step Instructions

### 1. Getting the Google Maps API Key

To use the Google Maps API, you need an API key. To get your key:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. If you don’t have a project, click **Create Project** and name it.
3. Once the project is created, select it from the dropdown at the top of the screen.
4. In the navigation menu on the left, select **APIs & Services** > **Library**.
5. Search for “Google Maps API” or "Directions API" and enable it for your project.
6. Next, go to **APIs & Services** > **Credentials** and click **Create Credentials** > **API Key**.
7. Copy the generated API key to use in the code later.
   
Optional - You may want to restrict the key to prevent misuse. Under **API restrictions**, select "Google Maps Directions API" to allow access only for this purpose.


### 2. Running the Script on Google Colab

1. Once the notebook opens, follow the instructions within the notebook:
   - Upload the Excel file containing the postcodes.
   - Insert your Google Maps API key into the code where prompted.
