# OpenBender_SDK
An open source SDK for the OpenFTC android app.

## Features
none

## Future Features
- Devices
  - *Pretty much the same as the current FTC device support but with some extra features*
  - __UNLIKE NORMAL APP, VOLTAGE CHANGES DO NOT CHANGE THE AMOUNT OF CURRENT SUPPLIED TO THE DEVICES__
  - Motors
    - Encoder Support
    - Virtual Encoder Support (Tracks value without encoder, but instead a `double` that increases or decreases with motor rotations)
    - Run by Time/ Power
  
  - Gyroscope
  - Servos
    - Same as Motors
  - Light
    - Set brightness
  
- Console (synced with client and server)
  - Log Data
  - Save Data into File

- Values Viewer (synced with client and server)
  - Create Entry
  - Remove Entry
  - Read Entry
  - Create JSON Entry

- Communication
  - Send data to client or server
  - Send files to client or server
  - Recieve data from client or server
  - Recieve files from client or server

- Canvas
  - Set Pixel
  - Draw Line
  - Draw Rect
  - Draw Eclipse
  - Get Input
  - Set Color
  - Draw Text (no custom fonts)
  - Save Canvas as File
  
- File Support (files synced with client and server at start of connection)
  - Local Android file system access
    - Read Files
    - Write Files
