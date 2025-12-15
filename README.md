# Arabic Phonetic Keyboard for Android

This is a simple Android application that adds Arabic Phonetic keyboard layouts for physical keyboards. It allows you to type in Arabic using a standard English (US or UK) physical keyboard connected to your Android device, using a phonetic mapping (e.g., pressing 'a' types 'ا', 'b' types 'ب').

> **⚠️ IMPORTANT:** This application **ONLY** works with physical external keyboards (e.g., Bluetooth keyboards, USB keyboards, or keyboard cases for tablets). It does **NOT** add a layout to the on-screen software keyboard (like Gboard or SwiftKey).

<img src="./preview.svg" />

## Features

- **Phonetic Layout**: Types Arabic characters based on their phonetic English equivalents.
- **Physical Keyboard Support**: Designed specifically for hardware keyboards (Bluetooth or USB) connected to Android devices.
- **Multiple Layouts**:
  - Arabic Phonetic (based on US Keyboard)
  - Arabic Phonetic (based on UK Keyboard)

## Installation

1.  Clone this repository or download the source code.
2.  Open the project in Android Studio.
3.  Build and run the application on your device.

## Usage

Once installed, you need to configure your physical keyboard to use the new layout:

1.  Connect your physical keyboard to your Android device.
2.  Go to **Settings** > **System** > **Languages & input**.
3.  Under **Physical keyboard**, tap on your connected keyboard.
4.  Tap on **Set up keyboard layouts**.
5.  Scroll down and select **Arabic Phonetic (US)** or **Arabic Phonetic (UK)** depending on your physical keyboard layout.

Now, when you switch your keyboard language to Arabic (usually by pressing `Ctrl + Space` or `Shift + Space` depending on your device), the keys will map phonetically to Arabic characters.

## Layout

The layout is based on the Arabic Phonetic Keyboard by Omar Al Zabir.

For a visual reference of the layout mapping and to try it online, please visit: [https://arabic.omaralzabir.com/](https://arabic.omaralzabir.com/)

## Building from Source

To build this project, you need Android Studio or the Gradle command line tools.

```bash
./gradlew assembleDebug
```

## FAQ

### What is the difference between US and UK keyboards?

The main difference is the physical layout of certain keys, such as the "Enter" key shape and the location of symbols like `@`, `"`, `~`, and `\`. Choose the layout that matches your physical keyboard to ensure symbols are mapped correctly.

### Does this replace my normal on-screen keyboard?

No. This app only provides layouts for **physical** keyboards connected to your device. Your on-screen software keyboard (Gboard, SwiftKey, etc.) will remain unchanged.

### Can I use this with other languages (Italian, Spanish, etc.)?

Currently, this project only includes Arabic Phonetic layouts for US and UK keyboards. If you need support for other physical keyboard layouts (like Italian, Spanish, German, etc.), contributions are welcome! Please feel free to open a Pull Request.

This project is forked from [custom-keyboard-layout](https://github.com/ris58h/custom-keyboard-layout). You can refer to that repository for examples on how to implement layouts for other languages.

### I installed the app, but I can't find it in my app drawer. Where is it?

This application does not have a user interface (UI) or an icon in the app drawer. It works in the background by adding a new keyboard layout option to your system settings. Follow the [Usage](#usage) instructions to enable it.

### How do I uninstall the app?

Since the app doesn't have an icon in the app drawer, you can uninstall it via the system settings:

1.  Go to **Settings** > **Apps** > **See all apps**.
2.  Find **Arabic Phonetic Keyboard** in the list.
3.  Tap on it and select **Uninstall**.

### Is it safe?

Yes. This app is open-source and does not require any sensitive permissions (like internet access or reading your contacts). It simply provides a mapping file for the Android system to interpret physical keyboard presses.
