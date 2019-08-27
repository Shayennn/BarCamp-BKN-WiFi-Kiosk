# BarCamp Bangkhen WiFi Kiosk

Free WiFi Registration Kiosk for BarCamp Bangkhen 2019.

## How client uses this system.

1. Walk-in
2. Put IDCard or Passport in the reader and wait for the system to read it.
3. Take a photo and wait for the system to compare with your ID.
4. If the system tells your face is not match. Call staff to confirm your ID by tapping his/him KU student card on the passport reader.
5. The system will show WiFi Password for you. Take a photo and keep it secretly.
6. Enjoy surfing internet.

## Frontend

Run locally, not allow outside to access. Moreover, the system connects to Backend and Hardware by using HTTP API.

### Stack

* Bootstrap4

## Backend

### Stack

* Flask(Python)
* Google Cloud Storage(For storing encrypted personal secret data)

## Hardware

If we want to read the smartcard, passport, Mifare Card, or process a live video. We must install software on the client device.

### Stack

* Flask + OpenCV + face_recognition(Python)
* Contactless smc reader. (ACR122U)
* Contact smc reader.

## License
ALL RIGHT RESERVED.
