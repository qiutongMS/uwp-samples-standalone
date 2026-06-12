# UWP Samples Standalone

94 UWP samples extracted from [Windows-universal-samples](https://github.com/microsoft/Windows-universal-samples) for migration analysis.

These samples are a curated subset (the C# / `cs` variants only) selected per `UWP_Migration_Analysis_V4.xlsx` (102 target samples; 8 had no C# variant in the source repo and were skipped).

## Structure

Each sample retains its original `cs` folder structure from the source repo:

- `Samples/<SampleName>/cs/` — C# UWP project
- `SharedContent/` — shared resources used by multiple samples

## Samples

- Accelerometer
- ActivitySensor
- AdaptiveStreaming
- AdvancedCasting
- Altimeter
- ApplicationData
- ApplicationResources
- AppServices
- AssociationLaunching
- AudioCategory
- AudioCreation
- BackgroundActivation
- BackgroundMediaPlayback
- BackgroundSensors
- BackgroundTask
- BackgroundTransfer
- Barometer
- BasicInput
- BasicMediaCasting
- BasicSuspension
- BluetoothAdvertisement
- BluetoothLE
- BluetoothRfcommChat
- CameraAdvancedCapture
- CameraFaceDetection
- CameraFrames
- CameraGetPreviewFrame
- CameraManualControls
- CameraOpenCV
- CameraProfile
- CameraResolution
- CameraStarterKit
- CameraVideoStabilization
- Compass
- Compression
- ContentIndexer
- CredentialPicker
- CustomHidDeviceAccess
- CustomSensors
- CustomSerialDeviceAccess
- CustomUsbDeviceAccess
- DatagramSocket
- DataReaderWriter
- DeviceEnumerationAndPairing
- DisablingScreenCapture
- DisplayOrientation
- DpiScaling
- ExtendedExecution
- Geolocation
- Geotag
- Gyrometer
- HotspotAuthentication
- Inclinometer
- KeyCredentialManager
- LampArray
- LampDevice
- LanguageFont
- LightSensor
- LinguisticServices
- Magnetometer
- MIDI
- MobileBroadband
- MobileHotspot
- NetworkConnectivity
- NfcProvisioner
- NumberFormatting
- OCR
- OnDemandHotspot
- OrientationSensor
- Package
- Pedometer
- PenHaptics
- PersonalDataEncryption
- Personalization
- PlayReady
- PowerGrid
- PresenceSensor
- Printing
- ProximitySensor
- RadioManager
- RelativeInclinometer
- SimpleImaging
- SimpleOrientationSensor
- Store
- TextSegmentation
- TextSuggestion
- TouchKeyboard
- TouchKeyboardTextInput
- Unicode
- UserInfo
- WiFiScan
- XamlDataVirtualization
- XamlDeferLoadStrategy
- XamlFocusVisuals

## Purpose

This repo is used to:
1. Verify each sample builds as UWP
2. Analyze migration feasibility to WinUI 3 / Windows App SDK
3. Track which samples have WinAppSDK equivalents
