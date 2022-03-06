# Sensing Layer App



```text
The Sensing Layer App is an android application wich aim is to read biometric data from user's wearables
and transmit them to the Orion broker.

Acquired biometrics data are then elaborated by the [Fatigue Monitoring System](https://github.com/ramp-eu/Fatigue_Monitoring_System) and,
whenever it occurs,
message alerts will be sent by [Intervention Manager](https://github.com/ramp-eu/Intervention_Manager) 
so that they can be displayed on the Sensing Layer App.
```

## Contents

- [Sensing Layer App](#title)
  - [Background](#background)
  - [Install](#install)

## Background

```text
Application has been built and is compatible with the [Empatica E4](https://www.empatica.com/en-eu/research/e4/) wristband sensor.
Biometrics data that are transmited are:
 - Heartrate
 - Temperature
 - Acceleration
 - Galvanic skin response
```

## Install

```text
1. Download the SensingApp.apk file.

2. You can either navigate to your Download folder using a file browser app or
simply begin the install by clicking on the completed download in your mobile browser.

3. Android will ask you to grant permission to either the file browser or
your web browser to install the app. Grant the permission and it should 
bounce you back to the installation screen. If not, navigate back to your
Download folder after granting the permission to try again.

4. The app should be safely installed.

```

## Usage

```text
- Turn on the Empatica E4 wearable.

- Launch the Sensing Layer App.

- From the App navigate to "Settings": enter the Orion broker's
url address and port then click on "Save".

- Navigate to "Home" and press "Start".

- The Empatica status will turn to "Connected" and the data will
flow from the wearable to the Orion broker.

- A notification will arrive to the phone when a message from
the Intervention Manager will be received. Messages list is available by navigating to "Messages"
```

