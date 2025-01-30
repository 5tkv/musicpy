# MusicPy

MusicPy is a powerful and user-friendly desktop application designed to manage and manipulate your music files efficiently. It features file conversion, metadata retrieval, and batch renaming, all within an intuitive interface.

## Features

- **Add Directory**: Load a folder containing music files into the application.
- **File Conversion**: Convert audio files between MP3, WAV, and FLAC formats.
- **Metadata Retrieval**: Automatically fetch and update song metadata using the YouTube Data API.
- **Batch Rename**: Rename multiple files at once with a custom prefix.
- **Dark Theme UI**: Aesthetic and easy-to-use dark mode interface.

## Roadmap
- **Cover Art**: I am planning to add cover art for metadata editing.
- **UI Change**: Personally, I think the UI is a bit bland, I'll try updating it.
- **Nothing much else, any suggestions, LMK thanks <3**

## Installation

### Easy Installation (EXE)

1. Download the latest `MusicPy.exe` from the [releases page](https://github.com/marriedtopython/MusicPy/releases).
2. Run the installer and enter your YT API KEY from [GOOGLECLOUD](https://console.cloud.google.com/)
3. Launch MusicPy from your desktop or start menu.

### Advanced Installation (Source Code)

1. Clone the repository:
   ```bash
   git clone https://github.com/marriedtopython/MusicPy.git
   cd MusicPy
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

**NOTE: YOU WILL NEED AN API KEY FROM [GOOGLE CLOUD](https://www.console.cloud.google.com). This is REQUIRED, as metadata retrieval wouldn't work without this!**

## Dependencies

MusicPy requires the following Python libraries:

- `tkinter`
- `mutagen`
- `pydub`
- `requests`
- `threading`

Ensure that FFmpeg is installed for audio conversion:
```bash
sudo apt install ffmpeg  # Linux
brew install ffmpeg      # macOS
winget install ffmpeg    # Windows
```

## Usage

1. **Launch the application** and select a music directory.
2. **Convert files** to a preferred format (MP3, WAV, FLAC).
3. **Fetch metadata** for songs automatically.
4. **Rename files** in bulk with a custom prefix.
5. View logs and errors if any occur during processing.

## Screenshots

![image](https://github.com/user-attachments/assets/1bc1a93b-70b4-48f0-83fe-7c82dbdec2d5)

## Credits

- **Developed by:** marriedtopython

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

