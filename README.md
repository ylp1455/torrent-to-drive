# Torrent-to-Drive

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oIm2qu3g4Z5faA8e6gsl8Tdpl3dqcAgu?usp=sharing)

## Overview

Torrent-to-Drive is a Python script designed to simplify the process of downloading torrents directly to your Google Drive within a Google Colab environment. The script utilizes the libtorrent library for efficient torrent handling and seamlessly integrates with Google Drive for convenient storage.

## Features

- **Libtorrent Integration:** Utilizes libtorrent for efficient and reliable torrent downloads.
- **Google Colab Compatibility:** Works seamlessly within the Google Colab environment.
- **Google Drive Integration:** Saves downloaded content directly to a user-specified location in Google Drive.
- **User-Friendly:** Simple and interactive script that prompts users for the magnet link and destination path.

## How to Use

1. **Run the Script:**
   - Execute the script in a Google Colab notebook environment.

2. **Input Magnet Link:**
   - Enter the magnet link for the desired torrent.

3. **Specify Google Drive Path:**
   - Provide the path within your Google Drive where you want to save the downloaded file.

4. **Monitor Progress:**
   - The script will display download progress, rates, and peer information until the torrent is fully downloaded.

5. **Access Colab Notebook:**
   - Click the "Open in Colab" badge above to access and run the script directly in Google Colab.

## Dependencies

- `libtorrent`: Python bindings for the libtorrent library.
- `google.colab`: Required for mounting Google Drive within the Colab environment.

## Contributions

Contributions are welcome! If you have ideas for improvements or bug fixes, feel free to fork the repository and submit a pull request.

## Disclaimer

Ensure compliance with legal and ethical standards when using this script for downloading content. Respect copyright laws and adhere to the terms of service for both libtorrent and Google Drive.

## License

This project is licensed under the [MIT License](LICENSE).
