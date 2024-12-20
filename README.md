# Mobile Barcode Scanner Web Application

## Overview
This is a web-based barcode scanner application that uses the device's camera to scan various types of barcodes in real-time. Built using QuaggaJS, this application provides a simple and intuitive interface for barcode scanning directly from a web browser.

You can try it at https://jvaz.github.io/CameraMobileBarcodeScannerTesting

## Features
- Real-time barcode scanning using device camera
- Support for multiple barcode formats:
  - Code 128
  - EAN-13
  - EAN-8
  - Code 39
- Responsive design that works on both mobile and desktop devices
- Camera controls (start/stop functionality)
- Immediate display of scanned results
- Preferential use of back camera on mobile devices

## Technical Stack
- HTML5
- CSS3
- JavaScript
- QuaggaJS (v0.12.1)

## Requirements
- Modern web browser with camera access support
- Device with camera (for scanning functionality)
- HTTPS connection (required for camera access in most browsers)

## Usage
1. Open the application in a web browser
2. Click the "Start Scanner" button to initialize the camera
3. Point the camera at a barcode
4. The scanned barcode value will appear in the "Scanned Result" section
5. Use the "Stop Scanner" button to halt the scanning process

## Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Security Notes
- The application requires camera permissions from the user
- Camera access is only available over HTTPS connections
- Camera stream is automatically stopped when scanning is disabled

## Development
To modify or enhance the application:
1. Clone the repository
2. Modify the HTML/CSS/JavaScript as needed
3. Test thoroughly on various devices and browsers

## License
MIT License

## Credits
- QuaggaJS Library: https://github.com/serratus/quaggajs