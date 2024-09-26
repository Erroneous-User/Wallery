# Wallery

Wallery is a Windows console application that automatically changes your desktop wallpaper based on the current battery percentage. Enhance your desktop experience with dynamic wallpapers that reflect your device's battery status.

## Features

- Automatically changes wallpaper based on battery percentage.
- Lightweight and efficient.
- Easy to configure and use.

## Requirements

- Windows 10 or later
- C++17 or later
- Windows API

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/wallery.git
    ```
2. Navigate to the project directory:
    ```sh
    cd wallery
    ```
3. Build the application using your preferred C++ compiler.

## Usage

1. Run the application:
    ```
    wallery.exe
    ```
2. The application will start monitoring your battery percentage and change the wallpaper accordingly.

## Configuration

You can configure the wallpapers for different battery percentages by Adding/Removing manually the `/Wallpaper` file in the project directory. The file should look like this:

```Inside Wallpaper Folder:
{
    "wallpapers": {
        "10%": "Wallpaper/wallpaper10.jpg",
        "20%": "Wallpaper/wallpaper20.jpg",
        "30%": "Wallpaper/wallpaper30.jpg",
        ...
        "x% battery percent": "Wallpaper/wallpaperx.jpg"
    }
}

License
This project is licensed under the MIT License. See the LICENSE file for details.
