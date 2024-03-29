# Demuxify

![App Main Screen](/images/app_screen.jpg)

Demuxify is a tool for audio source separation, allowing users to extract individual tracks from mixed audio recordings. You can separate audio sources from a song, giving you greater control over your audio editing and remixing projects.

## About Demucs

Demucs, developed by Meta Inc., is the underlying source separation model powering Demuxify. This model is designed to extract individual sound sources from complex audio mixtures. Demucs has gained recognition for its high-quality separation results and its ability to handle challenging audio recordings with multiple overlapping sources.

## Motivation

The main goal is to provide users with an easy-to-use interface for generating audio tracks by removing specific instruments, enabling the creation of play-alongs and karaoke versions of songs. You can remove vocals, drums, or other instruments from a recording, opening up new possibilities for practice, performance, and remixing.

## Features

- Separate audio tracks into individual sources.
- Remove specific instruments from mixed audio recordings.
- Easy-to-use interface.

## Getting Started

To get started:

1. Download the latest release.
2. Execute the installation program.
3. Run Demuxify.

## Usage

1. Select the audio file you want to separate. Supported formats: wav, ogg, mp3 and flac
2. Select the destination folder.
3. Choose a Demucs Model.
4. Choose the desired source separation mode.
5. Select the output format for the generated tracks. You can choose between wav, mp3 and flac.
6. Choose between different settings like clip mode, overlap, shifts, jobs, and device used.
7. Click "Separate" to begin the extraction process.

## Compatibility

- **Operating System**: The release is currently available for Windows operating system only.
- **Device Support**: The release supports Nvidia GPUs with Compute Capability 6.1 or higher, as well as CPU.

## Contributing

Demuxify is a personal project born out of necessity and driven by passion. But if you're interested in contributing, feel free to fork the repository and submit pull requests.

## License

Demuxify is licensed under the [MIT License](https://opensource.org/licenses/MIT), allowing for free and open-source use, modification, and distribution.
