# Neural Audio Stem Separation

This is an extension for [Deezer Spleeter](https://github.com/deezer/spleeter) to be run in Google Colab, using Google Drive as data storage.

`input` value may be
1.   Path to an individual audio file located in your Google Drive.
2.   Path to a directory in your Google Drive, containing multiple audio files. Each audio file found in the directory will be individually processed.
3.   Single YouTube URL
4.   Multiple YouTube URLs separated by spaces. Audio track from each youtube video will be individually processed.

Input will be separated to 4 stems: vocals, drums, bass and other. Stems will be saved as WAV files to your Google Drive (`output_dir`).
