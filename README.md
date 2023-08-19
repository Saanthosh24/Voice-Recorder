# Audio Recorder

This is a Python script that uses the `pyaudio` and `wave` libraries to record audio from a microphone and save it to a WAV file.

## Usage

1. Run the `audio_recorder.py` script using a Python interpreter.
2. Enter the desired file name (including extension) for the recorded audio file.
3. Enter the duration (in seconds) for the recording.
4. The program will record audio and save it to the specified file.

## Features

- Records audio from a microphone and saves it to a WAV file.
- Allows customization of sample rate and chunk size for recording quality.

## Example

Enter the name of the audio file to save (e.g., recording.wav): my_audio.wav
Enter the recording duration in seconds: 5
Recording...
Recording finished.


## Note

- The recorded audio will be saved in the same directory as the script.
- Ensure you have the `pyaudio` library installed using `pip install pyaudio`.
- This is a basic audio recording example. For advanced features, consider handling error cases and providing more settings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
