# BLE Serial IOs Example

This is a simple app, which scans for BLE Peripherials and connect to them. The example works with NORDIC_UART_SERVICE.

# UUIDS

Here are the UUIDS:

SERVICE_UUID:           "6E400001-B5A3-F393-E0A9-E50E24DCCA9E"

CHARACTERISTIC_UUID_RX: "6E400002-B5A3-F393-E0A9-E50E24DCCA9E"

CHARACTERISTIC_UUID_TX: "6E400003-B5A3-F393-E0A9-E50E24DCCA9E"

# How to Run the App

Clone the source code and open it in xCode. You'll need an apple computer and an actual iPhone to run it. The emulator wont work with BLE. Connect an iPhone with a USB cable and run the application and scan for devices.

![Build Image](markdown.assets/README/Screenshot%202021-10-21%20at%204.22.24%20PM.png)

# Screenshots

Here are some screenshots of the iPhone communication with esp32 using Nordic UART Service.

## Splash Screen

This is the splash screen for the app.

![Splash Screen](markdown.assets/README/IMG_5085.png)

## Scan Screen

Press the scan button to start scanning for BLE Peripherals. Select a device to connect to it.

![Scan Screen](markdown.assets/README/IMG_5086.png)

## Communication Terminal Screen

Press the connect button to connect to the device.

![Communication Terminal Screen](markdown.assets/README/IMG_5087.png)

# Communication

Presing the Connect Button creates a connection with the esp32.

## Device Connected

![Device Connected](markdown.assets/README/IMG_5089.png)

## Exchanging Messages

Once Connected, then we can exchange text messages between iPhone and the esp32.

![Exchanging Messages](markdown.assets/README/IMG_5090.png)

## Esp32 Data Received

Here is a screenshot of the data received to the esp32, which is displayed on Serial monitor.

![Esp32 Data Received](markdown.assets/README/Screenshot%202021-10-21%20at%204.16.40%20PM.png)

## Info

This messages opens when the info button is presses on the top-right corner of the screen.

